需要的文件
download_scannetv2.py
reader.py [数据解析最好 python2 的环境]
SensorData.py

#-o 保存文件路径
python download_scannet.py -o data --id scene0000_00
python reader.py --filename data/scans/scene0000_00/scene0000_00.sens --output_path scene0000_00