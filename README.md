# Java_ReLocation
### java 中的重定向
#### 步骤:

    1. new 一个dynamic web project
    2. IDE(eclipse)中的 window->perspective->costomize perspective->shortcuts
    3. general 中(File,Folder)
    4. java 中设置(class interface,package)
    5. web 中选择(dynamic web project,html file,jsp file, servlet)
    6. xml 中选择, xml file
    7.然后点击 ok
    8.接着 new 两个 servlet 设置他们的 url mapping 分别为/ loc1,/loc2如下图
    9.剩下的就是代码中写的几句了
    重点是重定向:response.sendRedirect("/KBNY/loc2");这个方法
 ![](https://ws1.sinaimg.cn/large/006tKfTcgy1fi3gxy1fhfj30t60rstbi.jpg)
  
