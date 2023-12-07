# SA-YOLOv7

paper on the way~

![result](https://github.com/maple0leaves/SA-YOLOV7/blob/master/img/result.png)

### Performance

Dataset：[hand_glove](https://pan.baidu.com/s/1APMrs7pjkuIFn4iSESul7A?pwd=esuk )

|   Model   | Size |   P    |   R    | map0.5:0.95 | FPS  |
| :-------: | :--: | :----: | :----: | :---------: | :--: |
| SA-YOLOv7 | 640  | 91.40% | 82.50% |   48.60%↑   | 72.2 |
|  YOLOv7   | 640  | 83.70% | 82.30% |   46.80%    | 89.2 |
|  YOLOv5m  | 640  | 89.30% | 84.2%  |    47.8%    | 67.5 |
|  YOLOv5l  | 640  | 86.9%  | 88.00% |   47.00%    |  59  |
|  YOLOv6n  | 640  | 79.10% | 79.00% |   46.30%    |  75  |
|  YOLOv6m  | 640  | 93.40% | 70.00% |   47.80%    | 46.6 |

### Testing&Training

[sa_yolov7.pt](https://pan.baidu.com/s/1zW3MG3RH6g2sy2nbhPv3CA?pwd=9645)

I use pycharm connect to my server ,when I fix code ,I run it directly in my pycharm,do not use command in  Terminal.If you like run in Terminal,mybe you should write commands by youself .

#### Testing

If you just want to try ,you should download sa_yolov7.pt,and change data/glove.yaml,test.py then run .if you want to test youself model ,you know ,just change paths .Also,you could ask me at issues.Welcome!

![data/glove.yaml](https://github.com/maple0leaves/SA-YOLOV7/blob/master/img/gloveyaml.png)

![test.py](https://github.com/maple0leaves/SA-YOLOV7/blob/master/img/test.png)

#### Training

![train.py](https://github.com/maple0leaves/SA-YOLOV7/blob/master/img/training.png)

#### environment

pytorch2.0,cuda11.8,ubuntu20.04

RTX3080Ti *8

### Reference

[WongKinYiu/yolov7: Implementation of paper - YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors (github.com)](https://github.com/WongKinYiu/yolov7)

[wofmanaf/SA-Net: Code for our ICASSP 2021 paper: SA-Net: Shuffle Attention for Deep Convolutional Neural Networks (github.com)](https://github.com/wofmanaf/SA-Net)

### Last

If you have any questions ,you could ask me at issuces.Welcome! I very happy I could  help you !

All of work finish by myself ,so if this work could help you ,please with my project link(https://github.com/maple0leaves/SA-YOLOV7/) Thank you!

