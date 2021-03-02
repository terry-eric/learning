# github setting

```https://git-scm.com/downloads  #git下載```

```C:\Program Files\Git\git-bash #點擊```

```ssh-keygen -t rsa -b 4096 -C "your_email@example.com" #git-bash中打上gmail```

C:\Users\eric2\id_rsa.pub,把內容複製加進這裡![image](https://user-images.githubusercontent.com/67619529/109429418-987bb980-7a36-11eb-8ec9-32c803c521da.png)

```
cmd 

git 

git --version #查看版本

git config --global user.name "yourname" #輸入user name

git config --global user.name #查看名稱

git config --global user.email "yourmail" #輸入mail

git config --global user.email #查看mail
```
# github upload download
>可再任意處創建資料夾任意名稱，這裡用在C:\

```在C:\創建git_set_test的資料夾```
```
cd/

cd git_set_test

git clone https://github.com/terry-eric/leaning.git #此處連結為github裡，右上角下載的連結

cd leaning 

git status #查看有無增加或改變檔案，並顯示檔案名稱

touch 123 #windows使用touch需先設定

git add 123

git commit -m 123 #後面的123為commit的提示字

git push #上傳檔案
```

參考網址:

```https://www.youtube.com/watch?v=py3n6gF5Y00&ab_channel=%E6%B2%88%E5%BC%98%E5%93%B2```>github setting

```https://docs.github.com/en/github/getting-started-with-github/set-up-git#setting-up-git```>setup git

```https://docs.github.com/cn/github/writing-on-github/basic-writing-and-formatting-syntax```>github基本撰寫格式和語法
