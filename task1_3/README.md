    利用浮动原理，左右定宽度分别进行左浮动和右浮动，此时主内容列（中间列没有定度）主会自动插入到左右两列的中间，注意的一点是
，中间列一定要放在左右两列的后面。
    同时设置最外层的DIV为浮动，并设置padding值，才能保证右边的图片栏在增加图片时，最外层的DIV高度可以随之变长。
    因为左边比右边多80个像素，所以中间的div在设置margin属性时，右边比左边多80个像素
    
    