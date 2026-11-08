## 开发支持音视频的设备

### 环境搭建

```bash
. ~/.espressif/tools/activate_idf_v6.1.sh

```

### 编译
```bash
idf.py -p /dev/ttyACM0 build flash monitor

```

### 烧录
```bash
idf.py -p /dev/ttyACM0 build flash monitor
```

### 配置参数
```bash
idf.py menuconfig
```
