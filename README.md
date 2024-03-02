# Roleplay-with-LanYangYang🐏 懒洋洋扮演

<div align="center">
![下载](https://cdn.zghhui.me/img/下载.jpg)



  <div>&nbsp;</div>
  <div align="center">
  </div>

</div>

# 简介

基于西游RolePlay的懒羊羊角色扮演

# 环境配置

## 开始

<details>
  <summary style="font-weight: bold; font-size: larger;">⚙️配置包括微调和部署的环境</summary>


新建环境-安装lmdeploy

使用 pip ( python 3.8+) 安装 LMDeploy，或者[源码安装](https://github.com/InternLM/lmdeploy/blob/main/docs/zh_cn/build.md)

```shell
conda create -n chatXY python=3.10 -y
pip install lmdeploy
```

LMDeploy的预编译包默认是基于 CUDA 11.8 编译的。如果需要在 CUDA 12+ 下安装 LMDeploy，请执行以下命令：

```shell
export LMDEPLOY_VERSION=0.2.0
export PYTHON_VERSION=38
pip install https://github.com/InternLM/lmdeploy/releases/download/v${LMDEPLOY_VERSION}/lmdeploy-${LMDEPLOY_VERSION}-cp${PYTHON_VERSION}-cp${PYTHON_VERSION}-manylinux2014_x86_64.whl
#比如pip install https://github.com/InternLM/lmdeploy/releases/download/v0.2.3/lmdeploy-0.2.3-cp310-cp310-manylinux2014_x86_64.whl
```

安装XTuner

```shell
cd train/Xtuner
pip install -e '.[all]'
```

安装其他依赖

```
pip install -r requirements.txt
```

</details>

# 快速开始

<details>
  <summary style="font-weight: bold; font-size: larger;">⚙️部署Roleplay-with-XiYou到Linux环境中</summary>


## 环境配置

新建环境-安装lmdeploy

使用 pip ( python 3.8+) 安装 LMDeploy，或者[源码安装](https://github.com/InternLM/lmdeploy/blob/main/docs/zh_cn/build.md)

```shell
conda create -n chatXY python=3.10 -y
pip install lmdeploy
```

LMDeploy的预编译包默认是基于 CUDA 11.8 编译的。如果需要在 CUDA 12+ 下安装 LMDeploy，请执行以下命令：

```shell
export LMDEPLOY_VERSION=0.2.0
export PYTHON_VERSION=38
pip install https://github.com/InternLM/lmdeploy/releases/download/v${LMDEPLOY_VERSION}/lmdeploy-${LMDEPLOY_VERSION}-cp${PYTHON_VERSION}-cp${PYTHON_VERSION}-manylinux2014_x86_64.whl
#比如pip install https://github.com/InternLM/lmdeploy/releases/download/v0.2.3/lmdeploy-0.2.3-cp310-cp310-manylinux2014_x86_64.whl
```
