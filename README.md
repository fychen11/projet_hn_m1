## Projet
Il s'agit d'un repository sur le mémoire du master HN 22-24: Le sacrifice des animaux à Yinxu (Dynastie Shang)

## Données
- les inscriptions sur os et carapace sont tirées de la base de donnée [殷契文渊](http://jgw.aynu.edu.cn/ajaxpage/home2.0/index.html)  
à l'aide du script [SearchByText](https://github.com/zhituaner/YinQiWenYuan) avec modifications apportées :
 ```
 Data = [item for item in Data if not item["BoneID"]=='']  #supprimer les éléments qui ont un BoneID vide afin d'appliquer correctement la fonction SplitBoneID(Dict)
 gxdsURL=f'http://www.guoxuedashi.net/jgwhj/?bh={numID}&bhfl={bhfl}'  #nouveau URL du 国学大师 pour extraire les transcriptions
 ```
Liste des animaux et mots clés  
* __羊__ 837
* __豕__ 633
* __犬__ 568  
* __牛__ 396
* __鹿__ 363
* __马__ 240
* __彘__ 198
* __虎__ 178
* __狐__ 107
* __雉__ 79
* __鱼__ 66
* __象__ 46
* __鸟__ 41
* __鸡__ 23
* __豹__ 19  
* __麇__ 18
* __熊__ 1

Autres animaux :
* __兔__ 32
* __獐__ 4
* __猴__ 2
* __猱__ 2
* __猫__ 1


- les ossements du site archéologique  
[CASS](http://kaogu.cssn.cn/zwb/xszl/kgsjk/) : [殷墟54号墓动物骨骼数据库](http://kaogu.cssn.cn/zwb/xszl/kgsjk/dwkgzlk/200904/t20090429_3915550.shtml)

- le dataset des estampages  
[甲骨文字检测数据集](http://jgw.aynu.edu.cn/DownPage)
