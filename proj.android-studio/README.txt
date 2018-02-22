####################################### ABOUT #######################################
This 'proj.android-studio' project was taken as base from original cocos2d-3.16 'cpp-template-default' and contains fixes in some projects files (list of fixed files giving below) and allow you build and run it without troubles.

fixed files list:
proj.android-studio\app\jni\Andorid.mk
proj.android-studio\app\build.gradle
proj.android-studio\build.gradle
proj.android-studio\gradle\wrapper\gradle-wrapper.jar
proj.android-studio\gradle\wrapper\gradle-wrapper.properties

####################################### prerequisites software for success building and running #######################################
* Android Studio 3.1
* Cocos2d-x-3.16
* Android NDK r12b (x64)

####################################### GUIDE #######################################
During first opening 'proj.android-studio' in Android Studio 3.1 you should manually set path to Android NDK. You can do that by opening 'File/Project Structures' and setting path to 'Android NDK location' filled. For testing purpose i used android-ndk-r12b (64 bit OS version).