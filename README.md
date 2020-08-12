# color-ui

为了方便在微信小程序中使用[开源项目ColorUI](https://github.com/weilanwl/ColorUI/)样式，将ColorUI中的css库转为微信小程序中的自定义组件，方便开发者使用  
在构建项目使用gulp打包工具时，参考了[开源项目lin-ui](https://github.com/TaleLin/lin-ui)中编写的打包函数方法

## 声明

项目于2020年8月12日进行开发，由于时间问题只是完成了gulp打包工具的搭建，并开发了部分button组件，项目会持续进行开发

## 如何使用

下载此源码，使用微信开发者工具导入项目，将examples目录导入可以查看使用示例；若直接使用组件，直接复制dist目录到自己已新建的微信小程序项目中

## 参与编写

下载此源码，在src目录下编写组件，按上述**如何使用**中导入examples目录使用并预览编的的组件，在开发之前需启动gulp监听文件变化，运行命令:

```n
npm run watch
```

