# xmind2testcase
   
Xmind2testcase简介

用来将xmind的测试用例转换到Excel中，导入缺陷管理工具的用力列表中，提高工作效率。



环境要求

xmind2testcase是基于python实现的，要先安装python才能使用。安装过程中特别要注意勾上Add Python 3.8 to PATH，然后点“Install Now”即可完成安装。



安装xmind2testcase

直接在电脑的命令行中运行xmind2testcase就可以了

安装：在本机cmd执行pip3 install xmind2testcase

版本升级 ：在本机cmd执行pip3 install -U xmind2testcase



运行及使用

step1：在cmd中运行xmind2testcase webtool 8000

step2：在网页上访问127.0.0.1:8000即可转化，界面如下





step3：缺陷管理工具如果是禅道的话，选择get zentao csv进行导出即可





乱码


初次使用可能会出现乱码问题，解决方法：通过安装记录找到安装文件的位置

找到xmind2testcase文件夹下面的zentao.py，将编码utf-8修改成gbk





巧思小课堂




原始版本用着有点不顺手，尤其是在项目实行敏捷管理之后。下面就给大家看看我的定制思路。



增加相关需求字段







修改优先级





修改用例类型





xmind的转换模板如下

优先级：在节点右键->图标->任务优先级中选择

相关需求：在节点右键->插入->批注中生成

前置条件：在节点右键->插入->备注中生成



