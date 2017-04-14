# bootstrapTablefixed
bootstrapTable表格固定行列，拖动列宽，换列的功能

#使用方法
resizeDisable("testTable", 1, 0);//表ID、固定行、固定列
引用
bootstrap.min.css
bootstrap-table.min.css
jquery.min.js
bootstrap.min.js
bootstrap-table.min.js
bootstrap-table-zh-CN.min.js
colResizable-1.6.min.js//表格拖动插件，无列拖动不需引用
freezeTable.js 
fixedTableHead.js//各个版本不一样


#1、无列拖动
无列拖动实现了bootstrapTable的表的行和列固定
#2、有列拖动
有列拖动实现了bootstrapTable的表的行和列固定、列宽拖动
#3、可换列
可换列实现了bootstrapTable的表的行和列固定、列宽拖动、换列

#问题
1.列拖动第一次无效
2.没有将三个插件封装到一起
