# yolov11-ncnn

## Benchmark.
| Model  | Infer time|
| ------------- | :-------------: |
| YOLOv5n  | 54 ms |
| YOLOv11n  | 48 ms |

## How to build and run
``` shell
mkdir build
cd build 
cmake ..
make 
./yolov11_ncnn ../data/bus.jpg
```

## Show
![show](./data/output.jpg)

## reference

<https://github.com/THU-MIG/yolov10><br>
<https://github.com/Tencent/ncnn><br>
<https://github.com/triple-Mu/ncnn-examples>
