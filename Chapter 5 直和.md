第五章

# 直接和

## 5.1总额、直接总额、直接产品

有一些从旧的向量空间形成新的向量空间的有用方法，特别是直接积和直接和。关于直接和，有一个微妙的点，即如果我们试图用笛卡尔积e×f来定义两个向量空间的直接和e`f，由于e`f=f`e的元素，我们没有得到正确的概念。因此，我们想把e×f的元素按顺序排列。对，但我们需要未重新排列的元素对。通过考虑一个家庭的直接总和是可能的。

（ei）i 1,2，更一般地说是家族（ei）i i。为了简单起见，我们首先考虑i 1,2的情况。

定义5.1。`在两个向量空间的一个族（2（或余积）eof the family 1）i∈1,2中，我们将（ei）i∈1,2定义为集（外部）

直接和e1

e1 ae2=h1，ui，h2，vi u∈e1，v∈e2，

添加

h1，u1i，h2，v1i+h1，u2i，h2，v2i=h1，u1+u2i，h2，v1+v2i，

和标量乘法

λh1，ui，h2，vi=h1，λui，h2，λvi。

我们将in1:e1→e1`e2和in2:e2→e1`e2中的注入定义为线性映射，这样in1（u）=h1，ui，h2,0i，

且in2（v）=h1,0i，h2，vi。

一百一十九

注意

e2 ae1=h2，vi，h1，ui v∈e2，u∈e1=e1 ae2.

因此，e1`e2的每个成员h1、ui、h2、vi可以被视为一个无序对，由两个向量u和v组成，分别用索引1和2标记。

注：事实上，e1`e2只是家族（ei）i 1,2 ei的产物。

这不能与笛卡尔积e1×e2混淆。向量空间e1×e2是所有有序对hu，vi的集合，其中u∈e1，v∈e2，加上和乘上一个标量定义如下：

hu1，v1i+h u2，v2i=hu1+u2，v1+v2i，λhu，vi=hλu，λvi.

qi∈1,2 ei和e1×e2之间有一个双射，但正如我们刚才所看到的，qi∈1,2 ei的元素是一定的集合。也可以定义任意数量向量空间的积e1×····×en。我们很快就会做到。

以下属性保留。

提案5.1.给定任意两个向量空间e1和e2，集合e1`e2是向量空间。对于每对线性映射，f:e1→g和g:e2→g，都有一个唯一的线性映射，f+g:e1`e2→g，这样（f+g）in1=f和（f+g）in2=g，如下图所示：

EIN1E‘1EPP2PPPPFPPPNPN’/7 g f+g

2欧nnnn

在nnnng

神经网络神经网络

E2

证据。定义

（f+g）（h1，ui，h2，vi）=f（u）+g（v）

对于每个u∈e1和v∈e2。立即验证F+G是具有所需性质的唯一线性映射。

我们已经注意到e1`e2与e1×e2是双射的。如果我们定义投影π1:e1`e2→e1和π2:e1`e2→e2，这样

π1（h1，ui，h2，vi）=u，

π2（h1，ui，h2，vi）=v，

我们有以下建议。


 

提案5.2.对于任意两个向量空间e1和e2，对于每对线性映射，f:d→e1和g:d→e2，都有一个唯一的线性映射，f×g:d→e1`e2，这样π1（f×g）=f和π2（f×g）=g，如下图所示：

FN nnnnnn 7 Eo 1π1

神经网络

D PNPNPNPNPNPFGP×PPGPPP/PPEP1（E'π22E2

证据。定义

（f×g）（w）=h1，f（w）i，h2，g（w）i，

对于每一个w∈d，立即证明f×g是具有所需性质的唯一线性映射。

注：有限族的直和与积同构是线性代数的一个特点。然而，对于无限族的积和和来说，这不再是正确的。

当u，v是向量空间e的子空间时，让i1:u→e和i2:v→e作为包含映射，如果u'v在命题5.1给出的i1+i2映射下与e同构，我们说e是u和v的直接和，我们写e=u'v（略带滥用符号，因为e和u'v a只是同构的）。定义e的任意子空间的和u1+············································

定义5.2.如果p≥2个向量空间e1，…，ep，则积f=e1×···································

（u1，…，向上）+（v1，…，vp）=（u1+v1，…，向上+vp）λ（u1，…，向上）=（λu1，…，λ向上）

对于所有的ui，vi∈ei和allλ∈r，e1×·····×ep的零向量是p-元组。

，

其中，第i个零是ei的零向量。

通过上述加法和乘法，向量空间f=e1×······×ep称为向量空间e1，…，ep的直积。

作为一种特殊情况，当e1=····=ep=r时，我们又找到了向量空间f=rp，投影图pri:e1×·····×ep→ei由

pri（u1，…，向上）=ui

显然是线性的。同样，地图ini:ei→e1×····×ep由

ini（ui）=（0，…，0，ui，0，…，0）

是内射的和线性的。如果dim（ei）=ni，如果（）是i=1，…，p的ei基础，那么很容易看出n1+····+np向量

（e11,0，…，0），…，（e1n1,0，…，0），

………

（0，…，0，ei1，0，…，0），…，（0，…，0，eini，0，…，0），

………

（0，…，0，ep1），…，（0，…，0，epnp）

构成e1×······×ep的基础，依此类推。

尺寸（e1×·····×ep）=dim（e1）+····+dim（ep）。

现在让我们考虑向量空间e和p的子空间u1，…，向上到e。我们有一个地图。

A:U1×·····×向上→E

由a（u1，…，up）=u1+·····+up给出，

当ui∈ui表示i=1，…，p时，很明显这张地图是线性的，因此它的图像是e的一个子空间，表示为

U1+·····+向上

称为子空间U1的和，…，向上。根据定义，

U1+·······+上·····································

并立即证明U1+·····································这也意味着U1+······+向上不依赖于因子ui的顺序；特别是，

u1+u2=u2+u1。

如果图A是内射的，那么根据命题3.12，我们得到了

每个0都是e的零向量，这意味着如果ui∈ui代表i=1，…，p和if

U1+·····+向上=0，

那么（u1，…，up）=（0，…，0），也就是说，u1=0，…，up=0。在这种情况下，每个u∈u1+······+up都有一个独特的表达式作为和

U=U1+·····+向上，

对于ui∈ui，对于i=1，…，p.确实，如果

u=v1+····+vp=w1+····+wp，

对于vi，wi∈ui，对于i=1，…，p，那么我们有

w1−v1+····+wp−vp=0，

既然vi，wi∈ui，每个ui都是一个子空间，wi−vi∈ui。a的注入性意味着wi-vi=0，也就是说，wi=vi代表i=1，…，p，这表明u的分解是唯一的。

很明显，任何p非零向量u1，…，上到ui∈ui都是线性无关的。为此，假设λ1u1+····+λpup=0

对于某些λi∈r，由于ui∈ui和ui是一个子空间，因此，对于i=1，…，p，a的内射性意味着λiui=0，对于i=1，…，p。由于ui=06，我们必须得到λi=0，对于i=1，…，p；也就是说，u1，…，up with ui∈ui和ui=06是线性无关的。

如果a是注射剂，那么当i=6 j时，我们必须有ui uj=（0）。但是，如果p≥3，这种情况通常是不够的。例如，如果e=r2和u1，用e1=（1,0）表示的线，u2是用d=（1,1）表示的线，u3是用e2=（0,1）表示的线，那么u1 u2=u1 u3=u2（0,0），但是u1+u2=u1+u3=u2+u3=r2，所以u1+u2+u3不是直接和。例如，d用两种不同的方式表示为

d=（1,1）=（1,0）+（0,1）=e1+e2。

定义5.3.对于任意向量空间e和任意p≥2个子空间u1，…，向上到e，如果上面定义的映射a是内射的，则该和u1+·····+向上称为直接和，并用

U1·····向上。空间e是子空间ui的直接和，如果

E=U1····向上。

如求和，u1 u2=u2 u1。观察到当图A为内射时，则为U1×上×上与U1×上的线性同构。区别在于，即使空间ui不被假定为某个公共空间的子空间，也定义了u1×······×up。

如果e是一个直接和e=u1········up，由于任何p非零向量u1，…，up与ui∈ui是线性无关的，如果我们在uj中选取一个基（uk）k∈i j，对于j=1，…，p，那么（ui）i∈i与i=i1·······ip是e的基，直观地，e被分成p独立的子空间。

相反，给定e的基（ui）i∈i，如果我们将索引集i划分为i=i1···ip，则每个子族（uk）k∈ij跨越e的一些子空间uj，并立即证明我们有一个直接和

E=U1····向上。

设f:e→e为线性映射。如果f（uj）uj，我们说uj在f下是不变的，假设e是有限维的，直接和e=u1·································································在f下，每个基向量uk的k∈ij的图像f（uk）都属于uj，因此表示f的矩阵a在基（ui）i∈i上是一个块对角矩阵的形式

，

对于每个块aj，一个dj×dj矩阵，dj=dim（uj），所有其他条目等于0。如果j=1时dj=1，…，p，则矩阵a是对角矩阵。

每个ui到e都有自然注入，由ini:ui→e表示。

现在，如果p=2，很容易确定图a:u1×u2→e的核心，我们有

a（u1，u2）=u1+u2=0 iff u1=−u2，u1∈u1，u2∈u2，

这意味着

kera=（u，−u）u∈u1 u2。

现在，u1 u2是e的一个子空间，线性映射u→7（u，−u）显然是u1 u2和kera之间的同构，所以kera与u1 u2是同构的。因此，我们得到以下结果：

提案5.3.给定任意向量空间e和任意两个子空间u1和u2，和u1+u2是直接和iff u1 u2=（0）。

直接和概念的一个有趣的例子是将一个方阵分解成它的对称部分和它的斜对称部分。回想一下，n×n矩阵a∈mn在a>=a时是对称的，在a>=-a时是斜对称的。

s（n）=a∈mn a>=a和skew（n）=a∈mn a>=-a

是mn的子空间，s（n）skew（n）=（0）。观察任意矩阵a∈mn，矩阵h（a）=（a+a>）/2是对称的，矩阵s（a）=（a−a>）/2是偏对称的。自从

，

我们看到mn=s（n）+skew（n），由于s（n）skew（n）=0，我们得到了直接和

mn=s（n）倾斜（n）。

注：斜对称矩阵的向量空间斜（n）也用so（n）表示。它是群so（n）的李代数。

命题5.3可以以符号为代价推广到任何p≥2个子空间。下列命题的证明留作练习。

提案5.4.给定任意向量空间e和任意p≥2个子空间u1，…，向上，以下属性等效：

*(1)*     u1+········+上的和是直接和。

*(2)*     我们有

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.gif)

*(3)*     我们有

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image004.gif)

因为同构

U1×上×上≈U1×上，

我们有

提案5.5.如果e是任何向量空间，对于任何（有限维）子空间u1，…

在e上，我们有dim（u1·····································

如果e是直接和

E=U1····向上，

因为每个u∈e都可以用一种独特的方式写成

U=U1+·····+向上

对于i=1…，p的ui∈ui，我们可以通过以下方式定义映射πi:e→ui，称为投影：

πi（u）=πi（u1+····+向上）=ui。

很容易检查这些映射是否是线性的并且满足以下属性：

（

πjπi=πi，如果i=6 J

0，如果i=j，

π1+····+πP=ide.

例如，对于直接和

mn=s（n）歪斜（n）

S（n）上的投影由下式给出

，

斜角上的投影（n）由

A−A>π2（A）=S（A）=

二

显然，h（a）+s（a）=a，h（h（a））=h（a），s（s（a））=s（a），h（s（a））=s（h（a））。=

0。

f f=f的函数称为等幂函数。因此，投影πi是等幂的。相反，可以显示以下命题：

提案5.6.设e为向量空间。对于任意p≥2个线性映射fi:e→e，如果

（

fj fi=fi如果i 6=j

0，如果i=j，

f1+····+fp=ide，

如果我们让ui=fi（e），我们有一个直接和

E=U1····向上。

我们也有以下的命题来描述等幂线性映射，它的证明也留作练习。

提案5.7.对于每个向量空间e，如果f:e→e是一个等幂线性映射，即f f=f，那么我们有一个直接和

E=切口国际货币基金组织，

所以f是对其图像的投影，imf。

我们现在给出任意非空指数集i的一个直接和的定义。首先，让我们回忆一下一个族（ei）i∈i的积的概念。给定一个族（ei）i∈i，其积q i ei，是所有函数f:i→si∈i ei的集合，这样，f（i）∈ei，对于每个i∈

i∈i。它是选择公理的众多版本之一，如果ei=6∅对于每一个i∈i，有then qi∈iprojectionei=6∅。成员πi:qi∈i efi∈→qeii∈，定义为，i ei，通常表示为（πi（（fi）fii∈）ii∈）=i。我们现在定义∈i，我们直接求和。

定义5.4.让我是任何非空集，让（ei）i∈i是向量空间的族。家族（ei）i∈i的（外部）直接和'i∈i ei（或副产物）定义如下：

` i∈i ei由有限支持的所有f∈qi∈i ei组成，加乘一个标量定义如下：

（fi）i∈i+（gi）i∈i=（fi+gi）i∈i，λ（fi）i∈i=（λfi）i∈i。

我们也有注入映射ini:ei→'i∈i ei，定义如下，ini（x）=（fi）i∈i，其中fi=x，fj=0，对于所有j∈（i−i）。

下面的命题是5.1命题的一个明显概括。

提案5.8.设我为任意非空集，设‘ei（ei，is a vector space，and for every family）i∈i为向量空间的族，设g为任意向量空间。直接和i∈i

（hi）线性映射的i∈i hi:ei→g，有一个唯一的线性映射

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image006.gif)

这样，（pi∈i hi）ini=hi，对于每一个i∈i。

评论：

(1)    人们可能会想，为什么直接和‘i∈i ei由有限支持的家族而不是任意家族组成；换句话说，为什么我们不把家族的直接和（ei）i∈i定义为qi∈i ei？上面定义的加和标量乘的积空间qi∈i ei也是一个向量空间，但问题是任何线性映射bh:qi∈i ei→g都必须由

eh（（ui）∈i）=xhi（ui），

我爱我

如果我是无限的，那么右边的和是无限的，因此也没有定义！如果我是有限的，那么qi∈i ei和'i∈i ei是同构的。

(2)    当e i=e时，对于所有i∈i，我们用e（i）表示‘i∈i ei’。特别是当ei=k时，对于所有i∈i，我们找到定义3.9的向量空间k（i）。

关于内射或外射线性映射，我们也有以下基本命题。

提案5.9.设e和f为向量空间，设f:e→f为线性映射。如果f:e→f是内射的，那么有一个称为收缩的投影线性映射r:f→e，这样r f=ide。如果f:e→f是主观的，那么有一个内射线性映射s:f→e称为截面，这样f s=idf。

证据。设（ui）i∈i为e的基，由于f:e→f是一个内射线性映射，由命题3.13，（f（ui））i∈i在f中是线性独立的，由定理3.5可知，f中有一个基（vj）j∈j，其中i j，其中vi=f（ui），对于所有i∈i，由命题3.13可以定义一个线性映射r:f→e。式中，r（vi）=ui，对于所有i∈i，r（vj）=w，对于所有j∈（j-i），其中w是e中的任何给定矢量，即w=0。因为r（f（ui））=ui对于所有i∈i，根据3.13号命题，我们得到r f=ide。

现在，假设f:e→f是主观的。设（vj）j∈j为f的基，因为f:e→f是可射的，对于每个vj∈f，都有一些uj∈e，这样f（uj）=vj。由于（vj）j∈j是f的基础，根据命题3.13，有一个唯一的线性映射s:f→e，因此s（vj）=uj。另外，由于f（s（vj））=vj，根据命题3.13（再次），我们必须有f s=idf。

5.9号提案的反面是显而易见的。

我们现在准备证明一个关于线性映射核的秩和维数的非常重要的结果。

## 5.2秩零定理；格拉斯曼关系

我们从以下基本命题开始。

提案5.10.设e，f和g为三个向量空间，f:e→f为一个内射线性映射，g:f→g为一个内射线性映射，并假定imf=kerg。然后，以下属性保持不变。（a）对于任意截面s:g→f of g，我们有f=kerg ims，线性映射f+s:e g→f是同构的。1

（b）对于任何收缩r:f→e of f，我们有f=imf kerr.2

弗格森

O/O/G（O/O/G）

21关于g的s:g→f节的存在，从命题5.9开始。

牵开器r的存在：f的f→e从命题5.9开始。


 

证据。（a）因为s:g→f是g的一部分，我们有g s=idg，并且对于每个u∈f，

G（U−S（G（U）））=G（U）−G（S（G（U）））=G（U）−G（U）=0。

因此，u−ss，然后（g（u））u∈=kers（vg），我们对一些v∈gfause=kergu+∈immss。另一方面，如果，g（u）=0，因为u∈keru g∈，

Kerg im等等，

g（u）=g（s（v））=v=0，

fbecause+s:eg gs=→fidf=g，表示同构。（b）的证明非常相似。Kerg，我们有f=uim=sf（v）=0ims。因此，但是，既然，sincef=kergf和imss，而且既然byare injective，assumption，im

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image007.gif)

F=注意，我们可以选择一个收缩kerg ims=imf ims，f是内射的，所以我们可以设置r:f→e，这样ims上的kerr im0，sinces。

弗格森

给定一个线性mapsf g e−→f−→g的序列，当imf=kerg时，我们认为该序列e−→f−→g在f处是精确的。如果除了在短精确序列上是精确的外，并且这表示为asf，f是内射的。

而G是悲观的，我们说我们有一个

0−→E−F→F−→G−→0。

命题5.10给出的短精确序列的性质通常通过说0−→e−f→f−→g g−→0是（短）分裂的精确序列来描述。

作为5.10号命题的推论，我们得到以下结果。

定理5.11.是线性映射。然后，（秩零定理）Lete与Kerefand imf fbe向量空间同构，并由此，f:e→f

dim（e）=dim（切口）+dim（imf）=dim（切口）+rk（f）。

证据。考虑

克尔

其中kerf−→i是包含图，是与Surjection关联的

f

得到一个−→f之间的同构，然后，我们将命题5.10应用于任意截面IME和切口imf，以及命题5.5，得到dim（f−→e of ef）=0 to dim（kerf）+dim（imf）。

注：线性映射f的核的维数dim（kerf）通常称为f的零。

我们现在用定理5.11得到一些重要的结果。

提案5.12。给定向量空间e，如果u和v是e的任意两个子空间，那么

调光（U）+调光（V）=调光（U+V）+调光（U V）

一个称为格拉斯曼关系的方程。

证据。回想一下，u+v是线性地图的图像

A:U×V→E

由a（u，v）=u+v给出，

我们在前面已经证明了a的kera核与u v核是同构的。根据定理

5.11，

尺寸（u×v）=dim（kera）+dim（ima）

但dim（u×v）=dim（u）+dim（v），dim（kera）=dim（u v），ima=u+v，因此

格拉斯曼关系成立。

格拉斯曼关系对于确定两个子空间在维>3的空间中是否具有非平凡交集是非常有用的。例如，很容易看出，在R5中，有子空间u和v，dim（u）=3，dim（v）=2，这样u v=（0）；例如，让u由向量（0,0,0,0,0,0），（0,1,0,0），（0,0,1,0,0）生成，v由向量（0,0,0,1,0）和（0,0,0,0,1）生成。然而，我们声称如果dim（u）=3和dim（v）=3，那么dim（u v）≥1。事实上，根据格拉斯曼的关系，我们

调光（U）+调光（V）=调光（U+V）+调光（U V）

即

3+3=6=dim（U+V）+dim（U V）

由于u+v是R5的子空间，dim（u+v）≤5，这意味着

6≤5+尺寸（U V）

即1≤dim（U V）。

作为命题5.12的另一个结果，如果u和v是维度n的向量空间中的两个超平面，那么dim（u）=n-1和dim（v）=n-1，读者应该证明

尺寸（U V）≥N−2，

所以，如果u=6v，那么

尺寸（U V）=N-2。

下面是直接从定理5.11得出的直和的特征。

提案5.13.如果u1，…，up是有限维向量空间e的任何子空间，那么dim（u1+······+up）≤dim（u1）+·····+dim（up），

和dim（u1+·····+向上）=dim（u1）+····+dim（向上）

如果统计研究所形成一个直接的总和U1·····向上。

证据。如果我们把定理5.11应用于线性映射

A:U1×······························向上

由a（u1，…，up）=u1+·····+up给出，我们得到

Dim（U1+······+向上）=Dim（U1×·······×向上）−Dim（Kera）

=dim（u1）+·····+dim（up）−dim（kera）

所以不等式如下。由于a是注射剂iff kera=（0），因此uis形成了第二个方程所持的直接和iff。

定理5.11的另一个重要推论是：

提案5.14.设e和f为两个有限维相同的向量空间dim（e）=dim（f）=n。对于每一个线性映射f:e→f，以下属性是等效的：

*(a)*    F是双主语。

*(b)*    F是悲观的。

*(c)*     F是注射剂。

*(d)*    切口=（0）。

证据。显然，（a）意味着（b）。

如果f是主观的，那么imf=f，所以dim（imf）=n。根据定理5.11，

dim（e）=dim（切口）+dim（国际货币基金组织）

由于dim（e）=n和dim（imf）=n，我们得到dim（kerf）=0，这意味着

切口=（0），所以f是内射的（见命题3.12）。这证明（b）意味着（c）。

如果f是内射的，那么根据命题3.12，切口=（0），所以（c）意味着（d）。

最后，假设切口=（0），那么dim（切口）=0和f是内射的（根据命题3.12）。根据定理5.11，

dim（e）=dim（切口）+dim（国际货币基金组织）

因为dim（kerf）=0，我们得到

dim（imf）=dim（e）=dim（f），

证明了F也是主观性的，因此是双主观性的。这证明（d）暗示（a）并结束证明。

我们应该注意到，5.14命题在无限维上失败了。

下面的建议也很有用。

命题5.15.一个同构f:vlet→ewbe一个向量空间。如果在v和w之间，e=u_v和e=u_w，那么

证据。设r为v和w之间的关系，定义如下：

hv，wi∈r iff w−v∈u。

在我们声称v和r w之间，这是一个函数关系，定义了一个线性同构mf（v）=w iff hv，wu r（r是w vf的图形）。如果w f:vv u→andw

−∈v0=v，因此，

wthenw00−w vv 0∈=0−uv，即，则∈ue，且since w=w0−0u=w w∈v。因此，w，对于everyuu−，且既然vv∈ris是一个直接和，uis是泛函的。类似地，如果，andw∈i∈fwis是主观的。我们还需要验证，存在一个唯一的pairw是一个直接和，u v=（0），and u wu and=（0）hu，v wi∈，因此−∈u v 0×∈ffvusis，，

注射。自从

这样w=u+v。

线性的。如果

W−V=U

和w0−v0=u0，

其中u，u0∈u，那么，我们有

（W+W0）−（V+V0）=（U+U0）

式中，u+u0∈u。同样，如果w−v=u

式中u∈u，则我们得到λw−λv=λu，

式中，λu∈u。因此，f是线性的。

假设一个向量空间e和e的任何子空间u，命题5.15表明u的任何子空间余维的维数，我们用codim（v表示，这样e=u u）v表示它。子空间只依赖于余维1的onu称为du。我们称暗

超平面。

线性映射或矩阵的秩是一个重要的概念，无论从理论上还是实践上，它都是线性方程可解性的关键。根据定义3.16，线性映射f:e→f的秩Rk（f）是f的图像子空间imf的维数dim（imf）。

我们有以下简单的建议。

提案5.16。给定线性映射f:e→f，以下属性保持不变：

*(i)*          Rk（f）=codim（切口）。

*(ii)*       Rk（f）+Dim（kerf）=Dim（e）。

*(iii)*     Rk（f）≤min（dim（e），dim（f））。

证据。因为根据5.11，dim（e）=dim（kerf）+dim（imf），根据定义，rk（f）=dim（imf），我们有rk（f）=codim（kerf）。因为Rk（f）=dim（imf），（ii）来自dim（e）=dim（kerf）+dim（imf）。至于（iii），因为imf是f的一个子空间，所以我们有Rk（f）≤dim（f），并且由于Rk（f）+dim（kerf）=dim（e），我们有Rk（f）≤dim（e）。

矩阵的秩定义如下。

定义5.5.在k域上给定m×n矩阵a=（aij），矩阵a的秩Rk（a）是a线性无关列的最大数目（以km为单位视为向量）。

从命题3.6来看，矩阵a的秩是a列生成的km子空间的维数，设e和f为两个向量空间，设（u1，…，un）为e的基，（v1，…，vm）为f的基，设f:e→f为线性映射，设m（f）为其矩阵w.r.t.基（u1，…，un）和（v1，…，vm）。因为f的秩Rk（f）是由（f（u1）、…、f（un））生成的imf的维数，所以f的秩是（f（u1）、…、f（un））中线性无关向量的最大个数，等于m（f）的线性无关列的个数，因为f和km是同构的。因此，对于表示f的每个矩阵，我们有Rk（f）=Rk（m（f））。

稍后我们将看到，利用对偶性，矩阵A的秩也等于A的最大线性无关行数。

如果u是超平面，那么对于维1的某些子空间v，e=u_v。然而，维1的子空间V是由任何非零向量V∈V生成的，因此我们用kv表示v，并写出e=u kv。显然，v/∈u。相反，让x∈e是一个向量，这样x/∈u（因此，x=0）6。我们声称e=u kx。实际上，由于u是一个超平面，对于一些v/∈u（v=0）6，我们有e=u kv。那么，x∈e可以用一种独特的方式写成x=u+λv，其中u∈u，并且由于x/∈u，我们必须有λ=06，因此，v=−λ−1u+λ−1X。由于e=u kv，这表明e=u+kx。由于x/∈u，我们得到u kx=0，因此e=u kx。证明了超平面是E的最大适配子空间H。

在第10章中，我们将看到超平面正是非零线性映射f:e→k（称为线性形式）的核心。

## 5.3总结

本章的主要概念和结果如下：

•     直积、和、直和。

•     预测。

•     基本方程

dim（e）=dim（切口）+dim（imf）=dim（切口）+rk（f）

（提案5.11）。格拉斯曼关系

调暗（U）+调暗（V）=调暗（U+V）+调暗（U V）。

•     双射线性映射f:e→f的特征。

•     矩阵的秩。