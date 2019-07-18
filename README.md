# EDSR-tensorflow

## Training

```
python main.py --device 0 --model_name EDSR --data_dir D:/Dataset/DIV2K --exp_dir D:/tensorflow/experiments --exp_name EDSR_R16_X2 --num_res 16 --scale 2 --is_init_res --is_train 
```

## Test

```
python main.py --device 0 --model_name EDSR --data_dir D:/Dataset/SR_test --exp_dir D:/tensorflow/experiments --exp_name EDSR_R16_X2 --num_res 16 --scale 2 --is_test --dataset_name Set5 
```