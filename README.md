# mbed_NucleoF072RB

Now is easier than ever to use **mbed** library offline with eclipse and GNU ARM. In this repo you will find a eclipse project with mbed library for ST [**NucleoF072RB**](http://developer.mbed.org/platforms/ST-Nucleo-F072RB/) board.

##Prerequists

You need to have installed [**GNU ARM** compiler]https://launchpad.net/gcc-arm-embedded) and [**Eclipse C/C++** IDE](http://www.eclipse.org/downloads/packages/eclipse-ide-cc-developers/lunasr1a) within [**GNU ARM Eclipse Plugin**](http://gnuarmeclipse.livius.net/blog/), check the following links in order to make the setup

- [Installing the GNU ARM compiler ( _spanish and english_ )](http://hotboards.org/index.php/es/blog/20-spanish/blog/st/81-pt1-instalando-compilador-windows)
- [Installing windows driver and update firmware ( _spanish and english_ )](http://hotboards.org/index.php/es/blog/20-spanish/blog/st/82-pt2-instalando-openocd-windows)
- [Installing Eclipse with GNU ARM Plugin ( _spanish and english_ )](http://hotboards.org/index.php/es/blog/20-spanish/blog/st/84-toolchain-pt3-proyectos-con-eclipse)

##Working with the project

There are two ways to integrate the template project into eclipse and start to working, both has similar aproaches and work well

###Import project to workspace

This method is easy, just clone or download ( _dont forget to unzip it_ ) the repository into your eclipse workspace ( _the folder where you have all your eclipse projects_ ), then open eclipse and goto to menu **File -> Import...** at the new window select **General -> Existing Projects into Worspace** and then **Next**.

In the next part select the option **Select root directory:** and **Browse...** the project folder wich i assume is in your workspace by right now, just click on **Finish**, open the file **main.cpp** and start coding mbed style. Have fun!!.

If you need more imformation about importing projects in eclipse just check the following [**post** ( _spanish only_ )](http://hotboards.org/index.php/es/blog/20-spanish/blog/st/117-importando-proyectos-en-eclipse)

###Cloning the project using Egit

First of all you need to install the plugin Egit in your Eclipse IDE, then goto menu **File -> Import...**
