## gulp 构建个人简历

> 这是一个基于 gulp 构建 html 个人简历的项目

### npm 环境检查

```
If they are not installed, follow the instructions here.
npm install --global gulp-cli
npm --version
npx --version
```

### 初始化新项目

> 需要全局安装`gulp-cli`和`gulp`

```
sudo cnpm install gulp gulp-cli -g
# 安装依赖
cnpm i
```

### 运行

```
gulp
```

代码结构

> 参考 views 的 index 首页

js 在 `src/js` 下面编写
css 在 `scss/\*`下面新建 scss 文件编写
views 在 `tpl/views` 下面编写

会进行热更新在 `src` 目录下生成相关文件
