# TempClean
A simple C# WinForms .NET Framework application that cleans Windows temporary files.

Made using Windows Forms Application (.NET Framework) with .NET Framework 4.8 base.

![](/images/print1.png)


# How to download
Go to the Releases tab and download it, you don't need to install it, just run and it will work.

* Requires .NET Framework 4.8 to run
* Windows 7 or later

**Please note**: Any antivirus alert triggered by this program is a **false positive**.


# How to build

## Requirements

* Microsoft Visual Studio 2022
  * .NET desktop development
  * Universal Windows Platform development
* Windows 10 or later

## Preparation
Download the source zip, extract it, then open the extracted folder, and open and the solution file (**TempClean.sln**) with Visual Studio.

Before building, make sure the build settings are correct. You can set the build type (debug or release) and the target platform (x86, x64, or AnyCPU) in the project settings.

![](/images/build2.png)

## Building

To build the project, go to the 'Build' menu and select 'Build Solution' (or press Ctrl + Shift + B). This will compile all project files and generate the executable.

![](/images/build1.png)

After building, check the build output in the 'Output' window of Visual Studio. This will display any errors or warnings that occurred during compilation.

After successfully building, the executable will be generated in the project's output folder. By default, this is often a subfolder such as 'bin\Debug' or 'bin\Release' within the project folder.

You can run the executable directly from Visual Studio by clicking on 'Start' or by pressing F5. Alternatively, you can navigate to the output folder and run the executable manually.

![](/images/build3.png)
