# automation-tests
This doc holds information on running automation for Serenity.

### Before you start
*Installing Java*
* you need a Java Development Kit (JDK). If you don't have a JDK installed, you can download JDK from the Java SE Downloads page. You
should download JDK - Java Development Kit.
* Updating the PATH Environment Variable (Optional)
* To set the PATH variable permanently, add the full path of the jdk1.8.0_101\bin directory to the PATH variable. Typically, this full path looks
something like C:\Program Files\Java\jdk1.8.0_101\bin. Set the PATH variable as follows on Microsoft Windows:
1. Click Start, then Control Panel, then System.
2.  Click Advanced, then Environment Variables.
3.  Add new variable «JAVA_HOME» with value is path to directory with JDK
* Add the location of the bin folder of the JDK installation for the PATH variable in System Variables. The following is a typical value
for the PATH variable: C:\WINDOWS\system32;C:\WINDOWS;C:\Program Files\Java\jdk1.8.0_101\bin

*Note:*
The PATH environment variable is a series of directories separated by semicolons (;) and is not case-sensitive. Microsoft
Windows looks for programs in the PATH directories in order, from left to right.
You should only have one bin directory for a JDK in the path at a time. Those following the first instance are ignored.

*Installing Gradle*
* You can download one of the Gradle distributions from the Gradle web site (you can select Binary only distribution version). The Gradle
distribution comes packaged as a ZIP.
* For running Gradle, firstly add the environment variable GRADLE_HOME. This should point to the unpacked files from the Gradle website. Next a
dd GRADLE_HOME/bin to your PATH environment variable. Usually, this is sufficient to run Gradle.
* To check if Gradle is properly installed just type gradle -v from the Command Line .. The output shows the Gradle version and also the local
environment configuration (Groovy, JVM version, OS, etc.). The displayed Gradle version should match the distribution you have downloaded.

*Installing Android Studio*
*Install and Configure Android SDK
*Add devices in AVD Manager

*Install NodeJs*

*Install Microsoft .net Framework*

*Installing Appium Desktop Client*

### Running tests
* Download automation tests from Git (e.g. https://github.com/AirCam/website/tree/dev/autotests)
* Open command-line interpreter (e.g. cmd)
* Proceed to auotests (e.g. cd Work\AirCam\website\autotests)
* Launch the tests (gradle clean test aggregate)
* Wait for build executing finish
* Veify Test results report (website\autotests\target\site\serenity\index.html)