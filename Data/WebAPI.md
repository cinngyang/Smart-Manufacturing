#### Representational State Transfer -  Web API

***

最近被前端的技術搞得暈頭轉向的，架構與運用以及平台。有時候很多事情存在兩難，現有的包袱，人員慣用技術與舊有系統維護。日後維運成本。畢竟 MS 平台下整題的成本升高。

+ Web API VS Web Service
+ PWA 
+  

REST指的是網路中Client端和Server端的一種呼叫服務形式， 對資源的操作包括獲取、創建、修改和刪除資源,這些操作就是 HTTP Method: GET、POST、PUT、PATCH和DELETE。這正好會對應到資料庫基本操作CRUD。**CRUD 為 Create(新增)、Read(讀取)、Update(更新)與Delete(刪除)**, 與 Web Service 的差異在於可以修改資料

Http Method

- GET：取得(想要的服務)的資料或是狀態。（safe & idempotent）
- POST：新增一項資料。
- PUT：利用更新的方式於"指定位置"新增一項資料。 （idempotent）
- PATCH：在現有的資料欄位中，增加或部分更新一筆新的資料。
- DELETE：指定資料刪除。 （idempotent）

使用時機

有數組資源要被多種不同平台使用時，例如，Android/ iOS / Web 要對同一 table 做存取

Reference<br>[How to Use RESTful APIs with Django](https://simpleisbetterthancomplex.com/tutorial/2018/02/03/how-to-use-restful-apis-with-django.html)<br>[Django REST framework](http://www.django-rest-framework.org/)<br>[RESTful 的Web API是現在的潮流](https://progressbar.tw/posts/53)<br>[從無到有打造 RESTful API service](https://ithelp.ithome.com.tw/users/20091343/ironman/762) <br>

