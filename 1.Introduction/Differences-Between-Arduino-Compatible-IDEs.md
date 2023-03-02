---
layout: page
title: Differences Between Arduino Compatible IDEs
excerpt: With so much choice of Arduino Development environments it can be hard to choose.  See our overview of the benefits and differences of the main ones here...
canonical_url: https://visualmicro.github.io/Introduction/Differences-Between-Arduino-Compatible-IDEs
nav_order: 5
search_exclude: false
nav_exclude: false
---
[//]: # (permalink: /1. Introduction/Differences-Between-Arduino-Compatible-IDEs)
[//]: # (https://www.visualmicro.com/page/Differences-Between-Arduino-Compatible-IDEs.aspx)

There are a variety of Arduino Compatible IDEs which are available today, below we break down Visual Micro vs the standard Arduino IDE and PlatformIO.

<table class="table table-striped" style="width: auto; margin-left: auto; margin-right: auto;">
<thead> 
<tr>
<th>Feature</th> <th class="text-center col-md-2">Visual Micro</th> <th class="text-center col-md-2">Arduino IDE</th> <th class="text-center  col-md-2">PlatformIO</th>
</tr>
</thead> 
<tbody>
<tr>
<td>Arduino IDE Compatible</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro is fully compatible with the Arduino IDE, allowing backwards compatibility for your projects." /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All Arduino IDE Sketches will work in the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - PlatformIO requires converting your INO to CPP, which makes it incompatible with the Arduino IDE" /></td>
</tr>
<tr>
<td>Supports Single INO</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro supports INO Sketches fully" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Arduino IDE supports INO Sketches fully" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - PlatformIO requires conversion from INO to CPP and additional headers adding" /></td>
</tr>
<tr>
<td>Supports Multiple INO</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro allows multiple INO files in line with the Arduino Specification" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Arduino IDE supports multiple INO files in tabs" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - PlatformIO requires conversion from INO to CPP and #include statements using" /></td>
</tr>
<tr>
<td>Sharing of variables and methods within multiple .ino files</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro allows sharing of variables and functions between your INO files" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Arduino IDE allows sharing of variables and functions between your INO files" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - PlatformIO requires conversion from INO to CPP and #include statements using" /></td>
</tr>
<tr>
<td>Supports C++ / C</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro supports C++ and C coding for embedded devices" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Arduino IDE supports C++ and C coding for embedded devices" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - PlatformIO supports C++ and C coding for embedded devices" /></td>
</tr>
<tr>
<td>
<p>Use Arduino Examples</p>
<p>(without code change)</p>
</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All examples can be used in Visual Micro with no alterations" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All examples can be used in Arduino IDE with no alterations " /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Examples have to be modified to work in PlatformIO" /></td>
</tr>
<tr>
<td>
<p>Use any historic Arduino project from the web</p>
<p>(without code change)</p>
</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All historic Arduino compatible projects are supported by Visual Micro without modification" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All historic project are supported by the Arduino IDE without modification" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - PlatformIO requires modification to INO files as a minimum to use Arduino projects from the web" /></td>
</tr>
<tr>
<td>Use same hardware configuration as the Arduino IDE</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All Arduino board options and board packages are fully supported in Visual Micro" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All board options and board packages are supported by the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Configuration is performed via an INI file with different options to standard Arduino pacakges" /></td>
</tr>
<tr>
<td>Use same library configuration as the Arduino IDE</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All Arduino Library specification options are supported in Visual Micro for seamless integration" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - All Arduino Library specification options are supported in the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Libraries may differ for PlatformIO configurations and often require additional files adding to the package" /></td>
</tr>
<tr>
<td>Cross-compatible code editing with Arduino IDE</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - You can edit code in Visual Micro and the Arduino IDE without any changes" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - You can edit code in the Arduino IDE without modification from Visual Micro" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Code changes are required to use the Arduino IDE again after PlatformIO" /></td>
</tr>
<tr>
<td>Requires additional config outside of normal Arduino usage</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - All Arduino configuration is supported in Visual Micro without changes" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - All Arduino configuration is supported in the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Additional INI file configuration is required which is not available for Arduino projects" /></td>
</tr>
<tr>
<td>Automatic Prototype Generation</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Function Prototypes are generated automatically, and can be disabled if required" /><br />(Optional)</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Function Prototypes are generated automatically" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Function Prototypes must be written with the code for correct compilation" /></td>
</tr>
<tr>
<td>Supports Shared Projects</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Shared Projects can be used to modularize code and use it in multiple cross platform projects" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Only libraries are available in the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Only libraries are avaiable in PlatformIO" /></td>
</tr>
<tr>
<td>Intellisense Code Suggestions</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Code Suggestions are generated in Visual Micro as you type" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Code Suggestions are available in the Arduino IDE 2.0" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Code Suggerstions are shown in PlatformIO as you type" /></td>
</tr>
<tr>
<td>
<p>Provides a Serial/USB debugger</p>
<p>(No code changes, all boards)</p>
</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro's unique Serial Debugger is simple to setup, and requires no code changes to your project, with many features available'" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Only Serial.println() can be used in the Arduino IDE, which requires modification to your sketch" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Only Serial.println() can be used in PlatformIO, which requires modification to your sketch" /></td>
</tr>
<tr>
<td>Supports Hardware Debug Probes</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro supports a wide variety of debug probes in a few clicks, as well as custom configuration available to suit any scenario " /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Arduino IDE 2 supports some debug probes with some configuration required for some boards" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - PlatformIO supports a range of debug probes using the INI configuration system" /></td>
</tr>
<tr>
<td>
<p>Supports CI/VC Tools</p>
<p>(TFS, Git, Azure Dev Ops, SVN etc..)</p>
</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - Visual Micro sits alongside a wide range of extensions for CI and VC from a variety of providers for Visual Studio" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Arduino IDE does not support CI or VC tools currently" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - PlatformIO sits alongside CI and VC extensions for VSCode" /></td>
</tr>
<tr>
<td>On-PC Unit Testing (without code change)</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - PC based Unit Testing Projects are supported in Visual Micro to allow cross platform compatible code to be tested without the hardware being required" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - No PC based Unit Testing features are currently available in the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - No PC based Unit Testing features are currently available in PlatformIO" /></td>
</tr>
<tr>
<td>On Chip Unit Testing (with Code Changes)</td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Currently no On-Chip Unit Testing is available in Visual Micro" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-No-Symbol.png" title="No - Currently no On-Chip Unit Testing is available in the Arduino IDE" /></td>
<td class="text-center"><img src="https://github.com/VisualMicro/visualmicro.github.io/raw/master/pics/Feature-Chart-Yes-Symbol.png" title="Yes - PlatformIO supports On-Chip unit testing via Serial using a Library which requires code changes" /></td>
</tr>
</tbody>
</table>
