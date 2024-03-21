# Proje Ödevi
## Bu Ödevde;
#### Bir yazılım dili olan C# öğreniyorum. Öğrenmek için ise hocamın bana verdiği 8 tane uygulama var.Onları yapıyorum.
## Ödevler şu şekilde:
#### öved_1 Kullanıcıdan iki sayı ve bir işlem (+, -, x, /) isteyen ve ardından işlemi hesaplayıp
sonucu ekrana yazan bir C# programı yazınız. Eğer işlem sembolü önceki
sembollerden farklıysa, "Tanınmayan karakter" metnini gösteriniz.
• Bu durumu if bloğunu kullanarak gerçekleştiriniz.
  Console.WriteLine("birinci sayı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("ikinci sayı girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
  
  Console.WriteLine("hangi işlemi yapmak istersiniz:\n toplam= 1\n çıkarma= 2\n çarpma= 3\n bölme= 4 ");
  int process = Convert.ToInt32(Console.ReadLine());
  
  int total= (s1+s2);
  int minus = (s1-s2);
  int impact = (s1*s2);
  int divide = (s1/s2); 
  if (process==1)
  {
      Console.WriteLine("girdiğiniz sayıların toplamı:"+total);
  }
  else if (process==2)
  {
      Console.WriteLine("girdiğiniz sayıların çıkması:"+minus);
  }
  else if (process==3)
  {
      Console.WriteLine("girdiğiniz sayıların çarpımı:"+impact);
  }
  else if (process==4)
  {
      Console.WriteLine("girdiğiniz sayıların bölmü:"+divide);
  }
  else 
  {
      Console.WriteLine("lütfen geçerli bir işlem giriniz");
  }
  #### ödev_2 Kullanıcıdan iki sayı ve bir işlem (+, -, x, /) sembolü isteyen ve ardından işlem<
hesaplayıp sonucu ekrana yazan bir C# programı yazınız.Eğer işlem sembolü
önceki sembollerden farklıysa, "Tanınmayan karakter" metnini göster<n<z.
• Bu durumu switch bloğunu kullanarak gerçekleştiriniz.
  Console.WriteLine("birinci sayı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("ikinci sayı girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
  
  Console.WriteLine("hangi işlemi yapmak istersiniz:\n toplam= 1\n çıkarma= 2\n çarpma= 3\n bölme= 4 ");
  int process = Convert.ToInt32(Console.ReadLine());
  
  int total= (s1+s2);
  int minus = (s1-s2);
  int impact = (s1*s2);
  int divide = (s1/s2); 
  
  switch (process)
  {
      case 1:
          Console.WriteLine("girdiğiniz sayıların toplamı:"+total);
          break;
      case 2:
          Console.WriteLine("girdiğiniz sayıların çıkması:"+minus);
          break;
      case 3:
          Console.WriteLine("girdiğiniz sayıların çarpımı:"+impact);
          break;
      case 4:
          Console.WriteLine("girdiğiniz sayıların bölmü:"+divide);
          break;
      default:
          Console.WriteLine("lütfen geçerli bir işlem giriniz");
          break;
  }
#### ödev_3 Bir sayı (x) <steyen ve bu sayının pozitif mi yoksa negatif mi olduğunu yanıtlayan
bir C# programı yazın.
  Console.WriteLine("bir sayı girin: ");
  int s1 = Convert.ToInt32(Console.ReadLine());
  if (s1 < 0)
  {
      Console.WriteLine(s1 + "sayısı negatifdir");
  }
  else if (s1 > 0)
  {
      Console.WriteLine(s1 +" " +"sayısı pozitifdir");
  }
#### ödev_4 C# dilinde üç sayıyı (x, y, z) isteyen ve en büyüğünü görüntüleyen bir program
yazın.
  Console.WriteLine("birinci sayı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("ikinci sayı girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("üçüncü sayıyı girin:");
  int s3 = Convert.ToInt32(Console.ReadLine());
  
  if (s1 > s2 && s1> s3)
  {
      Console.WriteLine("girdiğiniz sayılardan en büyük olanı sayı"+" "+s1);
  }
  else if (s2> s1 && s2> s3)
  {
      Console.WriteLine("girdiğiniz sayılardan en büyük olanı sayı"+" "+s2);
  }
  else if (s3> s1 && s3> s2)
  {
      Console.WriteLine("girdiğiniz sayılardan en büyük olanı sayı "+" "+s3);
  }
#### ödev_5 C#'ta bir sayı (x) isteyen ve 10 * x'i görüntüleyen bir program oluşturun. Kullanıcı 0
girene kadar tekrarlanmalıdır.
  while (true)
  {
  Console.WriteLine("birinci sayı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  int çarpam =(s1 * 10);
  Console.WriteLine(çarpam);
  if (s1 == 0)
  {
      break;
  }
  
  }
#### ödev_6 Kullanıcıdan bir dizi sayı (x, y) talep eden ve bunları ekranda görüntüleyen bir C#
programı oluşturun.
  Console.WriteLine("birinci sayı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("ikinci sayı girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
  while (s1 <= s2)
  {
      Console.WriteLine(s1++);
      
  }
#### ödev_7 C# dilinde sayı isteyen ve toplamlarını gösteren bir program yazın. Kullanıcı 0
girene kadar numara isteyin ve program bittiğinde Bitti gösterilir.
  int toplam= 0 ;
  while (true)
  {
      Console.WriteLine("sayı girin:");
      int sayı1 = Convert.ToInt32(Console.ReadLine());
      toplam += sayı1;
      if (sayı1 == 0)
      {
          Console.WriteLine(toplam);
          break;
      }
      else 
      {
      Console.WriteLine(toplam);
      }
  }
#### ödev_8 Kullanıcıdan 5 tam sayı isteyen ve aşağıdaki matematiksel istatistikleri ekranda
görüntüleyen bir C# programı oluşturun:
- 5 sayının toplamı
- Aritmetik ortalama
- Maksimum sayı
- minimum sayı
  Console.WriteLine("1. sayıyı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("2. sayıyı girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("3. sayıyı girin:");
  int s3 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("4. sayıyı girin:");
  int s4 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("5. sayıyı girin:");
  int s5 = Convert.ToInt32(Console.ReadLine());
  int toplam = (s1 + s2 + s3 + s4 + s5);
  Console.WriteLine("girdiğiniz sayıların toplamı:"+toplam);
  int ortalama = (s1 + s2 + s3 + s4 + s5)/5;
  Console.WriteLine("girdiğiniz sayıların ortalaması:"+ortalama);
  
  int max = s1;
  int min = s1;
  if (s1 > s2 && s1 > s3 && s1 > s4 && s1 > s5)
  {
      max = s1 ;
  }
  else if (s2 > s1 && s2 > s3 && s2 > s4 && s2 > s5)
  {
      max = s2;
  }
  else if (s3 > s1 && s3 > s2 &&  s3 > s4 && s3 > s5)
  
  {
      max = s3;
  }
  
  else if (s4 > s1 && s4 > s2 && s4 > s3 && s4 > s5)
  {
      max = s4;
  }
  else if (s5 > s1 && s5 > s2 && s5 > s3 && s5 > s4)
  
  {
      max = s5;
  }
  if (s1 < s2 && s1 < s3 && s1 < s4 && s1 < s5)
  
  {
      min = s1;
  }
  else if (s2 < s1 && s2 < s3 && s2 < s4 && s2 < s5)
  
  {
      min = s2;
  }
  
  else if (s3 < s1 && s3 < s2 && s3 < s4 && s3 < s5)
  
  {
      min = s3;
  }
  
  else if (s4 < s1 && s4 < s2 && s4 < s3 && s4 < s5)
  
  {
      min = s4;
  }
  
  else if (s5 < s1 && s5 < s2 && s5 < s3 && s5 < s4)
  
  {
      min = s5;
  }
  
  Console.WriteLine("girdiğiniz sayıların en büyük sayı:"+max);
  
  Console.WriteLine("girdiğiniz sayıların en küçük sayı:"+min);
#### ödev_9 C# dilinde bir sayı (x) ve bir miktar (y) isteyen bir program yazın. Bu sayıyı miktarın (y) katı
kadar gösterin.
  Console.WriteLine("x sayısını girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  Console.WriteLine("y miktarını  girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
      for (int j = 1; j <= s2; j++)
  {
      Console.Write(s1);
  }
#### ödev_10 1'den 500'e kadar 3'ün ve 5'in katları olan sayıları gösteren bir C# programı oluşturun.
  int x = 0;
  while(x < 500)
  { 
      Console.WriteLine(x);
      x+=15;
  }
#### ödev_11 C# dilinde kullanıcıdan kullanıcı adı ve şifre isteyen bir erişim kontrolü yazın. Her ikisi de
tamsayı olmalıdır ve giriş 12 ve şifre 1234 olduğunda "giriş başarılı yazmalı" yanlışsa ve
en fazla 3 deneme yapana kadar tekrarlanmalıdır.
Kullanıcı adı ve şifre doğruysa Giriş başarılı mesajını gösterir, aksi halde Giriş başarısız
mesajını gösterir.
  int deneme_hakkı =3;
  while (true )
  {
      if (deneme_hakkı == 0){
         Console.WriteLine("hakkınızz bitti :");
          break;
      }
      else 
      {
      Console.WriteLine("giriş yapınız : ");
      int giriş = Convert.ToInt32(Console.ReadLine());
  
      Console.WriteLine("şifre giriniz : ");
      int şifre = Convert.ToInt32(Console.ReadLine());
  
      if (giriş == 12 && şifre == 1234)
      {
          Console.WriteLine("giriş başarılı ");
          break;
      }
      else
      {
          Console.WriteLine("giriş başarısız");
          deneme_hakkı--;
      }
      }
  }
#### ödev_12 C# dilinde kullanıcıdan iki sayı isteyen ve bölme işlemi ile bölmenin geri kalanını
gösteren bir program yazın. İkinci sayı olarak 0 girilirse kullanıcıya bildirim yapın ve ilk
sayı olarak 0 girilirse programı sonlandırın.
  while (true)
  {
  Console.WriteLine("1. sayıyı girin:");
  int s1 = Convert.ToInt32(Console.ReadLine());
  
  Console.WriteLine("2. sayıyı girin:");
  int s2 = Convert.ToInt32(Console.ReadLine());
  
  if (s1 == 0)
  {
      break;
  }
  
   else if (s2 == 0)
  {
      Console.WriteLine("sıfır ile sayı bölünmez");
     
  }
  else{
  int işlem = s1 /s2;
  Console.WriteLine("sayıların bölülü:"+işlem);
  
  int kalan = s1 % s2;
  Console.WriteLine("kalan:"+kalan);}
  }
#### ödev_13 Kullanıcıdan bir sayı aralığı (x, y) isteyen ve x'ten y'ye kadar çarpım tablosunu
görüntüleyen bir C# programı oluşturun.
  Console.WriteLine("Bir X Sayısı Giriniz");
   int x = Convert.ToInt32(Console.ReadLine());
  
   Console.WriteLine("Bir Y Sayısı Giriniz");
   int y = Convert.ToInt32(Console.ReadLine());
    
  for (int i = x; i <= y; i++)
  {
   Console.WriteLine($"Çarpım tablosu {i} için:");
  for (int j = 1; j <= 10; j++)
    {
   Console.WriteLine($"{i} x {j} = {i * j}");
  }
  Console.WriteLine();
      }
  
      Console.ReadLine();*/
#### ödev_14 Bir öğrenc<n<n notunu bir tamsayıdan hesaplayan bir C# programı oluşturun.
Kullanıcıdan bir sayı (x) isteyin ve aşağıdakileri yanıtlayın:
- 10 - A+
- 9 - A
- 7,8 - B
- 6 - C
- 5 - E
- 0,4 - F
- C# dilinde switch, break ve default komutlarını kullanın.
  Console.WriteLine("notu giriniz: ");
  int sayı = Convert.ToInt32(Console.ReadLine());
  switch (sayı)
  {
      case 10: 
          Console.WriteLine("A+"); 
          break;
      case 9: 
          Console.WriteLine("A"); 
          break;
      case 8:
          Console.WriteLine("B+");
          break;
      case 7: 
          Console.WriteLine("B"); 
          break;
      case 6: 
          Console.WriteLine("C"); 
          break;
      case 5: 
          Console.WriteLine("E"); 
          break;
      case 4: 
          Console.WriteLine("F"); 
          break;
      case 3: 
          Console.WriteLine("F"); 
          break;
      case 2: 
          Console.WriteLine("F"); 
          break;
      case 1: 
          Console.WriteLine("F"); 
          break;
      case 0: 
          Console.WriteLine("F"); 
          break;
      default: 
          Console.WriteLine("böyle bir not yok"); 
          break;
  
  }
#### ödev_15 Kullanıcıdan iki tamsayı (x, y) isteyen ve bu sayıların aralığını (iki sayı da dahil olmak
üzere) üç farklı yöntemle gösteren bir C# programı oluşturun:
- for döngüsünü kullanarak.
- while döngüsünü kullanarak.
- do while talimatını kullanarak.
Console.WriteLine("1. sayıyı girin:");
int s1 = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("2. sayıyı girin:");
int s2 = Convert.ToInt32(Console.ReadLine());
for (int i = 1; s1 <= s2; i++)
{
Console.Write(s1 ++);
}*/
/*madde2
Console.WriteLine("1. sayıyı girin:");
int s1 = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("2. sayıyı girin:");
int s2 = Convert.ToInt32(Console.ReadLine());

while(s1<s2)
{
    Console.Write(s1 ++);
}
*/
/*madde3
Console.WriteLine("1. sayıyı girin:");
int s1 = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("2. sayıyı girin:");
int s2 = Convert.ToInt32(Console.ReadLine());
do 
{
    Console.Write(s1 ++);
}while (s1<s2);*/
#### ödev_16 Pozitif bir tamsayının kaç basamağı olduğunu hesaplayan programı c# ile hazırlayın.
Kullanıcı negatif bir tamsayı girdiğinde, program uyarı mesajı göstermeli ve karşılık gelen
pozitif sayı ile devam etmelidir.
while (true)
{
Console.WriteLine("Sayı giriniz");
int s1 = Convert.ToInt32(Console.ReadLine());                
int sayaç = 0;
if (s1 < 0)
{
Console.WriteLine("hata sayı negatıf");
s1 *= -1;
while (s1 > 0)
{
s1 /= 10;
sayaç++;
}             
Console.WriteLine(sayaç+" Basamaklı");
}
else
{
while (s1 > 0)
{
s1 /= 10;
sayaç++;
}             
Console.WriteLine(sayaç+" Basamaklı");
}             
}
#### ödev_17 Sadece bir for döngüsü ve char değişkenleri kullanarak alfabenin büyük harflerini
gösteren bir C# programı yazın.
for (char i = 'A'; i <= 'Z'; i++)
{
Console.Write(i);
}
#### ödev_18 C# dilinde, bir sayının mutlak değerini hesaplayıp gösteren bir program yazın.
Eğer sayı pozitifse, mutlak değeri tam olarak sayı x'tir.
Eğer sayı negatifse, mutlak değeri -x'tir."
Console.WriteLine("Sayı giriniz");
int s1 = Convert.ToInt32(Console.ReadLine());  
if (s1>0)
{
    Console.WriteLine("sayının mutlak değerden çıkmış hali"+" "+s1);
}
else if (s1<0)
{
    Console.WriteLine("sayının mutlak değerden çıkmış hali"+" "+s1);
}
#### ödev_19 C# dilinde, kullanıcıdan iki tamsayı isteyen ve çarpımlarını gösteren, ancak *
operatörünü kullanmadan gerçekleştiren bir program oluşturun. Ardışık toplamları
kullanmalısınız
Console.WriteLine("1. sayıyı girin:");
int s1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("2. sayıyı girin:");
int s2 = Convert.ToInt32(Console.ReadLine());
int toplam = 0;
for (int i=1;i <=s1 ; i++)
{
    toplam += s2;
}
Console.WriteLine(toplam);
#### ödev_20 C# dilinde kullanıcıdan bir tamsayı soran ve bu sayının asal sayı olup olmadığını
yanıtlayan bir program yazın.
Console.WriteLine("Sayı giriniz");
int s1 = Convert.ToInt32(Console.ReadLine());
int kontrol = 0;
int i = 2;
while(i < s1)
{
   if(s1 % i == 0)
   {
       kontrol++;
     
   }
   i++;

}
if(kontrol != 0)
{
    Console.WriteLine("Asal sayı DEĞİL");
}
else
{
    Console.WriteLine("Asal sayı ");
}
#### ödev_21 C# dilinde, x'ten y'ye kadar olan tek sayıları azalan sırada gösteren bir program
oluşturun.
Console.WriteLine("1. sayıyı girin:");
int s1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("2. sayıyı girin:");
int s2 = Convert.ToInt32(Console.ReadLine());
while(s1>=s2)
{
    if(s1 % 2 == 1){
       Console.Write(s1+" ");
    }

    s1--;
}
#### ödev_22 Süpermarket kasasını simüle eden ve para üstünü hesaplamak için bir C# programı
oluşturun. Ürün fşyatı (x) ve verşlen para (y) alan ve gerşye para üstü veren programı yazın.
Değişimi büyük banknotları önce kullanarak 100, 50, 20, 10, 5, 2 veya 1 banknotlarını
kullanarak yapmalısınız.
Console.WriteLine("Ürün Fiyatını Giriniz: ");
int fiyat = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Para Giriniz: ");
int para = Convert.ToInt32(Console.ReadLine());

double paraüstü = 0;
if (para >= fiyat)
{
    paraüstü = para - fiyat;
    int kuruş = 100;
    while (paraüstü >= kuruş)
    {
    int kuruşler = (int)paraüstü / kuruş;
    paraüstü = paraüstü % kuruş;
    Console.WriteLine($"{kuruşler} {kuruş}");
    }
    if (paraüstü > 0)
    {
        Console.WriteLine($" paraüstü: {paraüstü}");
    }
}
else
{
    Console.WriteLine("Para Üstünde Kalmıyorsunuz.");
}
#### ödev_23 Kullanıcıdan iki sayı isteyen ve koşullu operatör (?) kullanarak aşağıdakileri yanıtlayan bir
C# programı oluşturun:
- Eğer ilk sayı pozitifse
- Eğer ikinci sayı pozitifse
- Eğer ikisi de pozitifse
Console.WriteLine("1. sayıyı girin:");
int s1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("2. sayıyı girin:");
int s2 = Convert.ToInt32(Console.ReadLine());

string name1 = s1 > 0 ? "pozitif" : s1 < 0 ? "negatif" : "notr";

string name2 = s2 > 0? "pozitif" : s2 < 0? "negatif" : "notr";

Console.WriteLine($"A = {name1} \nB = {name2}");
if (s1 > 0 && s2 > 0 ){
    Console.WriteLine("ikiside pozitif");
}
else if (s1 < 0 && s2 < 0){
    Console.WriteLine("ikiside neghatif");
}
