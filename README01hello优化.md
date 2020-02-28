idea
    简介：
        目前IT界公认最好的java开发集成工具。
    下载安装
        百度上有
    hello实现
    idea安装后的文件目录介筛
        bin：执行文件包
        help：帮助手册
        jre：idea执行的时候，一些支持
        lib：idea用到的第三方jar包
        license：许可协议
        plugins：插件
        redist：扩展的东西，不用管
        额外c盘下idea目录，在用户目录下。idea文件夹下
            cofing：用户配置。如果换一台电脑，则导入这个配置文件。
            system：缓存文件，索引、日志、历史、临时文件等，如果idea运行奇葩问题，则删除这个文件夹来解决，大多数可以解决。
    idea优化配置，提高启动和运行速度
        在bin目录下idea64.exe.vmoptions和idea.exe.vmoptions 2个文件都修改
        -Xms1024m   //idea启动内存
        -Xmx1024m   //idea最大运行内存
        -XX:ReservedCodeCacheSize=512m  //idea缓存
    idea优化设置：都会存储带c盘用户下的config文件里
        toolbar工具栏显示：view-toolbar
        进入设置界面ctrl+alt+s
        主题设置：Appearance&Behavior -> Appearance -> Theme
        鼠标悬浮文档提示：Editor->General -> Show quick documentation on mouse over 
        显示方法分隔符：Editor->General ->Appearance-> Show method separators 勾选
            类里面的2个方法就会有横线区分。
        忽略大小写区分：Editor->General ->Code Completion -> Match case 勾选去掉
            比如输入string，不会提示String类
        自动导报（以前都是alt+enter人工导入）：Editor->general->Auto Import
                                                insert imports on paste 下拉选择all
                                                add unambiguous imports on the fly 勾选
                                                optimize imports on the fly 勾选                           
        取消单行显示文件tab：Editor->General ->Editor Tabs ->Show tabs in one row 勾选去掉
        设置编辑字体：Editor->Font
        配置类模板文档注释信息：Editor->File and Code Templates 然后Includes -> File Header
        设置文件编码:Editor -> File Encodings
        设置自动编译：eclipse是自动编译，idea默认不是。
            Build,Execution,Deployment -> Compiler 
                选勾：Build project automatically 和 compile independent modules in parallel
        水平/垂直显示代码
            右键文件Tab，选择 水平分隔，和垂直分隔。
    idea快捷方式改成eclipse
        File -> Settings -> Keymap 下拉选择eclipse
        建议使用idea的快捷键。
    idea固定代码缩写提示设置
        Editor -> Live Templates  下拉选Enter
    