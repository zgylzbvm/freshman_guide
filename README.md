# freshman_guide
FOR FRESHMAN IN NUDT CORE LAB RESEARCH AND CODING TOOLS                                                                                                                                 
&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&                                                        
针对硕士一年级新生的体系结构研究工具，以及一些需要注意的事项，写在                                  
这里，内容主要包括操作系统使用，相关文献软件的推荐与使用教程，编译                                                       
工具，一些代码规范还有相关的文献、书籍的推荐。                                                                 
#######################################################                         
本文针对国防科技大学计算机学院微处理器研究所硕士新生的指导                                                   
会定期更新内容                                                                     
#######################################################                     
目录：                                                                                                                         
1.操作系统选择                                                                                                                
2.vim使用与配置                                                                                                      
3.文献管理软件                                                                                                                
4.书籍推荐                                                                                                  
5.相关经典处理器与硬件论文的贴贴                                                                                               
————————————————————————我是分割线——————————————————————                                                                 
1.操作系统选择
    操作系统的安装
    推荐使用linux操作系统，优先使用Debian10系列 ： https://www.debian.org/releases/index.zh-cn.html (可以在该网站获取稳定版本）
    其次可以使用Ubuntu20+以上的版本 ： https://cn.ubuntu.com/download/desktop (可以在该网站获取稳定版本）
    https://ubuntu.com/download/desktop (可以选择21版本）
    注意：操作系统需要足够大容量的U盘作为系统盘，可以在京东购买：https://item.jd.com/2148924.html
    注意：操作系统需要符合你的处理器型号！！！                                                                                                         
    注意：需要使用启动盘制作工具，推荐使用Rufus：https://rufus.ie/zh/                                               
    操作系统安装Guide: Ubuntu: https://zhuanlan.zhihu.com/p/135953477                                 
                             https://www.cnblogs.com/masbay/p/10745170.html                                         
                     Debian: https://www.debian.org/releases/stable/amd64/index.zh-cn.html  （官方手册）
                             https://zhuanlan.zhihu.com/p/73122221                                                      
    如果还不会请seek你最近的师兄，人肉救援                                                                                       
    Linux的使用：                                                                                                       
    一个比较明细的教程：http://c.biancheng.net/linux_tutorial/                                        
    菜鸟教程：https://www.runoob.com/linux/linux-tutorial.html                                   
    注意： 最好的学习就是天天使用它                                                                                            
    vim的使用与操作脚本：                                                                                         
    最简单的入门：https://zhuanlan.zhihu.com/p/74633462                                                
    菜鸟教程：https://www.runoob.com/linux/linux-vim.html                                                                            
    git与gitte与github:
    git教程：https://www.w3cschool.cn/git/                                                                     
            https://www.liaoxuefeng.com/wiki/896043488029600
    主要掌握git clone/git push/git pull/git commit/git add/git rebase/git remove/git branch/git status/git log等命令                                   
    开始配置github会比较麻烦，细心或者寻求外援                                                                                                        
    gitte 类似于中国的github 官网 https://gitee.com                                                                                             
    Linux终端：                                                                                                                                    
    打开命令：alt+ctrl+t                                                                                                                         
    一般默认是bash解释器，这里推荐换成zsh                                                                                                              
    可以安装ohmyzsh: https://github.com/ohmyzsh/ohmyzsh                                                                                                                     
    文献管理软件个人建议使用zotero（下载请自行百度）如果你用endnote我觉得也没啥问题的哈
    然后有一点注意的就是，zotero每个月上传流量有限，可以和网盘做链接，这样非常节省流量
    具体的zotero使用可以看下面的教程：https://zhuanlan.zhihu.com/p/98428625?from_voters_page=true
    如何链接云盘：https://content.jianguoyun.com/26288.html
    zotero还有外挂的翻译软件，可以自行安装：https://gitee.com/l0o0/translators_CN
    
    
    具体的文章和科普的文献介绍可以先看这本书 ：Processor Microarchitecture：An Implementation Perspective
    文件的话这个仓库里面会有 ，先到这里嘎嘎
    后面会继续增加关于课题的书和经典的论文嘎嘎
    
    如果你真的是啥都不会的话
    那请看《深入理解计算机系统》，bilibili上面有网课搜 CSAPP 就可以，跟着看完
    看完上面那一本CSAPP,之后要看《计算机组成与设计：软件与硬件接口》 b站上也有课
    最后看计算机体系结构量化研究方法 推荐第六版 
    这些东西是默认你必须会的，不会有人专门为你做讲解和科普，建议功课打好。
    以上教材建议看英文版，看完了就看你需要干啥了，可以来找我，面聊
    然后个人建议，可以去看四大会的论文，看不明白不要紧，可以看那种短篇的B会的论文起手，找到自己的兴趣点最重要，前提请在微处理器领域
    有机会可以看OS相关课程。
    
    关于毕业和研究的时间线
    关于毕业论文和自己的研究需要有自己的timeline建议一周三次找带教老师(做项目带你的人），一个月至少一次和王老师反馈。
    一般建议毕业前的四个月你的实验必须solid，硕士论文建议实际内容两章，如果不会写，实验室有完整的硕士博士论文，可以进行参考全文60-80页（具体看学校要求），实验必须可以重复，所有的结果多次备份，毕业后三年再进行删除。博士论文成型的工作须三篇以上，能够串联成为体系的工作。
    
