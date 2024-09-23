# 项目管理 - drepo

## 查看所有项目信息

```bash
xlings drepo
```

**输出示例**

```bash
	drepo lists

--- d2python ---
git	: git@github.com:d2learn/d2python.git
url	: https://github.com/d2learn/d2python
name	: d2python
tags	: python
profile	: 动手学d2python项目
--- d2x ---
git	: git@github.com:d2learn/xlings.git
url	: https://github.com/d2learn
name	: d2x
tags	: template
profile	: drepo的模板配置文件
--- xlings ---
git	: git@github.com:d2learn/xlings.git
url	: https://github.com/d2learn/xlings
name	: xlings
tags	: tools, build, auto-exercises, pkg-manager
profile	: 技术、实验、练习、自学类项目, 快速构建和管理工具
--- d2ds ---
git	: git@github.com:d2learn/d2ds.git
url	: https://github.com/d2learn/d2ds
name	: d2ds
tags	: c++, data-structures
profile	: 强调动手实践的数据结构学习项目，其中包含在线书籍、公开课、练习代码等子项目
--- d2cpp ---
git	: git@github.com:d2learn/d2cpp.git
url	: https://github.com/d2learn/d2cpp
name	: d2cpp
tags	: c++
profile	: 动手学C++项目

	run xlings drepo [drepo_name] to download
```

## 项目下载和使用

> 以下载[d2ds](https://github.com/Sunrisepeak/d2ds)并运行dslings练习代码为例

### 下载项目

下载d2ds项目到当前目录

```bash
xlings drepo d2ds
```

### 安装目标项目依赖

在下载项目的根目录运行命令安装该项目的依赖

```bash
cd d2ds
xlings install
```

### 运行项目练习

运行d2ds项目中的dslings代码练习

```bash
xlings dslings
```