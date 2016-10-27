#MIT-SCHEME的安装

###1.下载
从[GUN网站](http://www.gnu.org/software/mit-scheme)选择相应的系统版本下载。

###2.安装
####Mac系统
1)点击下载好的.dmg文件，然后将应用程序拖动到程序目录

2)创建从应用程序目录到用户类库目录的硬链接
    
    sudo ln -s /Application/MIT\:GNU\ Scheme.app/Contents/Resource /usr/local/lib/mit-scheme-[platform-specification]

3)然后将mit-scheme文件创建硬链接到用户的bin目录

     sudo ln -s /usr/local/lib/mit-scheme-[paltform-specification] /usr/local/bin/scheme

4)在控制台敲入命令`scheme`,就可以看到已经安装成功

**注意** 如果你的下载的是32位版本上面的platform-specification应该是`i386`,64位为`x86-64`


##参考链接

[stackoverflow](http://stackoverflow.com/questions/12322434/how-to-install-mit-scheme-on-mac)
