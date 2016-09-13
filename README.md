# cropbox

## github地址：https://github.com/tuxingsheng/cropbox.git
## 在线访问地址：https://tuxingsheng.github.io/cropbox/


### 配置参数说明
```javascript
    this.defaults = {
        // crop选择器
        el: '#crop',
        // 触发器
        cp: '#cropImg',
        // crop背景色
        cropBgColor: 'rgba(0, 0, 0, .4)',
        // crop img地址
        imgSrc: '',
        // 不用修改
        imageBox: '.crop-wrap-content',
        thumbBox: '.crop-wrap-thum',
        spinner: '.crop-wrap-spinner',
        // 返回裁剪之后图片的base64和blob二进制
        callback: function (dataURL, dataBlob) {
            console.log(dataURL, dataBlob);
        }
    };
```
