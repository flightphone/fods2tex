# fods2tex
<pre>
copy head.t  C:\Data\  
copy font_size.t  C:\Data\ 
dotnet fods2tex.dll C:\Data\MyFileWithTables.fods 

Parameter stop in file *.fods:
&lt;table:table table:name="Table1" table:style-name="Table2" stop="12"&gt;

stop = columns count + 1
</pre>