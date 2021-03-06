# MutlColorLoadingView
![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![java](https://img.shields.io/badge/language-java-Borange.svg)  ![java](https://img.shields.io/badge/version-1.0.0-orange.svg)

[Englist](https://github.com/zhangchaojiong/MutlColorLoadingView/blob/master/README.md) | [中文版本](https://github.com/zhangchaojiong/MutlColorLoadingView/blob/master/README_zh.md)
>A beautiful loading view

## Design sketch

![demo.gif](https://github.com/zhangchaojiong/MutlColorLoadingView/blob/master/image/demo.gif)

## Usage：
* Setting up the dependency

```
implementation 'com.mutlcolorloadingview:mutlcolorloadingview:1.0.0'
```
* Simple use cases will look something like this:

```
<com.mutlcolorloadingview.MutlColorLoadingView
        android:id="@+id/mclv"
        android:layout_width="120dp"
        android:layout_height="105dp"
        android:padding="28dp"
        android:background="@drawable/bg_loading"
        app:mclv_duration="2000"
        app:mclv_first_color="@color/color_FFFFFFFF"
        app:mclv_second_color="@color/color_FF4D6BFF"
        app:mclv_three_color="@color/color_FFFF8400"
        app:mclv_stroke_width="4dp"
        />
```



## Styleable 

```
    <declare-styleable name="MutlColorLoadingView">
        <!--The color of the first progress-->
        <attr name="mclv_first_color" format="color" />
        <!--The color of the second progress-->
        <attr name="mclv_second_color" format="color" />
        <!--The color of the three progress-->
        <attr name="mclv_three_color" format="color" />
        <!--A round of time-->
        <attr name="mclv_duration" format="integer" />
        <!--Angle of progress-->
        <attr name="mclv_start_angle" format="integer" />
        <!--The thickness of the progress bar-->
        <attr name="mclv_stroke_width" format="integer|dimension"/>
        <!--The ratio of the first color progress to the total progress-->
        <attr name="mclv_rate_first_round" format="float" />
    </declare-styleable>
```


## License

```
Copyright (C) 2020 chaojiong.zhang

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```