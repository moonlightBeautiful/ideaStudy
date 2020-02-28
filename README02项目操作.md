idea
    eclipse中，一个workspace可以建立很多项目，eclipse可以显示多个项目。
    idea中，一个项目就是一个工作空间，项目中可以建立多个模块
    idea中建立和删除模块
        建立：右键项目，new module。
        删除：先remove再delete    
    建立静态web项目
        Static web -> Static web
    建立普通动态web项目，不含jsp  
        java-web application 
        启动，需要配置tomcat
    建立复杂动态web项目，含jsp
        在一次性粘贴很多文件到项目的时候，会建立索引，可能会卡死。
        解决：把要复制到的文件夹标记为excluded。
        查询项目的依赖
            project settings下，modules菜单栏下表，dependencies的tab下可以看到
            tomcat的依赖
                +号选择library，选择tomcat，范围是provided。
            第三方jar
                +号选择jars or..，可以把jar文件添加进去，也可以 选择包含jar文件的文件夹添加进去。
    配置maven
        idea内置maven，建议是使用，用自己的。
        Build,Execution,Deployment -> Maven
            三个重要配置
                maven home directory：自己下载的maven目录
                user setting file：maven配置文件，使用阿里云镜像
                local repository：本地仓库位置
            优化配置 Build,Execution,Deployment -> Maven ->importing
                自动下载源码和文档
        创建spring boot项目
            spring initializr -》 next - >group artifact 修改，打包形式war -》下一步 选择依赖        
    debug操作
        打断点：单击左侧栏
        step over 单步执行
        step into 进入方法  
        step out 跳出方法                 
        跳入到下一个断点
        表达式计算 ctrl+u