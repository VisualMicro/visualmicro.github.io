---
layout: page
title: Sketch Compatability
excerpt: How to add new/existing source files to Arduino sketches, and how to delete files. Explains Arduino file types and examples for creating classes.
canonical_url: https://visualmicro.github.io/Introduction/SketchCompatability
permalink: /Introduction/SketchCompatability
nav_order: 6
search_exclude: false
nav_exclude: false
---
[//]: # (Add Link to previous page in a commend, in case of issues and for reference)
[//]: # (https://www.visualmicro.com/page/User-Guide.aspx?doc=Compatibility.html)

# Compatibility of Visual Micro Projects With the Original Arduino IDE

Visual Micro was designed with maximum compatibility in mind.

If you ever decide to move away from Visual Micro, back to the original Arduino IDE, or if you want to share your projects with people not having Visual Micro, then you should obey a few rules.

The following table shows features of project structure that are exclusive to Visual Micro. If you have used one of these features, then the table shows you, what to do, to make your project compatible with the Arduino IDE again.

| If you have...	| then change this...	| Reason |
| :---        |    :----   |    :----   |
| ...added source files to your project that are stored outside your project folder<br/>(see [Adding and Deleting Source Files](https://www.visualmicro.com/page/User-Guide.aspx?doc=Add-Source-Files.html "Adding and Deleting Source Files")) | Delete the files from your project, move the files into the project folder using Windows Explorer, and add them again to the project | Arduino IDE can only compile files in the same folder where the main .ino file is stored. |
| ...removed files from a project without deleting it from the hard disk <br/> (see [Adding and Deleting Source Files](https://www.visualmicro.com/page/User-Guide.aspx?doc=Add-Source-Files.html "Adding and Deleting Source Files")) | Delete the files from your hard disk | Arduino IDE has no concept of "projects" and compiles every .ino or .cpp file it finds in the disk folder. <br/> Files you had removed from your Visual Micro will become part of your sketch again, if you are using Arduino IDE. |
| ...gave your source files filenames that: <br/> + start with a number (like "0file.cpp")<br/> + contain blanks (like "my file.cpp")<br/> + are longer than 30 characters | Change the file names, so that they compile with these restrictions | Arduino IDE cannot handle source filenames that start with a digit, contain blanks, or are longer than 30 characters. |

