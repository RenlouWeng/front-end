# 常用css效果

## 毛玻璃效果1
``` css
.blur{
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter：blur(10px);   
}

```
注意浏览器兼容性，可以采用support事先进行判断是否支持

## 毛玻璃效果2
``` css
.blur{
    filter: blur(10px);
    -webkit-backdrop-filter：blur(10px);   
}

```