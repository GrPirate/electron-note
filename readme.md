# Electron开发一个桌面应用（记事本）

1. 全局安装electron-forge

```
npm install -g electron-forge
```

2. 使用electron-forge初始化生成一个项目

```
electron-forge init notepad
```

3. 运行初始化项目

```
cd notepad
npm start
```

![]('./static/1.png')

## get start current project

1. 运行

```
npm start
```

2. 打包

```
npm run make
```
该命令会将文件打包到当前项目目录下的out文件夹下。