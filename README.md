# wepy-demo
vue+wepy  微信小程序 

### install
npm install -g wepy-cli     // 全局安装wepy-cli脚手架

wepy -v     // 查看版本号

wepy init standard wepy-demo    // 新建wepy-demo小程序项目，1.7.0之前的版本使用：wepy new myproject

cd wepy-demo    // 切换至项目目录

npm install     // 安装依赖

wepy build --watch      // 开启实时编译


### vscode wepy代码高亮
  1. 在 Code 里先安装 Vue 的语法高亮插件 Vetur。

  2. 打开任意 .wpy 文件。

  3. 点击右下角的选择语言模式，默认为纯文本。

  4. 在弹出的窗口中选择 .wpy 的配置文件关联...。

  5. 在选择要与 .wpy 关联的语言模式 中选择 Vue。

  6. 在VS Code编辑器设置中设置。 //文件-首选项-设置-settings.json settings.json "files.associations": { "*.wpy": "vue" }


### 教程参考：

https://my.oschina.net/wangnian/blog/2245468