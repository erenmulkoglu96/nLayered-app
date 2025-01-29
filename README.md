Katmanlı mimarileri öğrenmek için geliştirdiğim bir Windows Forms uygulaması. Bu uygulamada, Northwind veritabanında bulunan Products ve Categories tablosundaki ürünler ile ilgili Entity Framework yardımıyla ekleme, listeleme, güncelleme, silme işlemleri yapılabilmekte. Uygulamada ayrıca bağımlı nesneleri kontrol etmek adına Ninject kütüphanesi, doğrulama işlemlerini kontrol etmek adına ise FluentValidation kütüphanesi kullanılmıştır. 

(A Windows Forms application I developed to learn layered architectures. In this application, adding, listing, updating and deleting operations can be performed on the products in the Products and Categories table in the Northwind database with the help of Entity Framework. In the application, the Ninject library was used to control dependent objects and the FluentValidation library was used to control validation processes.)


Insallation & Usage (Kurulum ve Kullanım)

Northwind veritabanına <a href="https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs">buradan</a> ulaşabilirsiniz.
Entity Framework paketi NuGet Paket Yöneticisi aracılığıyla Northwind.DataAccess ve Northwind.WebFormsUI katmanlarına eklendi. <br />
FluentValidation paketi Nuget Paket Yöneticisiyle Northwind.Business katmanına eklendi.<br />
Ninject paketi NuGet Paket Yöneticisi aracılığıyla Northwind.Business ve Northwind.WebFormsUI katmanlarına eklendi.<br />
Northwind.WebFormsUI başlangıç ​​projesi olarak ayarlayın.

![image](https://github.com/user-attachments/assets/5368467b-245e-4d8d-a1e3-c0532d3ddf67)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

Eğitim için Engin Demiroğ'a saygılar, sevgiler.
