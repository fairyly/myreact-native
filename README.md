# myreact-native
react-native

## 搭建开发环境  
**Node NPM**  
 * 安装完node后建议设置npm镜像以加速后面的过程（或使用科学上网工具）。  
   注意：不要使用cnpm！cnpm安装的模块路径比较奇怪，packager不能正常识别！  
   npm config set registry https://registry.npm.taobao.org --global  
   npm config set disturl https://npm.taobao.org/dist --global  
   或者找到添加镜像的位置：nodejs安装目录/node_modules/npm/npmrc   
   添加：registry = https://registry.npm.taobao.org  
   
 * Yarn、React Native的命令行工具（react-native-cli）  
   Yarn是Facebook提供的替代npm的工具，可以加速node模块的下载。  
   React Native的命令行工具用于执行创建、初始化、更新项目、运行打包服务（packager）等任务。  
   npm install -g yarn react-native-cli
  
**安装Android Studio**  

 * 可以到 [谷歌开发者平台](https://developers.google.cn)下载安装
 
**测试安装**
  react-native init AwesomeProject  
  cd AwesomeProject  
  react-native run-android  
  Windows用户请注意，请不要在命令行默认的System32目录中init项目！会有各种权限限制导致不能运行！  

