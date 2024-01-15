- ipykernel 
```
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=YOUR_ENV_NAME
```
- [Export and Create conda environment with yml](https://shandou.medium.com/export-and-create-conda-environment-with-yml-5de619fe5a2)
```
conda env export > environment.yml
```

To check envs
```
conda info --envs
```


## For bdss20k-dataset

### Yolov8s
https://github.com/ultralytics/ultralytics/issues/3920
https://docs.ultralytics.com/modes/val/#arguments
Run special commands to see version, view settings, run checks and more:

```
        yolo help
        yolo checks
        yolo version
        yolo settings
        yolo copy-cfg
        yolo cfg
```

https://github.com/ultralytics/ultralytics/blob/b6baae584c3cf8560300a8eb1c267f68e63554bb/docs/en/quickstart.md?plain=1#L189
https://github.com/ultralytics/ultralytics/blob/b6baae584c3cf8560300a8eb1c267f68e63554bb/docs/en/quickstart.md?plain=1#L189

Settings
/home/shakib/.config/Ultralytics/settings.yaml
