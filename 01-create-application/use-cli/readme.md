##### 使用脚手架创建 Electron 项目

- electron-forge

  electron-forge 是可以进行 electron 项目的 创建，发布，安装 进行处理工具

  这里只说使用 electron-forge 如何进行创建一个 electron 项目

  其实非常的简单，我们可以使用 yarn 或者 npx 来调用 electron-forge

  我们以 npx 为例来作示例

  ```shell
  npx create-electron-app my-app
  ```

  my-app 就是我们的项目名/目录名

  成功之后，进入项目目录内

  ```shell
  cd my-app
  ```

  启动项目

  ```shell
  npm start
  ```

  启动成功，自动弹出 electron 窗口