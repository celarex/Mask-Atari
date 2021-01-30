# Mask-Atari

## Trained Examples 

(Left: Observations Right: Modified for human understanding)

Breakout

![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BreakoutBlack.gif)
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/Breakout.gif)

Asterix

![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/AsterixBlack.gif)
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/Asterix.gif)

## Hyper-parameter descriptions

### Scale

(Left: Scale 70 pixels Right: Scale 130 pixels)

![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderScale70.gif)
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderScale130.gif)

### Speed

(Left: Speed 10 pixels/frame Right: Speed 50 pixels/frame)

![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderSpeed10.gif)
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderSpeed50.gif)

### Number

(Mask number = 2)

![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderNumber2.gif)

(Loop Boundary)

![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderLoopBoundary.gif)

### Resolution

<!--
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BreakoutResolutionBlack.gif)
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BreakoutResolution.gif)
-->
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderResolutionBlack.gif)
![image](https://github.com/celarex/Mask-Atari/blob/main/Animations/BeamRiderResolution.gif)

|  Environment  |  Human  |  A2C-CNN(Full)  | A2C-CNN(Resolution Decay) |  A2C-CNN(Mask)  |  Random  |
|  ----  |  ----  |  ----  | ---- |  ----  |  ----  |
|  Assault  |  742  |  4428  | 1920 |  495  |  222  |
|  Asterix  |  8503  |  3765  | 2790 |  1888  |  210  |
|  Asteroids  |  47389  |  1844  | 1828 |  1362  |  719  |
|  BeamRider  |  16927  |  5486  | 4118 |  445  |  364  |
|  Breakout  |  30.5  |  381  | 369 |  119  |  1.7  |
|  Centipede  |  12017  |  3171  | 3207 |  2665  |  2091  |
|  MsPacman  |  6952  |  2131  | 1804 |  1200  |  307  |
|  Qbert  |  13455  |  9248  | 4420 |  549  |  164  |
|  SpaceInvaders  |  1669  |  817  | 757 |  487  |  148  |
|  StarGunner  |  10250  |  49395  | 43899 |  1661  |  664  |
|  ----  |  ----  |  ----  | ---- |  ----  |  ----  |


