###git仓库测试
###查找jar包中的字符串命令
find . -iname '*.jar' -printf "unzip -c %p | grep -q '192.168.100.167' && echo %p\n" | sh