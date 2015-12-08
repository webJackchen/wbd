# wbd
2015-12-6号接的外包单子，实现一个表单控件</br>

##调用方法

var a1 = new $.Table();</br>
        a1.init({</br>
            dataSource:['1998','1999','2000'],   //数据源</br>
            leftParentheses:['(','{','(('],    //左括号       此值需和右括号一一对应</br>
            rightParentheses:[')','}','))'],    //右括号      此值需和左括号一一对应</br>
            logic:['and','or'],   //逻辑符号</br>
            compareSymble:['=','>=','>','<','<='],    //比较符</br>
            ziduan:['1998','1999','2000'],</br>
            oContainer : $('.my-module')</br>
        });</br>
