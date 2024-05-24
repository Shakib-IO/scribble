```
# Visualization
import numpy as np
model.eval()
num_samples = 10
sample_count = 0

with torch.no_grad():
    for batch in test_loader:
        indices = np.random.randint(low=1, high=100, size=10) 
        inputs = batch['pixel_values'].to(device)
        labels = batch['label'].to(device)

        outputs = model(inputs)
        _, predicted = torch.max(outputs, 1)

        # Convert tensors to numpy arrays for visualization
        images = inputs.cpu().numpy()
        labels = labels.cpu().numpy()
        predicted = predicted.cpu().numpy()

        # Show images with their predicted and true labels
        num_images = len(images)
        fig = plt.figure(figsize=(25, 10))
        for i in range(num_images):
            ax = plt.subplot(1, num_images, i + 1)
            ax.imshow(images[i].transpose(1, 2, 0))  # Convert from (C, H, W) to (H, W, C)
            ax.axis('off')
            ax.set_title(f"Predicted: {predicted[i]}\nOriginal: {labels[i]}")
            sample_count += 1

            if sample_count >= num_samples:
                break

        if sample_count >= num_samples:
            break

plt.show()

```
