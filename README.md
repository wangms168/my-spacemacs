# spacemacs大幅简化说明
1、剔除evil，保留layers可扩展性框架（这个框架好啊！！）;

     注释掉spacemacs-bootstrap/package.el中的evil包,
   
     注释掉spacemacs-base/package.el中与evil有关的包
   
2、仅保留spacemacs-bootstrap与spacemacs-base这两个基本laters;

3、以后按约定 ( http://spacemacs.org/doc/CONVENTIONS.html ) 自己慢慢增加需要的layer。



windows系统建立连接实例(cmd在d:\emacs目录下)：mklink .spacemacs .\\.emacs.d\\.spacemacs

.\\.emacs.d\\.spacemacs为源文件，.spacemacs为目标文件。

