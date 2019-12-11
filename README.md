# react-native-aloha-test

## Getting started

`$ npm install react-native-aloha-test --save`

### Mostly automatic installation

`$ react-native link react-native-aloha-test`

## Usage
```javascript
import AlohaTest from 'react-native-aloha-test';

AlohaTest.sampleMethod('Testing', 123, (message) => {
      this.setState({
        status: 'native callback received',
        message
      });
    });
```
