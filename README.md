# npm-

- npm自动化前端脚本；

## 功能
-  gulp-less      ：less 编译；
-  gulp-ruby-sass ：sass 编译（可选配置）；
-  gulp-cached    ：缓存当前任务中的文件，只让已修改的文件通过管道；
-  gulp-uglify    ：js 压缩；
- gulp-rename    ：重命名；
-  gulp-concat    ：合并文件；
- gulp-jshint    ：js 语法校验；
- gulp-rev-append：插入文件指纹（MD5）；
- gulp-cssnano   ：CSS 压缩；
- gulp-imagemin  ：图片优化；
- browser-sync   ：保存自动刷新；
- gulp-autoprefixer：添加 CSS 浏览器前缀；
-  gulp-plumber   ：报错提示；

```
 automation/
   ├── dist/        编译后内容
   │   ├── css/
   │   ├── img/
   │   └──js/
   ├── src/         源代码
   │   ├── css/
   │   ├── img/
   │   └──js/
   ├── gulpfile.js  配置文件
   └── package.json 依赖版本管理
```
## 使用方法
git至本地后命令行行执行： npm install 下载依赖包；
