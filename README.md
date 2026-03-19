# My QGIS Build
自己编译的QGIS二进制包分享

------

需要用QGIS的时候，经常遇到安装很费劲的情况，而且安装完成后居然有好几个G。尤其是Arm架构下，QGIS安装比较费劲。所以我就自己编译了几个**绿色版本**，解压即用，或者直接执行。

软件包可以在[Release](https://github.com/Zoulei-CSU/My_QGIS_Build/releases)下直接下载。

| 文件                                                         | 版本     | 大小 | 系统        | 备注说明                                                     |
| ------------------------------------------------------------ | -------- | ---- | ----------- | ------------------------------------------------------------ |
| [qgis_3.16_windows_x64.7z](https://github.com/Zoulei-CSU/My_QGIS_Build/releases/download/v0.1/qgis_3.16_windows_x64.7z) | 3.16 LTS | 45M  | Win64       | 无Python。                                                   |
| [qgis_3.34_python_windows_x64.7z](https://github.com/Zoulei-CSU/My_QGIS_Build/releases/download/v0.1/qgis_3.34_python_windows_x64.7z) | 3.34 LTS | 88M  | Win64       | 带Python，支持插件。                                         |
| [qgis_3.16_linux_glibc2.17_amd64.AppImage](https://github.com/Zoulei-CSU/My_QGIS_Build/releases/download/v0.1/qgis_3.16_linux_glibc2.17_amd64.AppImage) | 3.16 LTS | 95M  | Linux x64   | 无Python。GLIBC版本2.17，支持Centos 7这种老系统，新系统建议用2.28的。 |
| [qgis_3.16_linux_glibc2.28_x86_64.AppImage](./download/v0.1/qgis_3.16_linux_glibc2.28_x86_64.AppImage) | 3.16 LTS | 101M | Linux x64   | 无Python。GLIBC版本>=2.28。                                  |
| [qgis_3.28_python_linux_glibc2.28_x86_64.AppImage](https://github.com/Zoulei-CSU/My_QGIS_Build/releases/download/v0.1/qgis_3.28_python_linux_glibc2.28_x86_64.AppImage) | 3.28 LTS | 183M | Linux x64   | 带Python，支持插件。GLIBC版本>=2.28。                        |
| [qgis_3.16_linux_glibc2.28_aarch64.AppImage](https://github.com/Zoulei-CSU/My_QGIS_Build/releases/download/v0.1/qgis_3.16_linux_glibc2.28_aarch64.AppImage) | 3.16 LTS | 89M  | Linux Arm64 | 无Python。GLIBC版本>=2.28。aarch64架构。                     |

说明：

1. Win版本的解压即用（最好解压到无中文、无空格的路径下），解压后执行QGISLauncher.exe即可。
2. Linux下载的AppImage文件，可能需要手动添加可执行权限：`chomd a+x xxx.AppImage`
3. 如果Linux用户希望修改AppImage文件内容，直接解包即可：`./xxx.AppImage --appimage-extract`



------

版权协议：本仓库只是对开源工程进行了编译，请遵守QGIS、Qt等软件的原始版权协议。
