git clone ssh://git@foggy-cliff.picoctf.net:59249/git/challenge.git  
4f7061f2  
cd challenge  
-> 切換目錄到challenge  
ls  
-> 列出  
git config user.name "root"  
git config user.email "root@picoctf"  
-> 要求先登入  
echo "requestflag" > flag.txt  
git add flag.txt  
git commit -m "pushflag"  
-> -m = message  
-> 建檔  
git branch  
-> 檢查分支  
git push origin master  
-> 推送commit到分支  
