### 1. Install libtorch

#### Recommended way
You can download the compatible version of libtorch from [Baidu Netdisk](https://pan.baidu.com/s/1DQGM3rt3KTPWtpRK0lu8Fg?pwd=8y4k) 
code: 8y4k,  then
```bash
unzip libtorch.zip
mv libtorch/ PATH/DYNAMIC_ORB/Thirdparty/
```
#### Or you can

```bash
wget https://download.pytorch.org/libtorch/cpu/libtorch-cxx11-abi-shared-with-deps-1.11.0%2Bcpu.zip
unzip libtorch-cxx11-abi-shared-with-deps-1.11.0%2Bcpu.zip
mv libtorch/ PATH/DYNAMIC_ORB/Thirdparty/
```

### 2. Build
```bash
cd DYNAMIC_ORB
chmod +x build.sh
./build.sh
```

### 3. Try

#### KITTI DATASET

```bash
/Examples/Stereo/stereo_kitti ./Vocabulary/ORBvoc.txt ./Examples/Stereo/KITTI00-02.yaml /home/tarun/northeastern/RSN/project/data_odometry_gray/dataset/sequences/00/
```