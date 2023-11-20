# SQL-Solutions
SQL examples and solutions.The Northwind database was used. The queries were written using PostgreSQL
Questions:
1. Product isimlerini (`ProductName`) ve birim başına miktar (`QuantityPerUnit`) değerlerini almak için sorgu yazın.
2. Ürün Numaralarını (`ProductID`) ve Product isimlerini (`ProductName`) değerlerini almak için sorgu yazın. Artık satılmayan ürünleri (`Discontinued`) filtreleyiniz.
3. Durdurulan Ürün Listesini, Ürün kimliği ve ismi (`ProductID`, `ProductName`) değerleriyle almak için bir sorgu yazın.
4. Ürünlerin maliyeti 20'dan az olan Ürün listesini (`ProductID`, `ProductName`, `UnitPrice`) almak için bir sorgu yazın.
5. Ürünlerin maliyetinin 15 ile 25 arasında olduğu Ürün listesini (`ProductID`, `ProductName`, `UnitPrice`) almak için bir sorgu yazın.
6. Ürün listesinin (`ProductName`, `UnitsOnOrder`, `UnitsInStock`) stoğun siparişteki miktardan az olduğunu almak için bir sorgu yazın.
7. İsmi `a` ile başlayan ürünleri listeleyeniz.
8. İsmi `i` ile biten ürünleri listeleyeniz.
9. Ürün birim fiyatlarına %18’lik KDV ekleyerek listesini almak (ProductName, UnitPrice, UnitPriceKDV) için bir sorgu yazın.
10. Fiyatı 30 dan büyük kaç ürün var?
11. Ürünlerin adını tamamen küçültüp fiyat sırasına göre tersten listele.
12. Çalışanların ad ve soyadlarını yanyana gelecek şekilde yazdır.
13. Region alanı NULL olan kaç tedarikçim var?
14. a.Null olmayanlar?
15. Ürün adlarının hepsinin soluna TR koy ve büyültüp olarak ekrana yazdır.
16. Fiyatı 20den küçük ürünlerin adının başına TR ekleyip listele.
17. En pahalı ürün listesini (`ProductName` , `UnitPrice`) almak için bir sorgu yazın.
18. En pahalı on ürünün Ürün listesini (`ProductName` , `UnitPrice`) almak için bir sorgu yazın.
19. Ürünlerin ortalama fiyatının üzerindeki Ürün listesini (`ProductName` , `UnitPrice`) almak için bir sorgu yazın.
20. Stokta olan ürünler satıldığında elde edilen miktar ne kadardır.
21. Mevcut ve Durdurulan ürünlerin sayılarını almak için bir sorgu yazın.
22. Ürünleri kategori isimleriyle birlikte almak için bir sorgu yazın.
23. Ürünlerin kategorilerine göre fiyat ortalamasını almak için bir sorgu yazın.
24. En pahalı ürünümün adı, fiyatı ve kategorisin adı nedir?
25. En çok satılan ürününün adı, kategorisinin adı ve tedarikçisinin adı?
26. Stokta bulunmayan ürünlerin ürün listesiyle birlikte tedarikçilerin ismi ve iletişim numarasını (`ProductID`, `ProductName`, `CompanyName`, `Phone`) almak için bir sorgu yazın.
27. 1998 yılı mart ayındaki siparişlerimin adresi, siparişi alan çalışanın adı, çalışanın soyadı
28. 1997 yılı şubat ayında kaç siparişim var?
29. London şehrinden 1998 yılında kaç siparişim var?
30. 1997 yılında sipariş veren müşterilerimin contactname ve telefon numarası
31. Taşıma ücreti 40 üzeri olan siparişlerim
32. Taşıma ücreti 40 ve üzeri olan siparişlerimin şehri, müşterisinin adı
33. 1997 yılında verilen siparişlerin tarihi, şehri, çalışan adı -soyadı ( ad soyad birleşik olacak ve büyük harf),
34. 1997 yılında sipariş veren müşterilerin contactname i, ve telefon numaraları ( telefon formatı 2223322 gibi olmalı )
35. Sipariş tarihi, müşteri contact name, çalışan ad, çalışan soyad
36. Geciken siparişlerim?
37. Geciken siparişlerimin tarihi, müşterisinin adı
38. 10248 nolu siparişte satılan ürünlerin adı, kategorisinin adı, adedi
39. 10248 nolu siparişin ürünlerinin adı , tedarikçi adı
40. 3 numaralı ID ye sahip çalışanın 1997 yılında sattığı ürünlerin adı ve adeti
41. 1997 yılında bir defasinda en çok satış yapan çalışanımın ID,Ad soyad
42. 1997 yılında en çok satış yapan çalışanımın ID,Ad soyad ****
43. En pahalı ürünümün adı,fiyatı ve kategorisin adı nedir?
44. Siparişi alan personelin adı,soyadı, sipariş tarihi, sipariş ID. Sıralama sipariş tarihine göre
45. SON 5 siparişimin ortalama fiyatı ve orderid nedir?
46. Ocak ayında satılan ürünlerimin adı ve kategorisinin adı ve toplam satış miktarı nedir?
47. Ortalama satış miktarımın üzerindeki satışlarım nelerdir?
48. En çok satılan ürünümün(adet bazında) adı, kategorisinin adı ve tedarikçisinin adı
49. Kaç ülkeden müşterim var
50. 3 numaralı ID ye sahip çalışan (employee) son Ocak ayından BUGÜNE toplamda ne kadarlık ürün sattı?
51. 10 numaralı ID ye sahip ürünümden son 3 ayda ne kadarlık ciro sağladım?
52. Hangi çalışan şimdiye kadar toplam kaç sipariş almış..?
53. 91 müşterim var. Sadece 89’u sipariş vermiş. Sipariş vermeyen 2 kişiyi bulun
54. Brazil’de bulunan müşterilerin Şirket Adı, TemsilciAdi, Adres, Şehir, Ülke bilgileri
55. Brezilya’da olmayan müşteriler
56. Ülkesi (Country) YA Spain, Ya France, Ya da Germany olan müşteriler
57. Faks numarasını bilmediğim müşteriler
58. Londra’da ya da Paris’de bulunan müşterilerim
59. Hem Mexico D.F’da ikamet eden HEM DE ContactTitle bilgisi ‘owner’ olan müşteriler
60. C ile başlayan ürünlerimin isimleri ve fiyatları
61. Adı (FirstName) ‘A’ harfiyle başlayan çalışanların (Employees); Ad, Soyad ve Doğum Tarihleri
62. İsminde ‘RESTAURANT’ geçen müşterilerimin şirket adları
63. 50$ ile 100$ arasında bulunan tüm ürünlerin adları ve fiyatları
64. 1 temmuz 1996 ile 31 Aralık 1996 tarihleri arasındaki siparişlerin (Orders), SiparişID (OrderID) ve SiparişTarihi (OrderDate) bilgileri
65. Ülkesi (Country) YA Spain, Ya France, Ya da Germany olan müşteriler
66. Faks numarasını bilmediğim müşteriler
67. Müşterilerimi ülkeye göre sıralıyorum:
68. Ürünlerimi en pahalıdan en ucuza doğru sıralama, sonuç olarak ürün adı ve fiyatını istiyoruz
69. Ürünlerimi en pahalıdan en ucuza doğru sıralasın, ama stoklarını küçükten-büyüğe doğru göstersin sonuç olarak ürün adı ve fiyatını istiyoruz
70. 1 Numaralı kategoride kaç ürün vardır..?
71. Kaç farklı ülkeye ihracat yapıyorum..?
