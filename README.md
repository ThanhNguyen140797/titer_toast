# react-native-titer-toast

## Getting started

`$ npm install react-native-titer-toast --save`

### Mostly automatic installation

`$ react-native link react-native-titer-toast`

## Usage
```javascript
import TiterToast from 'react-native-titer-toast';

// TODO: What to do with the module?
<TouchableNativeFeedback
  onPress={()=>{
    TiterToast.show("Your Test with duration: 1000", 1000)
  }}
  >
  <Text>Click here</Text>
</TouchableNativeFeedback>
```
