# sed-grep-awk-examples


## 替换文件中的字符串

替换文件 string.xml 中 `test1/test2/` 为空

```
sed -i s#test1\/test2\/##g string.xml
```