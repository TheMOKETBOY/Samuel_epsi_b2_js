**Rapport Objection Samuel**

Dans objection on peut rechercher les différentes Classes de l'application grâce à la commande : `android hooking seach classes com.viaforensics.andoid`

![searchClasses](https://user-images.githubusercontent.com/30469939/77367671-f437c000-6d5a-11ea-97c8-8b633563901a.PNG)

Nous avons les 20 Classes de l'application. A partir de ses classes nous pouvons affiner nos recherche. 

La commande : `android hooking list classes_methods com.viaforensics.andoid.ForensicsActivity`

Cela nous permet de lister toutes les méthodes de la Classes ForensicsAcitivty

![class_methods](https://user-images.githubusercontent.com/30469939/77368314-3dd4da80-6d5c-11ea-8a9a-7a94e9141717.PNG)

A partir de cela on peut réaliser un : 

`android hooking watch class_method com.viaforensics.android.ForrensicsActivity.capture --deumps-args --dump-backtrace --dump-return`

On peut avoir toute les méthode utilisé par le bouton capture dans on l'utilise

![backtrace](https://user-images.githubusercontent.com/30469939/77368865-7c1ec980-6d5d-11ea-8598-e778b199a062.PNG)
