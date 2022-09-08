# 9cc
<p>
  参考資料:<a href="https://www.sigbus.info/compilerbook">低レイヤを知りたい人のためのCコンパイラ作成入門</a>
</p>
<p>$ cc -o 9cc 9cc.c</p>
<p>$ ./9cc 123 > tmp.s</p>
<p>$ cc -o tmp tmp.s</p>
<p>$ ./tmp</p>
<p>$ echo $?<br>
<a>123</a>
</p>
<p>$ ./test.sh<br>
<a>0 => 0</a><br>
<a>42 => 42</a><br>
<a>OK</a>
</p>
