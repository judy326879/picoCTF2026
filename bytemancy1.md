wget https://challenge-files.picoctf.net/c_foggy_cliff/daa319a677eb71bb708aaa0943d7b89ed690c041c0ec5d554332f2e5432b4041/app.py  
cat app.py  
-> 看程式碼要求
-> vs code寫他要求的輸入
```python
print("\x65"*1751)
```
nc foggy-cliff.picoctf.net 65073  
