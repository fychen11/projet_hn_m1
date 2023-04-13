##Source
Les inscriptions sur os et carapace sont tirées de la base de donnée [殷契文渊](http://jgw.aynu.edu.cn/ajaxpage/home2.0/index.html)  
à l'aide du script [SearchByText](https://github.com/zhituaner/YinQiWenYuan) avec modifications apportées :
 ```
 Data = [item for item in Data if not item["BoneID"]=='']  #supprimer les éléments qui ont un BoneID vide afin d'appliquer correctement la fonction SplitBoneID(Dict)
 gxdsURL=f'http://www.guoxuedashi.net/jgwhj/?bh={numID}&bhfl={bhfl}'  #nouveau URL du 国学大师 pour extraire les transcriptions
 ```
 
##Liste des animaux et mots clés
__犬__ 568
__鹿__ 366
__彘__ 198
__鸡__ 23
__豹__ 19

###Autres animaux sans inscriptions
豸
