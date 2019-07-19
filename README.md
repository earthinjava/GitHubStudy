# GitHubStudy
gitHub的学习笔记
===============
将项目同步化：
----------------
    1.为文件创建git本地库<br>
    2.可忽略的文件<br>
      (1).classpath为Eclipse管理文件与项目无关<br>
      (2).project为Eclipse管理文件与项目无关<br>
      (3).settings为Eclipse管理文件与项目无关<br>
      (4).target(编译的文件)<br>
    3.金色圆柱体为已被提交同步到本地库中。<br>
    4.问号未被缓存，在git中表示此文件在git工作树下， 但并没有加入到git库, 不参与版本控制，可加入到staged中。<br>
    5.绿色加号为已被添加到缓存（staged），点击commit提交将把本地库同步。<br>
    6.Push推送到远程库<br>
将远程库文件完全克隆到本地：
----------------
    1.Import导入<br>
    2.选择导入方式为git -projects from git<br>
    3.选择利用Clone URI导入<br>
    4.从github中复制库的URI,粘贴到Eclipse中;<br>
    5.建议项目的本地存储地址改为eclipse的工作地址。<br>
    6.选择一种方式导入到eclipse；<br>
        ①以一种已存在的eclipse项目文件方式导入<br>
        ②以新项目的方式导入（会变成新工程的子目录）<br>
        ③以一种通用工程导入（通常选这个)<br>
    7.右键configure -convent to maven project<br>

冲突的来源：修改的内容基础变成了不是最新的，所以导致冲突。
----------------
