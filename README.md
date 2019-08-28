# # MySDK
MySDK is a project that implement react-native code to java library.
In MySDKActivity will use ReactRootView, its for root view which react native code live.

we should use same appKey which we define in index.js (**"MyReactNativeApp"**).
```
mReactRootView.startReactApplication(mReactInstanceManager, "MyReactNativeApp", null);

AppRegistry.registerComponent('MyReactNativeApp', () => HelloWorld);
```

I use same version react native which declare in package.json but i don't use official react native depedency because it just support to 0.20.1.
So i use another depedency from [mvnrepository].

[mvnrepository]: <https://mvnrepository.com/artifact/com.walmartlabs.ern/react-native>
