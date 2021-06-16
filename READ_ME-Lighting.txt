https://www.youtube.com/watch?v=_E0JXOZDTKA
---------------------------------------------------
Light Probes
---------------------------------------------------
1-Simdi bir sahneyi bake edince Unity bir LightMap cikario. Bu bir texture sahneye ait  ve sahnenin ustüne yansitilio.Light Probe da bu islemden sonra oraya koydgmuzda bu lightmapten yola cikarak bu datayi saklio.

2- SImdi bizdki sikinti su . Universal Pipleine kullandgmz icin baska bir skeilde bu isi halletmek gerekio. Valla zor oldgnu dusunuorm o sebeple baska proje aciorm.

3- baska bir yerde sahneyi ayarladm. Lightning sekmesine gelioz.Windows>Rendering>Lighting
Lighting Settings var bir tane o profil gbi anladm ben yeni bir tane actm ama emin deglm devam en sagda baked Lightmaps var sec abi onu. Butun bakelenecek objeleri sec static yap sonra burda generate Lighting de.Biraz sürüo ama güzel bir isiklandrma cikio.

4-karsdialstrma lsun diye yanyana da koyduk resim de aldik fark var simdi gelelim asil kisma light probe.

5- su an beyaz bir objeyi gzdrsem de randiman alamiom. cunku coktan bake edildiler.

6- Abi sonrasi cok entresan. light Problerai koyuyosn. bunlar kesinlikle sahnede bir yere degmemeli. Bend de deigiodu bilerek öyle biraktm. Bozulmalar cikio. 

7- meshleri seciosn ve lightning de light probeslari sec

8- Baktin oluo tekrar generate et.

9_ burasi oldukca ileri bir mevzu onu anladim.kapali alan videosuna bakarm sonra ama smdlik bu kisim hem guclu pc istio hem de ielri seviye s.et

------------------------------------------------------
Kapali alan
-------------------------------------------------------
ya da s.et simdilik gerek yok gercekten

Ertesi gin sabahtan bunla ugrastik.
bilinmesi gerekn seylerden biri su bu is cok pc gücü istio. Kratoslu sahne 20 dk da bake oldu. Buyuk ihtimal bir siniri astgim icin ok fazla bozulma yasandi. edeninin bilmiorm.


ikinci olarak bizim bu isiklandirmalar real time degil ne demek bu. Biz sahneyi static objelerle süsleyip bake ediorz. Bunun sponucunda bir isik haritasi cikio. Bu objelere emission materyaller koydgmuz icin, lightmap sadece bunlarin isigini kullaanio. Ama daha sonra o nesneleri ordan ceksek de map degismio. realtime olmadigi icin harita degtirilemez konuma gelio. Stabl sahneelr icin ideal ama gercek bit oyunda böyle olmaz elbet.

Ne yapiorz peki. Kisaca 
1- nesneler static, static olmayanlar werden  nicht berücj´ksichtigt.
2- Emission materyeller, haaa intensity artarsa isik gücü de artar 1 falan iyi o  anlamda
3- Window>Rendering>Lighting
4- Yeni isik ayari sec, burda bir sürü ayar var resolution, intensity size vesaire. Bunlari simdilik pas gectim ama önemliler. 
5- en sagda baked lightmaps var. Burda su an birsey yok niye? cunku birsey bake etmedik. asagida genrate diorz. Auto kapali olsun.
6- biraz bekleyince sonuc ortada.
7-tekrar bake etmek istersen öncekini silecen.
8- Ekstra ayarlar gercekten yorucu ve komplex bence bu akdr yeter.