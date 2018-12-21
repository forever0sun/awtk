## time\_clock\_t
### 概述
![image](images/time_clock_t_0.png)

 时钟控件。
### 函数
<p id="time_clock_t_methods">

| 函数名称 | 说明 | 
| -------- | ------------ | 
| <a href="#time_clock_t_time_clock_cast">time\_clock\_cast</a> |  转换为time_clock对象(供脚本语言使用)。
| <a href="#time_clock_t_time_clock_create">time\_clock\_create</a> |  创建time_clock对象
| <a href="#time_clock_t_time_clock_set_bg_image">time\_clock\_set\_bg\_image</a> |  设置背景图片。
| <a href="#time_clock_t_time_clock_set_hour">time\_clock\_set\_hour</a> |  设置小时的值。
| <a href="#time_clock_t_time_clock_set_hour_image">time\_clock\_set\_hour\_image</a> |  设置小时的图片。
| <a href="#time_clock_t_time_clock_set_image">time\_clock\_set\_image</a> |  设置图片。
| <a href="#time_clock_t_time_clock_set_minute">time\_clock\_set\_minute</a> |  设置分钟的值。
| <a href="#time_clock_t_time_clock_set_minute_image">time\_clock\_set\_minute\_image</a> |  设置分钟的图片。
| <a href="#time_clock_t_time_clock_set_second">time\_clock\_set\_second</a> |  设置秒的值。
| <a href="#time_clock_t_time_clock_set_second_image">time\_clock\_set\_second\_image</a> |  设置秒的图片。
### 属性
<p id="time_clock_t_properties">

| 名属性称 | 类型 | 说明 | 
| -------- | ----- | ------------ | 
| <a href="#time_clock_t_bg_image">bg\_image</a> | char* |  背景图片。
| <a href="#time_clock_t_hour">hour</a> | int32_t |  小时。
| <a href="#time_clock_t_hour_image">hour\_image</a> | char* |  时针图片。
| <a href="#time_clock_t_image">image</a> | char* |  中心图片。
| <a href="#time_clock_t_minute">minute</a> | int32_t |  分钟。
| <a href="#time_clock_t_minute_image">minute\_image</a> | char* |  分针图片。
| <a href="#time_clock_t_second">second</a> | int32_t |  秒。
| <a href="#time_clock_t_second_image">second\_image</a> | char* |  秒针图片。
### 事件
<p id="time_clock_t_events">

| 事件名称 | 类型  | 说明 | 
| -------- | ----- | ------- | 
#### time\_clock\_cast 函数
* 函数原型：

```
widget_t* time_clock_cast (widget_t* widget);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | widget\_t* | time\_clock对象。 |
| widget | widget\_t* | time\_clock对象。 |
* 函数功能：

> <p id="time_clock_t_time_clock_cast"> 转换为time_clock对象(供脚本语言使用)。



#### time\_clock\_create 函数
* 函数原型：

```
widget_t* time_clock_create (widget_t* parent, xy_t x, xy_t y, wh_t w, wh_t h);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | widget\_t* | 对象。 |
| parent | widget\_t* | 父控件 |
| x | xy\_t | x坐标 |
| y | xy\_t | y坐标 |
| w | wh\_t | 宽度 |
| h | wh\_t | 高度 |
* 函数功能：

> <p id="time_clock_t_time_clock_create"> 创建time_clock对象



#### time\_clock\_set\_bg\_image 函数
* 函数原型：

```
ret_t time_clock_set_bg_image (widget_t* widget, const char* bg_image);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| bg\_image | const char* | 背景图片。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_bg_image"> 设置背景图片。



#### time\_clock\_set\_hour 函数
* 函数原型：

```
ret_t time_clock_set_hour (widget_t* widget, int32_t hour);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| hour | int32\_t | 小时的值。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_hour"> 设置小时的值。



#### time\_clock\_set\_hour\_image 函数
* 函数原型：

```
ret_t time_clock_set_hour_image (widget_t* widget, const char* hour);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| hour | const char* | 小时的图片。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_hour_image"> 设置小时的图片。



#### time\_clock\_set\_image 函数
* 函数原型：

```
ret_t time_clock_set_image (widget_t* widget, const char* image);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| image | const char* | 图片。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_image"> 设置图片。



#### time\_clock\_set\_minute 函数
* 函数原型：

```
ret_t time_clock_set_minute (widget_t* widget, int32_t minute);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| minute | int32\_t | 分钟的值。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_minute"> 设置分钟的值。



#### time\_clock\_set\_minute\_image 函数
* 函数原型：

```
ret_t time_clock_set_minute_image (widget_t* widget, const char* minute_image);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| minute\_image | const char* | 分钟的图片。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_minute_image"> 设置分钟的图片。



#### time\_clock\_set\_second 函数
* 函数原型：

```
ret_t time_clock_set_second (widget_t* widget, int32_t second);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| second | int32\_t | 秒的值。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_second"> 设置秒的值。



#### time\_clock\_set\_second\_image 函数
* 函数原型：

```
ret_t time_clock_set_second_image (widget_t* widget, const char* second_image);
```

* 参数说明：

-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | 控件对象。 |
| second\_image | const char* | 秒的图片。 |
* 函数功能：

> <p id="time_clock_t_time_clock_set_second_image"> 设置秒的图片。



#### bg\_image 属性
-----------------------
> <p id="time_clock_t_bg_image"> 背景图片。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### hour 属性
-----------------------
> <p id="time_clock_t_hour"> 小时。


* 类型：int32\_t

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### hour\_image 属性
-----------------------
> <p id="time_clock_t_hour_image"> 时针图片。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### image 属性
-----------------------
> <p id="time_clock_t_image"> 中心图片。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### minute 属性
-----------------------
> <p id="time_clock_t_minute"> 分钟。


* 类型：int32\_t

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### minute\_image 属性
-----------------------
> <p id="time_clock_t_minute_image"> 分针图片。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### second 属性
-----------------------
> <p id="time_clock_t_second"> 秒。


* 类型：int32\_t

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### second\_image 属性
-----------------------
> <p id="time_clock_t_second_image"> 秒针图片。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |