Wanda
======

The fan favorite Wanda The Fish in your Ubuntu Unity Launcher.


In order to add Wanda to your launcher, create a file called wanda.desktop in your home directory. You can download
a photo of wanda from 
<a href ="http://www.google.co.in/imgres?um=1&hl=en&sa=N&tbo=d&biw=1366&bih=682&tbm=isch&tbnid=PY10QByhuOfsiM:&imgrefurl=http://www.apphist.com/android/app/7658664737853037650/wanda-the-fish&docid=xG_BnSOehmWhCM&imgurl=https://androidmarket.googleusercontent.com/android/market/com.fernandobohrer.wandathefish/hi-256-8-338272d2b8888d48f6927d2d081829a231202ce2&w=256&h=256&ei=RqcGUZG3KoTNrQe6qYHgAg&zoom=1&iact=rc&dur=462&sig=107115140550133500131&page=2&tbnh=144&tbnw=169&start=24&ndsp=35&ved=1t:429,r:25,s:0,i:163&tx=142&ty=81">
here </a>. 
Save it as wanda.jpg in your home directory.
The contents of wanda.desktop should be:
```
[Desktop Entry]
Version=1.0
Type=Application
Name= Wanda Says...
Comment= Easy access to fortunes
TryExec= <path to wanda.py>
Exec= python <path to wanda.py>
Icon= <path to wanda.jpg>
```
Now chmod +x to wanda.desktop and exit. Double click to execute. Drag and drop it onto your launcher.
