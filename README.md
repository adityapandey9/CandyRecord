
# react-native-candy-record

## Getting started

`$ npm install react-native-candy-record --save`

### Mostly automatic installation

`$ react-native link react-native-candy-record`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-candy-record` and add `RNCandyRecord.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCandyRecord.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCandyRecordPackage;` to the imports at the top of the file
  - Add `new RNCandyRecordPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-candy-record'
  	project(':react-native-candy-record').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-candy-record/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-candy-record')
  	```


## Usage
```javascript
import RNCandyRecord from 'react-native-candy-record';

// TODO: What to do with the module?
RNCandyRecord;
```
  