# wbd
2015-12-6号接的外包单子，实现一个表单控件</br>

##调用方法

var a1 = new $.Table();</br></br>
a1.init({</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dataSource:['1998','1999','2000'],   //数据源</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;leftParentheses:['(','{','(('],    //左括号       此值需和右括号一一对应</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rightParentheses:[')','}','))'],    //右括号      此值需和左括号一一对应</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;logic:['and','or'],   //逻辑符号</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;compareSymble:['=','>=','>','<','<='],    //比较符</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ziduan:['1998','1999','2000'],</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;oContainer : $('.my-module')</br>
&nbsp;&nbsp;&nbsp;&nbsp;});</br>
