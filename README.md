# 仓库说明

本仓库目的是拉取国外镜像

# 制造镜像

打TAG格式为：
* 前面加 `release-v`
* 版本号前面冒号改为 `-`

如：`nfs-provisioner:v4.0.8`

```shell
release-vnfs-provisioner-v4.0.8
```

# 拉取镜像

```shell
docker pull registry.cn-hangzhou.aliyuncs.com/laojia/images:release-vnfs-provisioner-v4.0.8 
```

