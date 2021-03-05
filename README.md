# flutter2_test1

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## 常用命令

检查flutter环境

```shell
flutter doctor
```

按照提示缺失环境即可

构建web版产品

```shell
flutter build web
```

如果需要编译成windows版，则需要下载 Visual Studio和对应C++的桌面开发套件(工作负载)

如果是使用idea新建的flutter项目，需要执行

```shell
flutter create --platforms=windows,macos,linux .
```

以便支持windows应用

开发过程中需要运行windows版本的话，终端执行

```shell
flutter run -d windows
```

构建windows产品

```shell
flutter build windows
```