###消除移动端默认input框
```
*focus {outline: none;}
```
***
###安卓手机软键盘压缩画面 & 遮挡输入框的问题
```
$('body').height($('body')[0].clientHeight)
```
***
###清除安卓手机输入框默认样式
```
input {
    border: 0;
    list-style: none;
    -webkit-appearance: none;
}
```
***
###写提示框怕出现清不掉的情况，应该用append的方法，添加前首先清除一下。
***
