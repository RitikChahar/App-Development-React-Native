# Setting Up The Developlment Environment For ``` React Native ```
## 1. Download and Install ``` Node.js ``` and  ``` JDK ```
- ### Install the latest LTS version of ``` Node.js ```
    ```
    https://nodejs.org/en/download/
    ```
- ### Install ``` JDK 11 ```
    ```
    https://learn.microsoft.com/en-us/java/openjdk/download
    ```
## 2. Download and Install ``` Android Studio ```
```
https://developer.android.com/studio
```
### Make sure to check the following while installing ``` Android Studio ```
- ### ``` Android SDK ```
- ### ``` Android SDK Platform ```
- ### ``` Android Virtual Device ```
- ### ``` Performance (Intel ® HAXM) ```
## 3. Download and Install the ``` Android SDK ```
1. ### Open Android Studio, click on ``` More Actions ```  button and select ``` SDK Manager ``` 
2. ### Select the ``` SDK Platforms ``` tab from within the ``` SDK Manager ```, then check the box next to ``` Show Package Details ``` in the bottom right corner
3. ### Look for and expand the ``` Android 12 (S) ``` entry, then make sure the following items are checked:
   * #### ``` Android SDK Platform 31 ```
   * #### ``` Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image ```
4. ### Next, select the ``` SDK Tools ``` tab and check the box next to ``` Show Package Details ``` here as well
5. ### Look for and expand the ``` Android SDK Build-Tools ``` entry, then make sure that ```31.0.0``` is selected
6. ### Click ``` Apply ``` to download and install the ``` Android SDK ``` and related ``` build tools ```
## 4. Configure the ``` ANDROID_HOME ``` Environment Variable
1. ### Open ``` Edit the System Environment Variables ```
2. ### Select ``` Environment Variables ```
3. ### Click on ``` New ``` in  ``` System Variables ```
4. ### Set variables names as ``` ANDROID_HOME ```
5. ### Set variable value as the path of your SDK, by default the SDK is installed at this location :
    ```
    %LOCALAPPDATA%\Android\Sdk
    ```
## 5. Add ``` platform-tools ``` to Path
1. ### Open ``` Edit the System Environment Variables ```
2. ### Select ``` Environment Variables ```
3. ### Click on ``` PATH ``` in ``` System Variables ```
4. ### Click ``` Edit ```.
5. ### Click ``` New ``` and add the path of ``` platform-tools ``` to the list, default location for ``` platform-tools ``` is:
    ```
    %LOCALAPPDATA%\Android\Sdk\platform-tools
    ```