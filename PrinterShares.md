nc -vz mysterious-sea.picoctf.net 59078  
smbclient -L //mysterious-sea.picoctf.net -p 59078 -N  
-> -N 匿名  
-> 匿名列出列表內東西  
help  
-> 列出command  
l  
-> 列出內部檔案  
get flag.txt  
exit  
cat flag.txt
