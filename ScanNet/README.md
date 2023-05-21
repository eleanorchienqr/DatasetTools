需要的文件：`download_scannetv2.py`, `reader.py`, `SensorData.py`.
1. 下载数据集
#-o 保存文件路径
```
python download_scannetv2.py -o data --id scene0000_00
```
2. 提取彩色图、深度图、相机内参、位姿。
```
python reader.py --filename data/scans/scene0000_00/scene0000_00.sens --output_path scene0000_00
```
3. 解压缩 instance-filt 与 laber-filt 文件夹到指定路径。