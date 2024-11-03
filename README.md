# NZYM
 Faster, Easier and Lighter Way of Creating Websites, Mobile and Desktop Applications, Be It for Business or Games... Introducing Nzym!!
 
 ![Nzym Logo](https://nzym.org/files/logo/logo.png)
 
 ## What is Nzym
 Nzym is a high-level programming language that is geared towards the development of media and web applications, both for the mobile and desktop platforms. The main philosophy of Nzym is to make coding easier, better and faster. This is through the adoption of a typing discipline that is weak but dynamic and compile tools that deploy with the use of some pre-built objects.


## Hello World
This is a simple Hello World program which will show an app window with the words "Hello World!" 
```nzym
Nzym Start;
Print Hello World!;
```

## Installation
Upon downloading the files, unzip them into your desired folder. Make sure you add the Bin folder to your PATH and you are good to go...

More information can be found on the [Nzym Official Website](https://nzym.org/).


## Basic Commands - Using Catalyst
### For the creation and building of Nzym programs and apps, you can use Catalyst in the following way:
```console
catalyst <COMMAND>
```

Commands:
 - create, -C, --create  Create a new Nzym package.
 - build, -B, --build    Compile the scripts into a library, program or content pages.
 - nzym, -N, --nzym      Access other Nzym tools available to the Nzym package.
 - help                  Print this message or the help of the given subcommand(s)

Options:
 - -h, --help     Print help
 - -V, --version  Print version
 
### The Catalyst Create Command 
```console
catalyst create <OPTIONS> <name_of_application>
```

Options:
  -c, --console <console>...  Develop a console application using Nzym terminal / catalyse
  -d, --desktop <desktop>...  Develop a multiplatform desktop application with NZYM GUI and CORE libraries
  -l, --library <library>...  Develop an Nzym library
  -m, --mobile <mobile>...    Develop a mobile application with Nzym and Cordova configurations
  -w, --web <web>...          Develop a web application using Nzym
  -h, --help                  Print help
 
### The Catalyst Build Command
```console
catalyst build
```

Options:
  -h, --help  Print help
  

## Executing Programs _(.nzex)_
These will run  through the use of the Catalyse program found in your Bin. You can also associate the extension **_.nzex_** to **catalyse.exe** to make it easier to run Nzym Applications from your desktop computer.

Executables are found in the app folder of your project folder once you have run the build command. This applies for Desktop and console app projects.