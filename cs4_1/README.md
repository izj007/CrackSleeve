# 破解CS4.1

## 使用说明
将cobaltstrike.jar和CrackSleeve.java放一起
编译(javac -encoding UTF-8 -classpath cobaltstrike.jar CrackSleeve.java)
解密文件(java -classpath cobaltstrike.jar;./ CrackSleeve decode)
自定义16位字符串加密文件(java -classpath cobaltstrike.jar;./ CrackSleeve encode CustomizeString)
将解密后的sleeve文件夹替换jar包中的文件夹