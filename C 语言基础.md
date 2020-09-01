# C 语言基础


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536380953274-4663180a-ce95-4b3a-9e4c-c96a03a92d66.png#align=left&display=inline&height=59&originHeight=61&originWidth=858&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536381712595-806e0c3f-3987-4579-bafa-4afb044587ab.png#align=left&display=inline&height=115&originHeight=167&originWidth=1204&status=done&width=827)

### 1、system 函数的使用

system 函数可以调用系统的cmd命令。
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536381866938-426dc101-68a8-4c76-affd-87b5a257ed87.png#align=left&display=inline&height=442&originHeight=442&originWidth=827&status=done&width=827)

### 2、c 程序编译步骤

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536383882411-a328ca69-24d8-478e-810c-7addae9cb86f.png#align=left&display=inline&height=233&originHeight=272&originWidth=966&status=done&width=827)


**gcc 编译过程**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536384167364-cd614a6b-a64b-47d3-92c1-9a8af690d57e.png#align=left&display=inline&height=348&originHeight=398&originWidth=947&status=done&width=827)



**程序的执行过程**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536385303581-f23a0cd2-3d38-4aaa-8ed7-dce6f2776cf4.png#align=left&display=inline&height=336&originHeight=495&originWidth=1218&status=done&width=827)


参考资料：
linux c 函数参考手册
[Linux C函数参考手册(PDF版).pdf](https://www.yuque.com/attachments/yuque/0/2018/pdf/105541/1536388023706-fe0b940f-03b7-4820-bab8-d95b9b47ae79.pdf?_lake_card=%7B%22src%22%3A%22https%3A%2F%2Fwww.yuque.com%2Fattachments%2Fyuque%2F0%2F2018%2Fpdf%2F105541%2F1536388023706-fe0b940f-03b7-4820-bab8-d95b9b47ae79.pdf%22%2C%22name%22%3A%22Linux+C%E5%87%BD%E6%95%B0%E5%8F%82%E8%80%83%E6%89%8B%E5%86%8C%28PDF%E7%89%88%29.pdf%22%2C%22size%22%3A1447086%2C%22ext%22%3A%22pdf%22%2C%22type%22%3A%22application%2Fpdf%22%2C%22id%22%3A%22L3n8F%22%2C%22card%22%3A%22file%22%7D)

Windows 平台下 Depends.exe 软件可以查看可以执行文件的依赖库。

### 3、CPU 内部结构与寄存器（了解）

**3.1、64位系统和32位系统的区别**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536388668142-c892ed31-4762-415a-b622-420c7dc75c58.png#align=left&display=inline&height=334&originHeight=352&originWidth=871&status=done&width=827)

**3.2、寄存器名字**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536388770860-47e8d95e-d8ff-446d-8fa8-fb11222c2eb8.png#align=left&display=inline&height=184&originHeight=189&originWidth=849&status=done&width=827)

3.3、寄存器、内存、缓存三者的关系
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536388907171-b92e3b26-86ef-499d-b351-af58bf715d48.png#align=left&display=inline&height=44&originHeight=44&originWidth=833&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536389205275-3c51b391-a253-488b-b139-2db8eaca004b.png#align=left&display=inline&height=311&originHeight=322&originWidth=857&status=done&width=827)


### 4、c 语言基础

**4.1、c 语言关键字**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536391856812-324064ae-b83e-4e0e-8367-18f3845a9a60.png#align=left&display=inline&height=382&originHeight=385&originWidth=834&status=done&width=827)

**4.2、变量**

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536392618269-7ab9d042-4aa9-477a-90e6-e2cab2ca0b97.png#align=left&display=inline&height=419&originHeight=422&originWidth=833&status=done&width=827)


**4.3、数据类型**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536392129511-d67911b7-ca2a-49ca-8c2a-a66642a0a495.png#align=left&display=inline&height=410&originHeight=449&originWidth=906&status=done&width=827)

### sizeof 关键字

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536393795071-4da04fb8-719b-405b-9f77-896db388edc0.png#align=left&display=inline&height=450&originHeight=483&originWidth=888&status=done&width=827)

sizeof(数据类型)、sizeof(变量名)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536395313780-01937a9c-5076-4a56-aa72-b65b139377dc.png#align=left&display=inline&height=195&originHeight=201&originWidth=851&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536395461007-8a8a1c76-e8da-4921-9953-4a46554ffaf7.png#align=left&display=inline&height=289&originHeight=307&originWidth=877&status=done&width=827)

### 5、计算机内存中数值的存储方式

**原码**
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536401626320-0e8a1b04-ccc6-4a59-87a1-2adeabefe146.png#align=left&display=inline&height=456&originHeight=474&originWidth=860&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536401742678-22c5fdf4-0fd9-4fd6-86c7-0bfcb226a0d6.png#align=left&display=inline&height=561&originHeight=569&originWidth=839&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536401858618-af3a4937-ef1b-4e34-a5b7-08abe7fb1da8.png#align=left&display=inline&height=475&originHeight=476&originWidth=829&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536402945098-6ac20af9-9c0b-438a-8a65-99f5e80d359a.png#align=left&display=inline&height=374&originHeight=387&originWidth=856&status=done&width=827)






![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536468665425-c9b6a6a5-0b23-4d60-be59-011b5a3ba8ba.png#align=left&display=inline&height=332&originHeight=398&originWidth=990&status=done&width=827)


### 变量的声明
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536575174412-29016076-9ed8-4f00-b3c7-76d58f236a6a.png#align=left&display=inline&height=229&originHeight=258&originWidth=932&status=done&width=827)
```c
//变量声明，一般不写
extern  int  a;

// 变量定义并赋值
int a=10;
```



![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536469238404-0104fe14-8256-40e6-a99b-c1195bf6818b.png#align=left&display=inline&height=453&originHeight=522&originWidth=952&status=done&width=827)





![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536469791039-e2cea468-eadb-45cb-8945-cd43d9afbdeb.png#align=left&display=inline&height=87&originHeight=95&originWidth=902&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536469767134-163f5ad0-5f84-4944-aec4-97ce88891b6f.png#align=left&display=inline&height=143&originHeight=158&originWidth=915&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536469691337-db146b99-f19f-444c-b692-80d84c640b3e.png#align=left&display=inline&height=494&originHeight=547&originWidth=915&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536469893813-1058ac0a-310e-4e93-8ab4-8ad0b97ed312.png#align=left&display=inline&height=314&originHeight=326&originWidth=858&status=done&width=827)




![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536473354199-391d3e73-6ed5-4c5f-a82a-5362d5fe2153.png#align=left&display=inline&height=540&originHeight=602&originWidth=922&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536484464046-f884314a-910f-47ef-a0a6-95bfbff557e4.png#align=left&display=inline&height=512&originHeight=596&originWidth=963&status=done&width=827)

数字0等价于‘\0’，但不等价‘0’(字符0)。


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536485625238-d82c0501-2f6b-44a3-99b5-e1eb7209fbba.png#align=left&display=inline&height=553&originHeight=637&originWidth=952&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536485806988-44b7d465-4f65-49fb-ab28-16562fb4be21.png#align=left&display=inline&height=501&originHeight=568&originWidth=937&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536485893946-d13a82c7-d555-4f19-be1f-123aea777380.png#align=left&display=inline&height=113&originHeight=126&originWidth=924&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536486043940-2b8998c4-cdbd-40e7-8f3b-61b7fdd2624b.png#align=left&display=inline&height=494&originHeight=559&originWidth=936&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536486157555-1751eba9-5f51-4045-b40b-4f92293d5e13.png#align=left&display=inline&height=286&originHeight=327&originWidth=945&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536486329396-7242770c-6c55-44eb-9740-4ee866eefce9.png#align=left&display=inline&height=142&originHeight=158&originWidth=922&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536486315785-a14dc73d-21ae-4fc6-b94f-2e3f0786a084.png#align=left&display=inline&height=309&originHeight=353&originWidth=945&status=done&width=827)



### 随机数
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536572818149-81b59825-da3a-4447-b2df-8935b08ebff1.png#align=left&display=inline&height=500&originHeight=548&originWidth=906&status=done&width=827)


### 多文件编程

头文件主要用来进行全局变量的定义、函数声明。
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536576365190-82366ced-66d3-445b-be68-dd4cdfcb5a2a.png#align=left&display=inline&height=245&originHeight=277&originWidth=936&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536576447321-7e69e961-3d9b-4564-b0fd-2b52cd90479b.png#align=left&display=inline&height=111&originHeight=124&originWidth=926&status=done&width=827)


“#progma once”一般用于Windows 平台下，linux 平台下只能用“#ifndef”避免重复包含。

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078081176-bae83b06-418a-4cff-91ca-66362346d14d.png#align=left&display=inline&height=512&originHeight=576&originWidth=930&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078135894-3ae0c309-7e75-4d45-b41e-09680b567a84.png#align=left&display=inline&height=386&originHeight=443&originWidth=948&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078156888-3ae78e4a-ee01-4b8b-9afd-135f71f714ec.png#align=left&display=inline&height=295&originHeight=339&originWidth=949&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078171060-b1da107a-297d-4f86-b773-2b163de5dd0b.png#align=left&display=inline&height=391&originHeight=446&originWidth=944&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078034738-255be8f2-c086-46f2-aa85-338519f5af82.png#align=left&display=inline&height=226&originHeight=259&originWidth=948&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078014751-97516244-70d7-4d56-bbbc-f38ee9be40f2.png#align=left&display=inline&height=343&originHeight=383&originWidth=923&status=done&width=827)



![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536576794873-2a7ae2e7-5d75-4e8b-8bd9-e6b9ec0ebe5f.png#align=left&display=inline&height=301&originHeight=338&originWidth=928&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536577924335-cd28677e-5989-41dc-ab69-e9bd8991d8c0.png#align=left&display=inline&height=195&originHeight=220&originWidth=934&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536578862235-aead0064-aebe-49c5-a71a-4d09de1307da.png#align=left&display=inline&height=508&originHeight=582&originWidth=948&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536578959929-8277a0fa-eb1a-4c3a-b0da-1d16ad627195.png#align=left&display=inline&height=136&originHeight=154&originWidth=939&status=done&width=827)

**野指针**：指针变量指向一个未知的空间（指针所指向内存中的值未知）

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536578837305-1769a5f0-1bfe-4445-96c1-1dc45bf368e4.png#align=left&display=inline&height=301&originHeight=316&originWidth=867&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536579284473-008d892b-4ab0-4a58-9843-0ad12a2f1ab8.png#align=left&display=inline&height=174&originHeight=176&originWidth=838&status=done&width=827)



![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536658711567-713c859d-7d8f-4f42-83d5-6b756c2c1deb.png#align=left&display=inline&height=263&originHeight=299&originWidth=939&status=done&width=827)

万能指针可以接收任意类型变量的内存地址，但是通过万能指针修改变量的值时，需要找到变量对应的指针类型。

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536659259817-c3554e2f-827e-4477-8e9a-f8407d4c3cc6.png#align=left&display=inline&height=424&originHeight=484&originWidth=945&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536660535618-d4b71dc5-9f90-4042-9bd1-9ffacf8e9a05.png#align=left&display=inline&height=429&originHeight=564&originWidth=1087&status=done&width=827)


指针可以修改 const 修饰的变量，二级指针可以修改 const 修饰的一级指针。
& 是升维度，* 是降维度。


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536660971002-14f58a8c-46bb-4959-aed6-c3cb34fa69dd.png#align=left&display=inline&height=282&originHeight=318&originWidth=934&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536662987278-74c32f5a-a6f7-4911-9a3c-f2832fb4fe18.png#align=left&display=inline&height=94&originHeight=94&originWidth=825&status=done&width=825)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536663584997-ceb1c2b6-e1b9-4f20-8051-6ba940c1c69e.png#align=left&display=inline&height=165&originHeight=165&originWidth=778&status=done&width=778)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536744948464-f1412b17-c2fe-4aa3-ba11-3eec4a0db689.png#align=left&display=inline&height=185&originHeight=210&originWidth=941&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536980796113-821ecb6f-4705-43a0-a8ab-6cdc8cb2617b.png#align=left&display=inline&height=475&originHeight=555&originWidth=966&status=done&width=827)
两个指针相减得到的是步长（两个指针之间的偏移量或者两个指针相差多少个字节）。


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536747154900-36c6684e-32ed-41f4-92dc-7412af3a5a88.png#align=left&display=inline&height=419&originHeight=481&originWidth=950&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536748119251-478579c0-9f54-4d7a-aa72-ea2bbfb065f1.png#align=left&display=inline&height=313&originHeight=331&originWidth=874&status=done&width=827)

字符串数组也是指针数组的一种模式。

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536748716161-00b7a915-504a-4fb5-9840-03bcd9db2544.png#align=left&display=inline&height=411&originHeight=468&originWidth=941&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536981223998-40cca42e-054c-4e41-92f8-785e46ffd875.png#align=left&display=inline&height=402&originHeight=464&originWidth=955&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536981309541-21bc7500-b318-42d0-98a8-fdd9eac35e7b.png#align=left&display=inline&height=473&originHeight=538&originWidth=941&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536834390164-7fcb6635-bc8b-4c42-8386-6e51eaa1799f.png#align=left&display=inline&height=384&originHeight=442&originWidth=952&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536836100601-da613b5c-3c82-4d8f-9b8d-f282ac833e22.png#align=left&display=inline&height=458&originHeight=517&originWidth=934&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536981750838-b3212b4a-3b18-4401-b452-67a44240c204.png#align=left&display=inline&height=521&originHeight=601&originWidth=954&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537003393640-24703ba6-daba-470c-9732-6427e5d9cf80.png#align=left&display=inline&height=328&originHeight=328&originWidth=824&status=done&width=824)



![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536992858944-2b7b8de6-6a24-48ba-b3f1-199b8642b492.png#align=left&display=inline&height=520&originHeight=594&originWidth=944&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536993091390-d1aaef6b-cfae-481e-b910-7428db1cc61a.png#align=left&display=inline&height=248&originHeight=280&originWidth=933&status=done&width=827)


### 主函数参数
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1536994544740-5129bab6-b77e-425b-ac56-4a357a7aeb3a.png#align=left&display=inline&height=482&originHeight=552&originWidth=948&status=done&width=827)




![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537066423516-4af678b4-8cdf-492f-a285-e3ac245c7b01.png#align=left&display=inline&height=348&originHeight=397&originWidth=944&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537067576799-3119ddaa-362a-49a1-b6a7-ccd62f81532c.png#align=left&display=inline&height=307&originHeight=350&originWidth=943&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537067823464-9f3ef291-d8d2-4df8-8969-ee93a5b03225.png#align=left&display=inline&height=426&originHeight=488&originWidth=947&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537068118732-7a8fedc5-e3f8-439c-833c-9242439ddddd.png#align=left&display=inline&height=362&originHeight=413&originWidth=943&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537068007978-71dc67e8-1c3f-489b-971a-e7e7e48af50c.png#align=left&display=inline&height=381&originHeight=434&originWidth=941&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537075877036-ceff20f9-015d-4b80-a985-7012645d6627.png#align=left&display=inline&height=420&originHeight=478&originWidth=941&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537076441245-640fc2e3-2322-4d8e-b8ca-18a8139e06a6.png#align=left&display=inline&height=386&originHeight=439&originWidth=940&status=done&width=827)



总结
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537076875887-b05db86f-ec42-4987-98c2-0928bd8aadb8.png#align=left&display=inline&height=263&originHeight=382&originWidth=1200&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537076957602-e9d2153b-b1a1-4c2a-8149-dfa44b80ae9d.png#align=left&display=inline&height=360&originHeight=492&originWidth=1130&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537077040527-b0d692d9-f780-4688-a5f6-ad43a015b8d0.png#align=left&display=inline&height=208&originHeight=276&originWidth=1100&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078400953-e89c4620-1d3b-4bbc-8eef-37874b39096a.png#align=left&display=inline&height=482&originHeight=557&originWidth=955&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537079643473-c14d1b10-1056-4fad-b9d6-bcff50db4b80.png#align=left&display=inline&height=235&originHeight=263&originWidth=924&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537079116885-72c1e52e-8810-4649-a057-f5e07002339d.png#align=left&display=inline&height=484&originHeight=540&originWidth=923&status=done&width=827)

总结
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537081340986-43c60c16-488c-4b34-b895-a0d3194a611d.png#align=left&display=inline&height=402&originHeight=553&originWidth=1138&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537083548099-53440005-5e4a-4429-9ba5-d7556bacdf34.png#align=left&display=inline&height=134&originHeight=152&originWidth=941&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537082671205-61f2bfe2-7c38-49b7-9eb4-faf312f0297d.png#align=left&display=inline&height=213&originHeight=237&originWidth=919&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537083499782-4b06de29-e3e4-4609-84df-4a9d621b239b.png#align=left&display=inline&height=254&originHeight=284&originWidth=924&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537083455909-056b0541-c1f5-4701-8115-5cb0630a2e25.png#align=left&display=inline&height=347&originHeight=405&originWidth=965&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537083665635-958f603b-266c-4cab-ac4f-43d792aa06a9.png#align=left&display=inline&height=372&originHeight=430&originWidth=957&status=done&width=827)



![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078477698-fbb2e29f-58a8-4cac-b0f7-5e21c0c271bf.png#align=left&display=inline&height=428&originHeight=497&originWidth=960&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078512169-6cf57c54-c0d9-4ed1-b04e-72c574aac392.png#align=left&display=inline&height=133&originHeight=147&originWidth=912&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078562889-2bb58d2c-4aef-4ec2-83b5-49d40691b290.png#align=left&display=inline&height=343&originHeight=381&originWidth=919&status=done&width=827)![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078594392-0e66184f-ea5d-43df-9988-bbaafbb6f815.png#align=left&display=inline&height=254&originHeight=284&originWidth=926&status=done&width=827)![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078623892-8aae811f-9ea5-4d52-8526-3143175ee2d2.png#align=left&display=inline&height=338&originHeight=400&originWidth=979&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078649218-591cf532-af6e-4544-b10f-1d65a216a0d9.png#align=left&display=inline&height=396&originHeight=444&originWidth=927&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078700800-0ee5c161-b2b3-405b-a0bd-b81c649c6c49.png#align=left&display=inline&height=300&originHeight=337&originWidth=930&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537085734764-d3ab8186-0083-4a78-a230-aa61a808043f.png#align=left&display=inline&height=585&originHeight=585&originWidth=827&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537086753136-313fc10d-1d52-424a-8372-c76dafdc2702.png#align=left&display=inline&height=207&originHeight=339&originWidth=1355&status=done&width=827)

栈模型
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537087399924-d6541b9f-1ee6-4033-9f6d-822b0b3a7095.png#align=left&display=inline&height=469&originHeight=604&originWidth=1064&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078771960-67912e6e-38b5-4b54-807b-dca96a46a2c2.png#align=left&display=inline&height=310&originHeight=361&originWidth=964&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078790985-94895e3c-e25f-4e7e-aa58-00219c6b748c.png#align=left&display=inline&height=235&originHeight=264&originWidth=928&status=done&width=827)

memset() 函数主要作用是将一段内存空间的值设置为 0。

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537682940711-9d6b7266-e001-49f1-b53e-7383e78605eb.png#align=left&display=inline&height=287&originHeight=327&originWidth=943&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537683518108-525fe56d-0a63-4066-9d9f-c0e3627c9cec.png#align=left&display=inline&height=443&originHeight=517&originWidth=966&status=done&width=827)



![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078809015-5d9c5fd3-be65-411b-9feb-5ca731e6c252.png#align=left&display=inline&height=396&originHeight=452&originWidth=945&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537087864550-39dd7b03-7530-49fa-aee7-62bd722e0e04.png#align=left&display=inline&height=307&originHeight=347&originWidth=935&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537078844861-821a9e3f-10db-4fd1-b7e2-abd31a9688c9.png#align=left&display=inline&height=447&originHeight=513&originWidth=950&status=done&width=827)


### 常见内存问题
1、数组下标越界。
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537690827888-4cee5db2-446e-47de-8dd8-dd89db8c1d93.png#align=left&display=inline&height=193&originHeight=208&originWidth=892&status=done&width=827)
内存操作时，数组越界。

2、申请堆内存0字节空间、申请的内存空间应和存储的类型对应![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537688424104-9d544ca6-80e2-43f0-8904-c97be14eb6da.png#align=left&display=inline&height=58&originHeight=58&originWidth=773&status=done&width=773)
存储2个整型内存剩余，存储3个整型，内存不够。

3、同一个堆空间多次释放。
```c
int* p=(int*)malloc(sizeof(int)*10);
free(p);
free(p);//堆空间不允许多次释放

p=NULL;
free(p);
free(p);//空指针允许多次释放
```

4、释放的指针与申请的指针不同
```c
int* p=(int*)malloc(sizeof(int)*10);
p++;//改变指针指向
free(p);
```


### 二级指针对应的堆空间

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537760947141-ecbdd6be-1da3-46f9-85f4-de8c83d9720d.png#align=left&display=inline&height=273&originHeight=273&originWidth=824&status=done&width=824)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537760835904-6a9c7ab8-48f0-46e9-bdb1-e8e46021cade.png#align=left&display=inline&height=354&originHeight=564&originWidth=1319&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537760997619-01647467-6084-4715-acc8-4cbcb1cadafb.png#align=left&display=inline&height=320&originHeight=362&originWidth=935&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537761089948-ae7a4290-3f5e-47ca-aa03-845605cdf7a3.png#align=left&display=inline&height=302&originHeight=322&originWidth=883&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537761171334-7fad502d-7664-4b67-bca8-4d0527d26298.png#align=left&display=inline&height=190&originHeight=198&originWidth=862&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537761202236-b68b798a-f169-4da9-aa6a-5faa493ebd64.png#align=left&display=inline&height=304&originHeight=318&originWidth=866&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537766329295-31ea8854-8a96-4d06-ab0e-1ba13afff307.png#align=left&display=inline&height=129&originHeight=142&originWidth=911&status=done&width=827)


开辟堆空间存储结构体
```c
struct student{
    char name[21];
    int age;
};

struct student * stu =(struct student*)malloc(size0f(struct student)*3);
```


### 结构体和指针
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537766978455-81de431b-0d1e-4a0e-913c-81745c1ccbd6.png#align=left&display=inline&height=234&originHeight=235&originWidth=830&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537770539474-913283ca-ad24-4299-86b4-8abdfbcadc08.png#align=left&display=inline&height=268&originHeight=305&originWidth=941&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537771325547-dd3ab127-6fb3-45b4-a2d1-a8cf0b4b64dc.png#align=left&display=inline&height=370&originHeight=419&originWidth=937&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537771477166-3099fe2f-eb0d-46fc-b2be-8040f4f88f98.png#align=left&display=inline&height=260&originHeight=303&originWidth=964&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1537771958442-e4b7674a-8918-46a5-8bef-4b77056d1bdc.png#align=left&display=inline&height=557&originHeight=557&originWidth=938&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538461304336-3cb2d228-a8f6-416b-be31-cef496a9e688.png#align=left&display=inline&height=496&originHeight=496&originWidth=923&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538461672955-288dc701-acd7-4f12-83bb-dcd1f4421824.png#align=left&display=inline&height=486&originHeight=486&originWidth=929&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538461879466-b214e3bd-7a19-419a-9a72-f9c0c08869dd.png#align=left&display=inline&height=536&originHeight=536&originWidth=885&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538462465184-0748442d-43bb-4821-8d0e-38fc030e986b.png#align=left&display=inline&height=628&originHeight=628&originWidth=943&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538462725938-912b815e-feeb-494e-9f95-cc689088bfee.png#align=left&display=inline&height=383&originHeight=383&originWidth=914&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538462765783-1ed8a0f6-09c8-4a3d-bb08-6ff128afe78e.png#align=left&display=inline&height=409&originHeight=409&originWidth=901&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538462864935-6fd6263d-2892-4da8-a02c-61ebd2dbd7c6.png#align=left&display=inline&height=384&originHeight=384&originWidth=948&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538462912816-22b072a4-7e81-4251-a0fc-5af607884415.png#align=left&display=inline&height=443&originHeight=443&originWidth=945&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538462941408-125ce228-4e68-4cb1-802b-1eece6a93d96.png#align=left&display=inline&height=349&originHeight=349&originWidth=920&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538463205229-8e466616-4868-4a7f-9082-921214555a87.png#align=left&display=inline&height=311&originHeight=311&originWidth=926&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538463230881-b0bf9b55-6d06-4051-98b9-fbf5dd5332f2.png#align=left&display=inline&height=534&originHeight=534&originWidth=939&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538463283159-14eb588e-5c7b-46e5-be5c-f43ac0c6ccda.png#align=left&display=inline&height=72&originHeight=72&originWidth=924&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538463263475-a08714ae-a970-42ad-a404-53187ae9b77d.png#align=left&display=inline&height=517&originHeight=517&originWidth=937&status=done&width=827)

打开文件失败的原因
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538463616540-32c50a04-83dc-4d0b-af21-bcf1556feda2.png#align=left&display=inline&height=91&originHeight=91&originWidth=822&status=done&width=822)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538556238912-e1e0a851-010a-4a08-b78b-00c7afb7f5e8.png#align=left&display=inline&height=73&originHeight=73&originWidth=940&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538464254206-f3139af9-a51b-4ae3-acf2-c2284438870c.png#align=left&display=inline&height=391&originHeight=446&originWidth=944&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538464284302-7481d371-53a1-4583-a0b2-76c94ddbcc9c.png#align=left&display=inline&height=236&originHeight=266&originWidth=932&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538464315350-38d0778e-e2f7-493d-9867-fcdb55007345.png#align=left&display=inline&height=448&originHeight=505&originWidth=932&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538464335237-96b29fe5-4cd8-497b-a44f-2d276d23bc3e.png#align=left&display=inline&height=259&originHeight=290&originWidth=927&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538464468717-a258d3a8-2ec6-4f07-9d9c-2a7020eda020.png#align=left&display=inline&height=292&originHeight=331&originWidth=938&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538539144267-95f0ecc1-cb7d-4de7-b259-4a5c4f1d1544.png#align=left&display=inline&height=388&originHeight=446&originWidth=951&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538556398150-04c50fe0-7bff-41b0-802e-b284529c118a.png#align=left&display=inline&height=226&originHeight=258&originWidth=944&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538540360428-65e12bbb-260c-4ee9-baab-fcb5f8044f60.png#align=left&display=inline&height=264&originHeight=264&originWidth=827&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538539389727-42eb900e-3a76-4952-8a62-ccb243eb68af.png#align=left&display=inline&height=380&originHeight=432&originWidth=940&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538539595382-5e1604e2-3f54-4787-9265-ece88c2da6f9.png#align=left&display=inline&height=377&originHeight=377&originWidth=829&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538542504212-2731b55c-5acf-410b-860c-fc0e1ae0ede1.png#align=left&display=inline&height=491&originHeight=566&originWidth=954&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538545354132-fb810ef7-7453-4403-a144-e68ae8c06f5c.png#align=left&display=inline&height=457&originHeight=523&originWidth=947&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538545484800-672edfa7-3e4b-4576-b9da-c5585df2718a.png#align=left&display=inline&height=261&originHeight=261&originWidth=828&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538550022118-e37c5e5d-0bd0-41e9-9aab-6737194657f5.png#align=left&display=inline&height=438&originHeight=508&originWidth=959&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538550070602-7fe39315-c3e4-414e-9bb1-0c8040738253.png#align=left&display=inline&height=422&originHeight=476&originWidth=932&status=done&width=827)

写入
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538550874989-40969dda-66b5-40dc-82c6-bb36f0dd5d9e.png#align=left&display=inline&height=253&originHeight=254&originWidth=830&status=done&width=827)
读取
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538551190407-5612b423-8c01-4a1f-9f60-ccc16a1a2f58.png#align=left&display=inline&height=263&originHeight=264&originWidth=830&status=done&width=827)


写入一个数组
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538551143863-2bf5c090-a90c-4ebd-b02b-857da7c5cea8.png#align=left&display=inline&height=313&originHeight=313&originWidth=828&status=done&width=827)
读取一个数组
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538551252630-9775a433-280f-4321-adba-7827e8f78deb.png#align=left&display=inline&height=97&originHeight=97&originWidth=829&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538551265585-600f37a4-98da-4d8b-9712-4f7da5c9043f.png#align=left&display=inline&height=93&originHeight=93&originWidth=826&status=done&width=826)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538551286250-189792c1-c586-4d86-89dd-50a739de8f82.png#align=left&display=inline&height=177&originHeight=178&originWidth=830&status=done&width=827)




![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538558583924-70e25d25-e509-47ef-950c-118fcf79105a.png#align=left&display=inline&height=518&originHeight=589&originWidth=941&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538558841524-b3ff4778-e7d6-4c49-a864-c3d120aafec0.png#align=left&display=inline&height=361&originHeight=410&originWidth=939&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538628799458-7613771b-8d74-45ef-b127-793c1d6558ff.png#align=left&display=inline&height=418&originHeight=464&originWidth=919&status=done&width=827)


![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538557873719-65a8ce63-2fae-4d24-95eb-d7c6e34ae232.png#align=left&display=inline&height=347&originHeight=400&originWidth=954&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538557941409-f30b1db0-e367-47f6-8404-8a382f2e72c5.png#align=left&display=inline&height=361&originHeight=406&originWidth=931&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538628832003-dc363e95-ea60-4e0d-8dda-7fca7dd2c186.png#align=left&display=inline&height=543&originHeight=619&originWidth=943&status=done&width=827)

rename()方法还可以移动文件。
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538629066012-b4a2dbf3-1527-4f06-aace-bf9a6ca19d7f.png#align=left&display=inline&height=65&originHeight=65&originWidth=829&status=done&width=827)

![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538629128909-60b3f7e2-fd5d-45c8-b208-ecf92181991f.png#align=left&display=inline&height=403&originHeight=460&originWidth=943&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538629544469-cb3379d4-55fc-4fe3-b25a-a0701c195ea9.png#align=left&display=inline&height=386&originHeight=432&originWidth=925&status=done&width=827)
![](https://cdn.nlark.com/yuque/0/2018/png/105541/1538629516957-68dd19f6-1f82-4aa4-a0df-866ccb636a71.png#align=left&display=inline&height=291&originHeight=330&originWidth=937&status=done&width=827)

