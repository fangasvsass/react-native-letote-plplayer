
# react-native-letote-plplayer

## Getting started

`$ npm install react-native-letote-plplayer --save`

### Mostly automatic installation

`$ react-native link react-native-letote-plplayer`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-letote-plplayer` and add `RNPlplayer.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPlplayer.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.letote.RNPlplayerPackage;` to the imports at the top of the file
  - Add `new RNPlplayerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-letote-plplayer'
  	project(':react-native-letote-plplayer').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-letote-plplayer/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-letote-plplayer')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNPlplayer.sln` in `node_modules/react-native-letote-plplayer/windows/RNPlplayer.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Plplayer.RNPlplayer;` to the usings at the top of the file
  - Add `new RNPlplayerPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNPlplayer from 'react-native-letote-plplayer';

// TODO: What to do with the module?
RNPlplayer;
```
  