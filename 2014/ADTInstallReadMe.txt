Android/Eclipse Bundle Installation Instructions
The following instructions will allow students to run the Android SDK and pre-configured Eclipse IDE with Android plug-ins from a USB Thumb Drive. We believe this configuration is the easiest setup for students with the added benefit that it does not interfere with any installed Eclipse IDE used for classes, and does not require an internet connection with prolonged download of plug-ins for each computer. An additional benefit is that students can keep their projects on the USB Thumb Drive (with appropriate backup recommended!) and use nearly any computer for development, either at school or at home. The only requirement is that there is an updated, current version of the Java JDK installed on the computer that is used.

The instructions below also work if you wish to install the tools directly on a school or home computer instead of a USB Thumb Drive. Note that doing so GREATLY improves the performance of the development environment.

The installation assumes that Java JDK 6 or higher has already been installed. If the students are already using Eclipse on the machine then this is likely already true. If not, the JDK can be downloaded from:

http://www.oracle.com/technetwork/java/javase/downloads/index.html

Unfortunately due to Oracle licensing we cannot include the image on the DVD. Only the JDK image is needed so ignore any that include JEE or NetBeans.

The needed files are on the delivered DVD (with the exception of the Java JDK) or they can be downloaded from the following locations:

On the DVD:
adt-bundle-windows-x86_64-20140702p.zip 
and
adt-bundle-windows-x86-20140702p.zip if the JDK you installed was the 64bit install use this one.

Internet:
Go to http://developer.android.com/sdk/index.html#download and click the big blue Download the SDK ADT Bundle for Windows. However, if you do this other options are required to be installed via download as well. In total over a GB of data.  If electing this route instead of a Harris provided preconfigured zip file then after installing the sdk open SDK Manager.exe on Windows or open Eclipse and in the Window menu select Android SDK Manager.  Then in Windows or Mac ensure the following have check boxes next to them and if not check the box and install.
Tools
 Android SDK Tools
 Android SDK Platform-tools
 Android SDK Build-tools
Android 4.4W (API20)
 SDK Platform
Android 4.4.2 (API19)
 SDK Platform
 ARM EABI v7a System Image
 Intel x86 Atom System Image
 Google APIs (x86 System Image)
 Google APIs (ARM System Image)
Extras
 Android Support Library
 Google USB Driver (NOTE this is only installed on Windows not Mac)
On Mac there is a bug and you can't select or deselect individual packages.
So first at the bottom Deselect All, Then select the top level package.  This will cause all of the sub levels to be selected. You can then deselect packages that are not needed.

To use on the computer unzip the appropriate 32 or 64 bit zip file to the C: drive. Note if you place this deeper than C you will likely get a path too long error. Alternatively the students can unzip it onto their thumb drives (They will need to be large thumb drives with at least 5GB of free space).

Alternatively, if performing the install on multiple USB drives or multiple machines, you may want to unzip the package first and then copy the extracted folder to each USB drive or machines to save time.

Students can then run 
adt-bundle-windows-x86-20140702p\eclipse\eclipse.exe or
adt-bundle-windows-x86_64-20140702p\eclipse\eclipse.exe
to start Eclipse with the Android plug-ins.

Note that whatever workspace the studets are using for their existing projects they MUST not reuse that workspace for this Eclipse.  They will need a new workspace for their Android development or they may get odd behaivor in the IDE.

