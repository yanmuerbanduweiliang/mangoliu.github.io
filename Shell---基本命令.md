#Shell---基本命令
**who** <br>
查看当前系统有谁在登陆。<br>

**wc** <br>
数目计算。-l按行，-w字数，-c字符数。<br>

**^D(ctrl-D)**<br>
文件结束符。<br>

**'#！ /bin/sh '**<br>
shell脚本通常第一行是这句。<br>

变量赋值时候，=号两端完全没有任何空格。取用时前面需要加上$。<br>

默认的标准输入输出是终端。<br>

**'<'**<br>
改变标准输入；<br>
**'>'**<br>
改变标准输出；<br>
**'>>'**<br>
附加到文件。<br>

**|**<br>
建立管道。将前面的程序的标准输出变成后面程序的标准输入<br>

**tr**<br>
转换字符。 tr [options] source-char-list replace-char-list<br>
-d 删除。<br>

**/dev/null**<br>
传输到这个文件的数据会被系统丢掉。<br>
**/dev/tty**<br>
重定向的到终端。<br>

shell脚本的各参数由整数来命名。当超过9时，需要用大括号框起来。<br>

**'#'**<br>
后面会被注释掉。<br>
