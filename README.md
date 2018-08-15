
# react-native-paypal

## Getting started

`$ npm install react-native-paypal --save`

### Mostly automatic installation

`$ react-native link react-native-paypal`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-paypal` and add `RNPaypal.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPaypal.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNPaypalPackage;` to the imports at the top of the file
  - Add `new RNPaypalPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-paypal'
  	project(':react-native-paypal').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-paypal/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-paypal')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNPaypal.sln` in `node_modules/react-native-paypal/windows/RNPaypal.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Paypal.RNPaypal;` to the usings at the top of the file
  - Add `new RNPaypalPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNPaypal from 'react-native-paypal';

// TODO: What to do with the module?
RNPaypal;
```
  