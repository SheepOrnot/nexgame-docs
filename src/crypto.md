<h1 id="j7Fy4">crypto是什么？</h1>
&nbsp;密码学，但是由于种种原因，古典密码学基本很少在crypto里见到(被赶到misc里了)，更多考察现代密码学，同时也侧重于考察**密码分析学**，即发现并利用某个密码体系的漏洞。

<h1 id="Mja2J">必备工具</h1>
&nbsp;**sagemath**，密码手永远的**白月光**。有句话说得好，只有你想不到，没有sagemath做不到，其语法与python一致，只不过说提供了更多的可调用函数。安装教程：[sagemath 入门笔记 | 独奏の小屋](https://hasegawaazusa.github.io/sagemath-get-started.html)。

&nbsp;**纸和笔**，个人感觉crypto应该是ctf唯一要手算的，有些东西光看可能看不出来，拿笔写写会想得比较明白。

<h1 id="GZVTz">基础知识</h1>
&nbsp;首先，现代密码学是需要一定的理论知识，基本上是**数论**的知识(用不着学很深，留个印象，知道怎么算就行)，随着学习的深入，你会逐渐加深理解。对于入门来说，你需要掌握以下概念(可能会有未涉及到的), 模运算，逆元，欧拉函数，最大公因数的求解，费马小定理等。

&nbsp;其次，需要掌握python的基本语法以及sagemath里常用的一些库函数。

<h1 id="PJa0G">入门线路</h1>
&nbsp;就ctf里的crypto而言，最好的入门方式就是从**RSA**开始学习，首先是了解RSA的加解密流程，然后知道为什么RSA安全。其次是要了解RSA里一些常考的漏洞，这里建议看看ctf-wiki上的[RSA 介绍 - CTF Wiki (ctf-wiki.org)](https://ctf-wiki.org/crypto/asymmetric/rsa/rsa_theory/)，不全，但是讲得比较可以。最全的是这位大佬的[**RSA | Lazzaro (lazzzaro.github.io)**](https://lazzzaro.github.io/2020/05/06/crypto-RSA/)**，**可以当成字典来查。RSA了解得差不多后，就是公钥体系的各种密码，常考的主要有ECC，背包，ElGamal。

&nbsp;公钥了解得差不多之后，就是对称加密体系。对称加密体系其实真正的加密原理并不复杂，主要是流程太多，无非就是异或，替代置换这些。这些建议是边打边学，因为实在很多，题目出的也一般是其变种。

&nbsp;以上都是现代密码，为了对抗量子计算机的攻击，科学家们又提出了后量子密码，其中就包括格密码。格不仅本身能作为一个比较好的密码体系，又能作为一种攻击手段**(crypto一般最难的题就是出格)**

&nbsp;个人认为crypto的新生村的要求就是知道怎么套用网上的脚本就行，可以对原理不是很清楚。之后随着学习的深入，学会自己造。crypto的一大特色之处就在于比较接近科研，攻击方法背后都是有科研论文支撑的，因此读一些经典的crypto论文然后复现也是一种学习方法。

---

&nbsp;另外，再说说密码学这门学科。上面只是针对ctf里的crypto性价比高的入门线路，如果想系统地了解密码学这门学科，建议是按照密码学发展顺序来学，可以看看网上的一些网课，这样可能比较成体系。

<h1 id="GtKUY">学习资料：</h1>
<h2 id="ZwJVo">博客推荐：</h2>
[密码学简介 - CTF Wiki (ctf-wiki.org)](https://ctf-wiki.org/crypto/introduction/):ctf-wiki，虽然不全，但是讲得挺好

[类别: crypto | Lazzaro (lazzzaro.github.io)](https://lazzzaro.github.io/categories/crypto/): lazzaro佬的博客，密码祖师爷，比较全。

[Emmaaaaaaaaaa-CSDN博客](https://blog.csdn.net/XiongSiqi_blog?type=blog): Emmaaaaaaaaa讲得浅显易懂，适合新生入门。

[糖醋小鸡块的blog (tangcuxiaojikuai.xyz)](https://tangcuxiaojikuai.xyz/):主要是比赛wp，适合赛后复现，以及学到中后期的密码手。



持续完善中。。。。。





