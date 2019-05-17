#彻底删除IDEA

卸载MAC中的IDEA Intellij 首先在应用里面右键移动到垃圾桶然后使用命令行：
cd Users/xxx/Library/ 上面的xxx对应你的用户名，
然后输入
```
rm -rf Logs/IntelliJIdeaxxx/ 
rm -rf Preferences/IntelliJIdeaxxx/
rm -rf Application\ Support/IntelliJIdeaxxx/ 
rm -rf  Caches/IntelliJIdeaxxx
```
上面的对应xxx对应不同的版本号，注意开头是 IntelliJIdea就行
