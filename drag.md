<!-- 

    利用prototype扩展
    移动的结构position要先预设fixed、relative、absolute;
    拖拽的手柄父级或者子级存在a标签时，1秒后自动覆盖hover层;

    数据
    move_pop：移动的结构
    handle：拖拽的手柄
    backgroundColor：填充背景色（如果有设置）

    引入js后实例化&创建空数组
    var _drag = new drag(),
        element_array = [];
    element_array[0] = {
        move_pop: document.querySelector("#xxxxxx"),
        handle: document.querySelector(".xxxxxx"),
        backgroundColor: "#ffffff"
    }
    element_array[1] = {
        move_pop: document.querySelector(".xxxxxx"),
        handle: document.querySelector("#xxxxxx"),
        backgroundColor: "#ffffff"
    }
    ......
    
    注册
    _drag.on(element_array); 

-->