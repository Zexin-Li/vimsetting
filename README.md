# my vim setting
my vim config

# 使用方式
yum install ctags
把 .vimrc copy 到 ~/ 路径下
把 .vim copy 到 ~/ 路径下

ctags
生成c++ tags: ctags -R --c++-kinds=+p --fields=+iaS --extra=+q

为了方便使用在profile里面
alias vctags="ctags -R --c++-kinds=+p --fields=+iaS --extra=+q"

