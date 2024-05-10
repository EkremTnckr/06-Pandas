# 06-Pandas
Pandas serisi, herhangi bir türdeki (tamsayı, dize, float, python nesneleri, vb.) verileri tutabilen tek boyutlu e􀆟ketli bir dizidir. DataFrames'i tam olarak anlamak için serilerin temellerini bilmeniz gerekir. Pandas serisini bir excel sayfasındaki e􀆟ketli bir sütun olarak düşünebilirsiniz.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/bf45a85c-32a2-4801-9eeb-21bc4f6185eb)
Pandas serisi, herhangi bir türdeki (tamsayı, dize, float, python nesneleri, vb.) verileri tutabilen tek boyutlu e􀆟ketli bir dizidir. DataFrames'i tam olarak anlamak için serilerin temellerini bilmeniz gerekir. Pandas serisini bir excel sayfasındaki e􀆟ketli bir sütun olarak düşünebilirsiniz.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/9096e065-cc91-4d20-976b-1dc49e26840d)
Bir seride, eksen e􀆟ketleri indeks olarak adlandırılır. Seriler yalnızca indeksli tek bir liste içerebilirken, DataFrames birden fazla seriden oluşabilir.
Data Frame Basics-1 (Attributes)
DataFrame, verilerin satırlar ve sütunlar halinde hizalandığı iki boyutlu bir veri yapısıdır. Üç temel bileşen; veriler, satırlar ve sütunlar Pandas DataFrame'i oluşturur.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/97c0e94e-96e3-43d2-8502-ae109d81c225)
DataFrame(): İki boyutlu, boyutu değiştirilebilir, potansiyel olarak heterojen tablo verileri. Veri yapısı ayrıca etiketli eksenler (satırlar ve sütunlar) içerir. Birincil pandas veri yapısı
Series(): Eksen etiketleri içeren tek boyutlu ndarray (zaman serileri dahil).
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/d65484a8-595c-459c-99fb-ffa0415ba6ca)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/1248fd39-6d8f-49c2-82e5-72910518e20e)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/4d08f8b6-95bd-4f56-bf17-6e8848c35c68)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/2199466a-46be-46c8-a3f0-82272dfd7240)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/7baf9c0b-af20-401f-8e1a-c052a5150650)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/96bbbd17-dca2-4d15-bec3-8991df7e77bf)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/41952293-d69a-4883-bec8-d1b9e03e1f5c)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/89cc1b05-11d6-4233-b033-f2a8840743f7)
Data Frame Basics-2 (Index & Selecting)
Veri Çerçevesi Temelleri-2 (Dizin ve Seçme)
DataFrame, verilerin satırlar ve sütunlar halinde hizalandığı iki boyutlu bir veri yapısıdır. Üç temel bileşen; veriler, satırlar ve sütunlar Pandas DataFrame'i oluşturur.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/84e5c32b-edfb-45d2-95bd-29e72aec84c8)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/3f31b873-77a6-4c94-b89a-bae8f6f64fd4)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/16de8bfc-9169-49b6-80f0-827dab4d6522)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/28522945-2d12-46af-9eef-e76ab56bcb49)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/e1b74515-15a4-46fd-a24d-1cd9b1583c1b)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/36b6ea18-fe6d-4772-9eee-efb4234ab625)
Data Frame Basics-3 (Properties)
Veri Çerçevesi Temelleri-3 (Özellikler)
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/309fd3c9-7776-494e-a354-b7433db553d4)
df.info(): Bu yöntem, dizin türü ve sütunları, boş olmayan değerler ve bellek kullanımı dahil olmak üzere bir DataFrame hakkında bilgi yazdırır
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/364eb836-5c3f-4079-b1d0-4e8ad35b2c27)
df.describe(): NaN değerleri hariç olmak üzere, bir veri kümesinin dağılımının merkezi eğilimini, dağılımını ve şeklini özetleyenleri içeren tanımlayıcı ista􀆟s􀆟kler oluşturun
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/cc1da714-505a-4223-a089-636fce41d3e3)
df.shape: DataFrame'in boyutluluğunu temsil eden bir tuple döndürür.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/51430797-26c1-4a14-9e2d-e503d4e047fa)
len(df): Bir dizenin uzunluğunu (karakter sayısını) verir. Sözlükler, listeler veya tuple'lar için girdi sayısını verir.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/ccff080f-21f8-49b0-ae21-1b8ba6b008b3)
df.col.value_counts(): Benzersiz değerlerin sayılarını içeren bir Seri döndürür
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/cdcd0658-4b83-4264-bc9d-90385b5317aa)
df.mean(): İstenen eksen üzerindeki değerlerin ortalamasını döndürür.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/ea12f66a-606f-4e20-a146-9750c300f647)
df.col.sum(): İstenen eksen üzerindeki değerlerin toplamını döndürür.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/bc135d10-d5b1-4504-b858-644da995ec21)
df.col.unique(): Karma tablo tabanlı benzersiz. Benzersizler görünüm sırasına göre döndürülür. Bu sıralama yapmaz
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/4b796f07-38f4-4ef6-903b-61cf1b74b891)
df.isnull().sum(): Eksik değerleri tespit edin. Her sütundaki eksik değerlerin toplam sayısını döndürür.
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/fd14745b-338d-43bd-bd63-f9fee04f87d5)
df.drop():E􀆟ket adlarını ve ilgili ekseni belirterek veya doğrudan dizin veya sütun adlarını belirterek sa􀆨rları veya sütunları kaldırın
![image](https://github.com/EkremTnckr/06-Pandas/assets/118742142/b5cd1d5e-37dc-4526-be2c-15efcad45595)










