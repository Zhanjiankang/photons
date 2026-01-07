# 图片链接转换指南

## 通用转换规则

GitHub原始链接格式：
```
https://github.com/{用户名}/{仓库名}/blob/{分支名}/photos/{图片路径}
```

可转换为以下两种图床链接格式：

1. raw.githubusercontent.com格式：
```
https://raw.githubusercontent.com/{用户名}/{仓库名}/{分支名}/photos/{图片路径}
```

2. jsdelivr CDN格式：
```
https://cdn.jsdelivr.net/gh/{用户名}/{仓库名}@{分支名}/photos/{图片路径}
```

## 实际示例

### 原始GitHub链接
```
https://github.com/Zhanjiankang/photons/blob/main/photos/111.png
```

转换为：

1. raw.githubusercontent.com格式 (推荐生产环境使用):
```
https://raw.githubusercontent.com/Zhanjiankang/photons/main/photos/111.png
```

2. jsdelivr CDN格式:
```
https://cdn.jsdelivr.net/gh/Zhanjiankang/photons@main/photos/111.png
```