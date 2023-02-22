# How the Software Tools Work Together
This page gives you an insight on how the different software tools work together.

## The Development Environment without Visual Micro
This is what a development environment looks like without Visual Studio/Atmel Studio and Visual Micro, as Arduino or your hardware vendor provides it:

![Original Software Toolset](https://www.visualmicro.com/documentation/pics/Toolchain-1.png "Original Software Toolset")

**IDE**  (**I**ntegrated **D**evelopment **E**nvironment) is the user interface you interact with. Most likely, this will be the original Arduino IDE.
The  **gcc toolchain**  consists of all tools that run in the background if you select "build" or "upload" commands.
These are mainly the gcc compiler and linker and the upload tool (normally avrdude.exe)

Since you are working with the IDE, you don't have to work with the toolchain programs directly, your IDE controls them in the background. However, the gcc toolchain is a set of independent command line programs (.exe's) that could be used without an IDE.

The  **USB VCP (Virtual Com Port) driver**  is also provided by Arduino or your board manufacturer and is responsible for communication between your board and the PC.

## The Development Environment with Visual Micro
This is how a development environment looks after you have installed Visual Studio/Atmel Studio and Visual Micro:

![VM/VS/AS Software Toolset](https://www.visualmicro.com/documentation/pics/Toolchain-2.png "VM/VS/AS Software Toolset")

 **Visual Studio** or **Atmel Studio** are your new **IDE** (**I**ntegrated **D**evelopment **E**nvironment). They will replace your original IDE, although you can still use it, it won't be uninstalled.
**Visual Micro** is an so called Extension that "lives" inside Visual Studio/Atmel Studio and adds functions to them that enable you to do Arduino programming. The  **gcc toolchain** remains unchanged, but is now controlled by Visual Micro and not by your original IDE anymore.
The **USB VCP (Virtual Com Port) driver** also remains the same.

## Adding New Platforms
*Visual Micro* lets you install additional development platforms from Arduino and other manufacturers, that support additional boards with different CPU architectures.

You can install platforms with *Visual Micro's* [Board Manager](https://www.visualmicro.com/page/User-Guide.aspx?doc=Board-Manager.html). Platforms will be installed side-by-side and chosen by Visual Micro depending on the board type you select:

![VM/VS/AS Software Toolset](https://www.visualmicro.com/documentation/pics/Toolchain-3.png "VM/VS/AS Software Toolset")

The drawing shows two platforms installed side by side, a **3rd party Board Platform** and the original **gcc toolchain** beneath it.
