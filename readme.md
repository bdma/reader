###性能优化     
    1，尽量减少repaint，reflow
    2，缓存了大量可缓存的数据，localStorage
    3，大量transform动画代替DOM操作
    4，未对非static 定位元素使用transform
    5，适当使用硬件加速 transform:translate(0,0,0);
