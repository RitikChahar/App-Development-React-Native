# Creating First React Native APP and Running It On Android Device
## 1. To create a project using React Native use the following command
```js
npx react-native init ProjectName
```
## 2. Connect your smartphone to your system with ``` USB Debugging Enabled ```
- ### To check if your device is connected use the following command
    ```js
    adb devices
    ```
## 3. Create ``` local.properties ``` in the ``` android ``` directory (if not present by default) and add the following path in it
```
sdk.dir = C\:\\Users\\YOURUSERNAME\\AppData\\Local\\Android\\Sdk
```
## 4. Running your React Native application
```
npx react-native run-android
```
## 5. To Reinstall ``` node_modules ```
```
rm -rf node_modules && npm install
```