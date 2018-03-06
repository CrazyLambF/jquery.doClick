# jquery.doClick
jquery.doClick：为元素同时绑定单击事件和双击事件。

# 使用方法:
```javascript
    $(dom).doClick({
        /**
         * 点击事件回调
         * @param self：自身dom对象 (注意: 这里无法用this获取自身dom对象)
         */
        onClick: function (self) {}
        /**
         * 双击回调事件
         * @param self：自身dom对象 (注意: 这里无法用this获取自身dom对象)
         */
        dbClick: function (self) {}
    })
```
