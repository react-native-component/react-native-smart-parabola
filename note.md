* 要注意android上view根据onLayout得到layout.x, layout.y计算出的值,
与ios上有些许差异, 例如, android上根据原点定义一个view绝对对位, left:10, top: 10, 得到的x = 9.9, y = 9.9,
ios上没有此问题, 总能得到x = 10, y = 10

