# npm-
npm自动化前端脚本；<br />
<br />
  包含功能：
    gulp-less      ：less 编译；<br />
    gulp-ruby-sass ：sass 编译（可选配置）；<br />
    gulp-cached    ：缓存当前任务中的文件，只让已修改的文件通过管道；<br />
    gulp-uglify    ：js 压缩；<br />
    gulp-rename    ：重命名；<br />
    gulp-concat    ：合并文件；<br />
    gulp-jshint    ：js 语法校验；<br />
    gulp-rev-append：插入文件指纹（MD5）；<br />
    gulp-cssnano   ：CSS 压缩；<br />
    gulp-imagemin  ：图片优化；<br />
    browser-sync   ：保存自动刷新；<br />
    gulp-autoprefixer：添加 CSS 浏览器前缀；<br />
    gulp-plumber   ：报错提示；<br />
    
  /automation      ：主目录<br />
    /dist          ：编译后目录结构<br />
      /css<br />
      /img<br />
      /js<br />
      /components<br />
    /src           ：源代码目录结构<br />
      /css<br />
      /img<br />
      /js<br />
      /components<br />
    /gulpfile.js   ：配置文件；<br />
    /package.json  ：依赖版本管理；<br />
    <br />
    <br />
git至本地后命令行行执行： npm install 下载依赖包；
