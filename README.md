# react-native-in-one
react-native best lib collections

### awesome 

[awesome-react-native](https://github.com/jondot/awesome-react-native)

### 键盘遮挡

[KeyboardAwareScrollView](https://github.com/APSL/react-native-keyboard-aware-scroll-view)

### 轮播图

[react-native-snap-carousel ✨4265](https://github.com/archriss/react-native-snap-carousel)

### 设备信息大全

[react-native-device-info ✨3391](https://github.com/rebeccahughes/react-native-device-info)



# Tips

* ### 关于 react-native Picker 在 iOS 上不显示的问题

  Picker 的样式必须设定 width, height, 并且不能有 alignItems。

  ***注意在 Android 和 iOS 上 Picker 是不同的样式的控件， Android 上是弹出选择框，iOS 上直接是滑动选择***

  ***所以在 iOS平台不显示大概率是样式问题***
  
* ### 关于shadow 在iOS 平台不显示的问题

  需要设置 view 的 background
  
  Android 上需要使用 elevation 来设置阴影
  
* ### 关于StatusBar height 
  Android 上 获取状态栏高度   
  ```
  import { StatusBar } from 'react-native';
  const height = StatusBar.currentHeight;
  
  ```
  iOS 状态栏高度 20
  
