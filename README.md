# wbd
2015-12-6号接的外包单子，实现一个表单控件/n

##调用方法

var a1 = new $.Table();/n
        a1.init({/n
            dataSource:['1998','1999','2000'],   //数据源/n
            leftParentheses:['(','{','(('],    //左括号       此值需和右括号一一对应/n
            rightParentheses:[')','}','))'],    //右括号      此值需和左括号一一对应/n
            logic:['and','or'],   //逻辑符号/n
            compareSymble:['=','>=','>','<','<='],    //比较符/n
            ziduan:['1998','1999','2000'],/n
            oContainer : $('.my-module')/n
        });/n
