MY RC
===========

this is my rc files 

bin
---------
my tools 


vimrc
----------
my .vimrc 

1. 把最后一行

```
source $HOME/.vim/ftplugin/dyz.vim
```

这个删除
2. 在家目录下建立

```
mkdir -p .vim/bundle
```

3. 在.vim/bundle 目录下

```
cd ~/.vim/bundle
git clone git@github.com:dolfly/vundle.git 
```
4. 打开 vim

命令行模式下执行
```
:BundleInstall 
```


