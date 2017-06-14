# 安装uncrustify-pre-commit

## 安装uncrustify
```
  brew install uncrustify
```

# 配置uncrustify-pre-commit

1. 把bin文件夹拷贝到git仓库下面
2. 把`bin/hooks/pre-commit` 拷贝到`.git/hooks/`下面

# 使用
在`git commit`的时候会自动格式化代码

# 代码风格配置
编辑 `bin/uncrustify.cfg` 修改代码风格
