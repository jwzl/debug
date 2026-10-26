# 1. 持续采集视频流
```
v4l2-ctl -d /dev/video2 \
    --stream-mmap \
    --stream-count=0 --verbose
```

