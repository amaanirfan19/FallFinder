# wallet-detection-yolov8

- Trained over 500 images collected from Roboflow Universe as well as webscraping to increase diversity
- Applied various data augmentation methods to increase dataset size to over 1.5k.
- Used google colab's free GPU to speed up running time by 10x


Training output:
```250 epochs completed in 2.870 hours.
Optimizer stripped from runs/detect/train/weights/last.pt, 6.2MB
Optimizer stripped from runs/detect/train/weights/best.pt, 6.2MB

Validating runs/detect/train/weights/best.pt...
Ultralytics YOLOv8.0.106 🚀 Python-3.10.11 torch-2.0.1+cu118 CUDA:0 (Tesla T4, 15102MiB)
Model summary (fused): 168 layers, 3005843 parameters, 0 gradients
                 Class     Images  Instances      Box(P          R      mAP50  mAP50-95): 100% 4/4 [00:02<00:00,  1.42it/s]
                   all        100        102      0.948      0.961      0.975      0.844
Speed: 3.2ms preprocess, 3.6ms inference, 0.0ms loss, 2.1ms postprocess per image
Results saved to runs/detect/train
```

## Below are some videos predicted by the model on unseen data!
![dropped-wallet](https://github.com/amaanirfan19/FallFinder/assets/52991990/03133e8e-0ca5-4201-ba46-a33343a1dafd)


![dropped-purse](https://github.com/amaanirfan19/FallFinder/assets/52991990/866e2b64-d2db-4372-a6e8-bae328f975da)


![dropped_wallet-2](https://github.com/amaanirfan19/FallFinder/assets/52991990/d587e789-3e4f-4662-8a08-68af2e987a1b)
