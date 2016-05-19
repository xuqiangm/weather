参考　[link](https://github.com/fcambus/ansiweather)　用 shell 写的一个查看天气的工具

## 安装：

- 在 .bashrc 文件，添加 WEATHER_CONFIG 变量，值为工程中的 configuration 文件的路径
- 将该工程的路径添加到 $PATH 路径中

## 使用：

**用法**: weather [options]

选项有 :

- -l 指定地点
- -c 显示当前时间的天气
- -f 指定显示未来某一天的天气
- -F 显示未来5天（包括今天）的天气
- -u 显示用法