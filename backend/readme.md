# 后端环境管理

使用requirements.txt文件来管理项目的依赖

0. 创建并使用自己的环境（注：环境管理方法可以自己定，只要requirement.txt一样就可以了）

```bash
conda create -n myflaskenv python=3.9
conda activate myflaskenv # 你的环境名
```

1. 生成requirement.txt文件的命令：

```bash
pip freeze > requirements.txt
```

2. 安装依赖的命令

```bash
pip install -r requirements.txt
```
