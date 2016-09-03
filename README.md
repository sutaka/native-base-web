NativeBase for Web
------------------
[![npm version](https://badge.fury.io/js/native-base-web.svg)](https://badge.fury.io/js/native-base-web)

NativeBase-web is a project to bring [NativeBase](http://nativebase.io/) components to the Web, with the help of [react-native-web-extended](https://github.com/Chion82/react-native-web-extended).

Get Started
-----------
To install:

```
npm install --save native-base-web
```

NativeBase-web is depended on react-native-web-extended, an extended version of [react-native-web](https://github.com/necolas/react-native-web). Install it if you have not yet configured your app structure:

```
npm install --save react-native-web-extended
```

Setup resolve alias in your webpack configuration:

```JavaScript
resolve: {
	alias: {
		'react-native': 'react-native-web-extended',
		'native-base' : 'native-base-web'
	}
}
```

Components
----------
Most components from [NativeBase](http://nativebase.io/) are included with same features and parameters. You can read the [NativeBase documentation](http://nativebase.io/docs/v0.5.7/) to use them in NativeBase-web while we are working on our gitbook.

Working components:  
* Anatomy  
* Badge  
* Button  
* Card  
* Check Box  
* Form  
* Icon (Available icon familys: Ionicons, FontAwesome, MaterialIcons)  
* InputGroup  
* Layout  
* List  
* Radio Button  
* Search Bar  
* Spinner  
* Tabs  
* Thumbnail  

Migrate from NativeBase projects
--------------------------------
It is possible to migrate your [NativeBase](http://nativebase.io/) project to a NativeBase-web without changing lots of your code.

TODO
