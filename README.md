<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/104068298-878e9480-51b9-11eb-8ce3-3aecaddb6015.png">
  <br />
  Arduino Guide
</h1>

#### A guide covering Arduino devices such as the Arduino Uno and Arduino Nano. Along with the tools, applications and libraries that will make you a better and more efficient developer with Arduino devices. Also, learn about cool projects that you can build with your Arduino device.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

# Table of Contents

1. [Models of Arduino boards](https://github.com/mikeroyal/Arduino-Guide/blob/main/README.md#models-of-arduino-boards)

2. [Arduino Learning Resources](https://github.com/mikeroyal/Arduino-Guide/blob/main/README.md#arduino-learning-resources)

3. [Arduino Tools](https://github.com/mikeroyal/Arduino-Guide/blob/main/README.md#arduino-tools)

4. [Operating Systems for Arduino](https://github.com/mikeroyal/Arduino-Guide/blob/main/README.md#operating-systems-for-arduino)

5. [C/C++ Development](https://github.com/mikeroyal/Arduino-Guide/blob/main/README.md#cc++-development)

6. [Rust Development](https://github.com/mikeroyal/Arduino-Guide/blob/main/README.md#rust-development)


<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/111917911-9dcd9200-8a3f-11eb-8463-9c21514b4792.png">
</p>

# Models of Arduino boards

[Back to the Top](https://github.com/mikeroyal/arduino-Guide/blob/main/README.md#table-of-contents)

[Checkout the Arduino Starter Kit](https://store.arduino.cc/usa/arduino-starter-kit)

<img src="https://user-images.githubusercontent.com/45159366/104068309-8a898500-51b9-11eb-9265-beb5a28e649b.jpg">



[Checkout the Arduino Uno](https://store.arduino.cc/usa/arduino-uno-rev3)

<img src="https://user-images.githubusercontent.com/45159366/104068324-8eb5a280-51b9-11eb-942c-390f5b29b259.jpg">


**Arduino Uno Hardware Specs**

 - Microcontroller	ATmega328P
 - Operating Voltage	5V
 - Input Voltage (recommended)	7-12V
 - Input Voltage (limit)	6-20V
 - Digital I/O Pins	14 (of which 6 provide PWM output)
 - Flash Memory	32 KB (ATmega328P) of which 0.5 KB used by bootloader
 - SRAM	2 KB (ATmega328P)
 - EEPROM	1 KB (ATmega328P)
 - Clock Speed	16 MHz
 
 
 [Checkout the Arduino Nano](https://store.arduino.cc/usa/arduino-nano)
 
<img src="https://user-images.githubusercontent.com/45159366/104068320-8d847580-51b9-11eb-960d-8faa3ef525fc.jpg">


**Arduino Nano Hardware Specs**

 - Microcontroller	ATmega328
 - Architecture	AVR
 - Operating Voltage	5 V
 - Flash Memory	32 KB of which 2 KB used by bootloader
 - SRAM	2 KB
 - Clock Speed	16 MHz
 - Input Voltage	7-12 V
 - Digital I/O Pins	22 (6 of which are PWM)
 
 
## Arduino Learning Resources

[Back to the Top](https://github.com/mikeroyal/arduino-Guide/blob/main/README.md#table-of-contents)
 
[Arduino](https://www.arduino.cc/) is an open source electronic prototyping platform enabling users to create interactive electronic objects.
 
[Arduino Reference Manual](https://www.arduino.cc/reference/)
 
[Getting Started with Arduino](https://create.arduino.cc/getting-started)
 
[Arduino Education](https://www.arduino.cc/education)
 
[Arduino Store](https://store.arduino.cc/)
 
[Arduino Forum](https://forum.arduino.cc/)
 
[Arduino Courses on Udemy](https://www.udemy.com/topic/arduino/)
 
[Arduino Courses on Coursera](https://www.coursera.org/courses?query=arduino)
 
[Online Arduino Classes on Skillshare](https://www.skillshare.com/browse/arduino)
 
[Introduction to Arduino course on Pluralsight](https://www.pluralsight.com/courses/arduino-introduction)
 
[Arduino Training Courses on NobleProg](https://www.nobleprog.com/arduino-training)
 
[Arduino with Python course from Real Python](https://realpython.com/arduino-python/)

[200+ Arduino Projects on Instructables](https://www.instructables.com/Arduino-42/)


## Arduino Tools

[Back to the Top](https://github.com/mikeroyal/arduino-Guide/blob/main/README.md#table-of-contents)
 
[Arduino CLI](https://github.com/arduino/arduino-cli) is an all-in-one solution that provides builder, Boards/Library Manager, uploader, discovery and many other tools needed to use any Arduino compatible board and platforms.
 
[Arduino IDE](https://www.arduino.cc/en/software) is an open source integrated development environment(IDE) for the Arduino computing platforms based on easy-to-use hardware and software.
 
[Arduino Pro IDE](https://github.com/arduino/arduino-pro-ide) is a professional version of the Arduino IDE that brings more features for advanced users and developers. The project is currently in the experimently version.

[VSCode Arduino](https://github.com/Microsoft/vscode-arduino) is a VSCode extension for Arduino.  The Arduino extension makes it easy to develop, build, deploy and debug your Arduino sketches in Visual Studio Code, with a rich set of functionalities. 
 
[Gobot](https://gobot.io/) is a framework using the [Golang](https://golang.org/)  programming language for robotics, physical computing, and the Internet of Things(IoT).
 
[Tasmota](https://tasmota.github.io/docs) is an alternative firmware for [ESP8266](https://en.wikipedia.org/wiki/ESP8266) based devices with easy configuration using webUI, OTA updates, automation using timers or rules, expandability and entirely local control over MQTT, HTTP, Serial or KNX.
 
[Blynk](https://www.blynk.cc/) is a C++ library for embedded hardware. It works with over 400 hardware models such as Arduino, ESP8266, Raspberry Pi, Intel Edison/Galileo, LinkIt ONE, Particle Core/Photon, ARM mbed, etc.
 
[Arduino Thread](https://github.com/ivanseidel/ArduinoThread) is a library tha makes it simple to run Threads on Arduino.
 
[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.
 
[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. 

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[Chipyard](https://chipyard.readthedocs.io/en/latest/) is an open source framework for agile development of Chisel-based systems-on-chip. It will allow you to leverage the Chisel HDL, Rocket Chip SoC generator, and other [Berkeley](https://berkeley.edu/) projects to produce a RISC-V SoC with everything from MMIO-mapped peripherals to custom accelerators.

[The Eclipse Embedded CDT](https://github.com/eclipse-embed-cdt/eclipse-plugins) is a collection of plug-ins for Arm & RISC-V C/C++ developers.
[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.


# Operating Systems for Arduino

[Back to the Top](https://github.com/mikeroyal/arduino-Guide/blob/main/README.md#table-of-contents)

[HeliOS](https://www.arduino.cc/reference/en/libraries/helios/) is an embedded operating system that is free for anyone to use. While called an operating system for simplicity, HeliOS is better described as a multitasking kernel for embedded systems.

[FreeRTOS](https://freertos.org/) is a market-leading real-time operating system (RTOS) for microcontrollers and small microprocessors.

[Simba](https://simba-os.readthedocs.io/en/latest/getting-started.html) is a small OS for an Embedded Programming Platform like Arduino. It aims to make embedded programming easy and portable.

[Trampoline](https://github.com/TrampolineRTOS/) is a static RTOS for small embedded systems.

[DuinOS](https://github.com/DuinOS/DuinOS) is Framework (a wrapper) for use the FreeRTOSwith Arduino.

[VxWorks](https://www.windriver.com/products/vxworks) is an industry-leading real-time operating systems (RTOS) for building embedded devices and systems for more than 30 years.

[LynxOS](https://www.lynx.com/products/lynxos-posix-real-time-operating-system-rtos) is a native POSIX, hard real-time partitioning operating system developed by Lynx Software Technologies.

#  C/C++ Development

[Back to the Top](https://github.com/mikeroyal/arduino-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95024321-2b0a5f00-0637-11eb-9e94-0b1415162651.png">
  <br />
</p>


## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)

## C/C++ Tools

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems. 

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed. 

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language. 

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library. 

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).



## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Arduino-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Arduino-Guide/blob/master/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
