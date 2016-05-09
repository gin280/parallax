```js
<script>

// 下面的都是默认属性
$('.pages').parallax({
    direction: 'vertical',  // horizontal (水平翻页)
    swipeAnim: 'default',   // cover (切换效果)
    drag:      true,        // 是否允许拖拽 (若 false 则只有在 touchend 之后才会翻页)
    loading:   false,       // 有无加载页
    indicator: false,       // 有无指示点
    arrow:     false,       // 有无指示箭头
    /*
     * 翻页后立即执行
     * {int}        index: 第几页
     * {DOMElement} element: 当前页节点
     * {String}     directation: forward(前翻)、backward(后翻)、stay(保持原页)
     */
    onchange: function(index, element, direction) {
        // code here...
    },
    /*
     * 横竖屏检测
     * {String}     orientation: landscape / protrait
     */
    orientationchange: function(orientation) {
        
    }

});

</script>
```