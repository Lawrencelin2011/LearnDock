# LearnDock
學習怎麼使用 Docker

# 新專案開始建立的方式 (cmd 系統管理員)：

## [1] 建立專案 目錄，並且 到 專案目錄去:

```
方法 1. 先去 Git 上面 new 一個 repository.
再到 C:\Gitps 這裡 colone 下來.
git clone "https://github.com/Lawrencelin2011/LearnDock.git"

方法 2. 直接建立新目錄.
C:\Gitps>md mysite
C:\Gitps>cd mysite
```

## [2] 檢查是不是有 您要的 Python 版本：
```
py -0p
```
C:\GitProjects\mysite>py -0p
 -V:3.11 *        C:\Users\mojtpm\AppData\Local\Programs\Python\Python311\python.exe
 -V:3.9           C:\ProgramData\Anaconda3\python.exe
 -V:3.8           C:\Users\mojtpm\AppData\Local\Programs\Python\Python38\python.exe
 -V:3.7           C:\Users\mojtpm\AppData\Local\Programs\Python\Python37\python.exe
 -V:ContinuumAnalytics/Anaconda39-64 C:\ProgramData\Anaconda3\python.exe

 (如果沒有您要的版本，則要去下載，並且 Set-Up)
 (這裡要使用 V3.11 -- 目前Render 只吃這個版本，另外，Django 5.0 也吃這個版本)

## [3] 建立 venv, 並且 Activate 這個 venv:
```
py -3.11 -m venv venv
.\venv\Scripts\activate
```
(venv) C:\GitProjects\mysite>

（使用 V3.11)