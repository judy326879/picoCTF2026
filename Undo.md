nc foggy-cliff.picoctf.net 58173  
base64 -d  
-> base64解碼  
rev  
->  前後順序交換  
tr '-' '_'  
-> - 改成 _  
tr '()' '{}'  
tr 'n-za-mN-ZA-M' 'a-zA-Z'  
->凱薩解碼(n-za-m -> a-z)  
