# docker_aliy

aliy镜像服务仓库

## 拉取

```shell

docker login --username=dongcho registry.cn-hangzhou.aliyuncs.com

docker pull registry.cn-hangzhou.aliyuncs.com/chongd/env_qc:[镜像版本号]
```

## 现有镜像

### qingcheng_u1804:青城linux18.04环境docker： 8.049G
- qt5.14.2 vtk6.3+8.2 opencv4.12 pcl1.8
```shell
docker run -it -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix:ro -v /path_ws/:/data --name {name} [镜像版本号]
```
```shell
xhost +
```
```shell
qtcreator
```
