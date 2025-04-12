# Xmrig Without Donate Edition | Donate 0%

## Introduction
This is a modified version of Xmrig with the donation percentage set to 0%, allowing you to keep all the mining rewards.

Windows user can download the executable file directly from the `Releases` on the right.

## Compilation Steps
1. Open `x64 Native Tools Command Prompt for VS 2022`. I'm using VS2022 here, but you can adjust it according to your situation.
2. Create a `build` folder where you downloaded the files, then `cd` into the `build` folder.
3. Run `cmake .. -G "Visual Studio 16 2019" -A x64 -DXMRIG_DEPS=c:\xmrig-deps\msvc2019\x64`  
   Note: Change `c:\xmrig-deps` to your own folder path.
4. Generate the `Release` files: Switch to `Release` mode, then click to build `xmrig`. After the compilation is done, you can find `xmrig.exe` in the `build\Release` folder.

## Notes
- Ensure that your system environment is properly configured, including the installation of CMake and Visual Studio.
- If you encounter any issues during the compilation process, check if the dependency file paths are correct.

# Xmrig 无抽水版本

## 简介
这是一个修改过的Xmrig版本，将捐赠比例设置为0%，让你可以完全保留挖矿收益。

Windows系统可以直接在右边`Releases`下载exe可执行文件。

## 编译步骤
1. 打开x64 Native Tools Command Prompt for VS 2022。我这里是VS2022，视情况更改。
2. 在你下载的地方建立`build`文件夹，再`cd`到`build`文件夹。
3. 运行`cmake .. -G "Visual Studio 16 2019" -A x64 -DXMRIG_DEPS=c:\xmrig-deps\msvc2019\x64`  
   注意把`c:\xmrig-deps`改为你自己的文件夹。
4. 生成`Release`文件：先调至`Release`模式，再点击生成`xmrig`。等待编译好以后可以在`build\Release`文件夹中找到`xmrig.exe`。

## 注意事项
- 确保你的系统环境配置正确，包括CMake和Visual Studio的安装。
- 如果在编译过程中遇到问题，请检查依赖文件路径是否正确。
