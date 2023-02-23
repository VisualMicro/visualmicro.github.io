---
layout: page
title: Visual Studio or Atmel Studio
permalink: /Introduction/VisualStudioOrAtmelStudio
nav_order: 4
---
[//]: # (https://www.visualmicro.com/page/User-Guide.aspx?doc=Getting-started-which-IDE.html)

# Visual Studio or Atmel Studio?
Both Visual Studio and Atmel Studio provide identical Arduino compile, upload and debugging features.

Both programs, Visual Studio and Atmel Studio, are so called **IDE**s, **I**ntegrated **D**evelopment **E**nvironments

**Microsoft Visual Studio** is a commercial product from Microsoft that you can buy in software stores.

> :memo: **Note:** 
Microsoft also offers "[Visual Studio Community Edition](https://www.visualstudio.com/products/visual-studio-community-vs)", which is a fully featured, free version for teams of up to 5 developers or non-commercial applications.
Visual Micro is fully compatible with this edition.
For all users who don't have access to the commercial edition, Community edition is a great -and legal- option for using Visual Studio without any costs.

Atmel Studio is a similar product, is free of charge and can be [downloaded from the Atmel web page](https://www.atmel.com/tools/atmelstudio.aspx).

Both products are based on the same Visual Studio shell, which make them very similar in functionality, usage and appearance.

| If you..... | Then Choose this IDE |
| :---        |    :----   |
| ...want to use all kinds of Arduino compatible boards with processors from various manufacturers, not only from Atmel.<br/>...want to benefit from the newest functions offered by Microsoft<br/>...want to install additional add-ins and extensions from other manufacturers | Use Microsoft Visual Studio. <br/> Visual Studio together with Visual Micro based environment supports processors from multiple manufacturers. Boards supported include all Arduino and Arduino compatible boards, LaunchPads, Pic32, Chipkit, Intel Galileo etc.<br/>Since all these boards are Arduino compatible, you will be able to switch from one board to another while keeping your sketches.<br/>There is a large number of add-ins and extensions to Visual Studio that extend its functionality, from Microsoft as well as other manufacturers, most of them appear in [Visual Studio Gallery](https://visualstudiogallery.msdn.microsoft.com/).<br/><br/>There is a similar portal from Atmel, but Atmel's gallery contains much less add-ins and extensions to choose from. |
| ..want to use boards with processors manufactured by Atmel only<br/>...plan to switch to the professional development options offered by Atmel, like hardware debugging using JTAG | Use **Atmel Studio**.<br/><br/>Atmel Studio is free but is limited to processors from Atmel only. Boards supported include all genuine Arduinos like the Zero, Uno, Mega, Nano, Due, Yún etc. as well as compatible boards (clones) from other manufacturers, see this [Wikipedia article](https://en.wikipedia.org/wiki/List_of_Arduino_boards_and_compatible_systems#Arduino-compatible_boards).<br/>Boards with CPUs from other manufacturers, e.g. the Teensy boards, are not supported.<br/><br/>The current version of Atmel studio is normally based on a slightly older version of Microsoft Visual Studio.|

## More differences

### Advantages of Visual Studio over Atmel Studio
- Visual Studio has more features for advanced users, and if you already own a copy of Visual Studio it would be preferred.
- Visual Studio opens quickly and provide high speed [intellisense](https://en.wikipedia.org/wiki/Intellisense#IntelliSense) (not perfect but good).
- The plugin for Atmel Studio is currently lacking a few minor features such as **"Project > Show All Arduino Files"**. This feature is very useful for exploring library sources within the project and also aids the class explorers.
- Atmel Studio lacks some of the customization features of Visual Studio.
- Visual Studio [intellisense](https://en.wikipedia.org/wiki/Intellisense#IntelliSense) code suggestions are more accurate. Example: you will see Serial,Serial1 etc. for mega 2560 and just "Serial" for Uno, Atmel Studio will show Serial,serial1 etc. for all boards.
- Visual Studio provides web authoring tools within an Arduino sketch project for web based boards such as the Yun (both IDE's support web/network compile and upload).
- Visual Studio Express ([download link](https://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx)), Microsoft Expression Web ([download link](http://www.microsoft.com/en-us/download/details.aspx?id=36179)), or other web design tool can be used instead, so this is not a huge weakness for Atmel Studio.
- Visual Studio is required for other "non-Atmel" architectures such as Energia, Intel Galileo, and Chipkit.
- There are more IDE add-ins and extensions available for Visual Studio than for Atmel Studio (see **Tools > Extensions and Updates...** in Visual Studio, **Help > Atmel Gallery** in Atmel Studio.
- [Visual Studio Gallery](https://visualstudiogallery.msdn.microsoft.com/) offers a broader choice of add-ins and extensions that [Atmel Gallery](https://gallery.atmel.com/).

### Advantages of Atmel Studio over Visual Studio
- Visual Studio "disables" source code based on #defined conditions, which is very useful but can also be frustrating because it also disabled [intellisense](https://en.wikipedia.org/wiki/Intellisense#IntelliSense) within the disabled code. Atmel Studio does not do this.
- Atmel Studio has the simulator and various other tools.
- Visual Studio [intellisense](https://en.wikipedia.org/wiki/Intellisense#IntelliSense) understands only C++, Atmel Studio is naturally aware of the micro-controllers' native language.
- Atmel Studio knows about its own micro-controllers.

