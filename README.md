robotframework中RIDE的下载及安装
1.首先说一下我当前的环境配置

win10系统64位
python3.6.5，已配置环境变量
2.安装RIDE前需要安装的依赖包（使用pip就可以直接安装）

首先必须有robotframework这就不用多说了
其次安装Pygments
再次安装wxPython（wxpython是用于支持python图形化界面的，安装它主要是用来运行RIDE的）
3.现在来说最重要的RIDE的安装

首先由于使用的python版本是3.6.5，官网上支持的一般都是python2.7，所以3.6需要到这个地址下载RIDE的gz包，网址：https://github.com/HelioGuilherme66/RIDE/archive/python3.zip
下载完成后解压到本地，cmd进入到解压出来的路径，执行命令：python setup.py install
此时RIDE安装完成，此时提示：Creating Desktop Shortcut to RIDE...

4.这时我们来创建RIDE的快捷方式以及打开RIDE

桌面鼠标右键->新建->快捷方式->
输入：D:\python\python.exe -c "from robotide import main;main()"，->进行下一步命名为：RIDE
我们来更换一下图标：点击快捷方式->右键属性->更换图标路径选择D:\python\Lib\site-packages\robotide\widgets\robot.ico
