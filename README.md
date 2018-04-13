int[] buyuksayi = new int[10];
 int[] kucuksayi = new int[10];
 int i,sayi;
 
for (i = 0; i <= 5; i++)
 {
 Console.Write("sayıyı giriniz..:");
 sayi = Convert.ToInt16(Console.ReadLine());
 
 if (sayi >= 50)
 {
 buyuksayi[i] = sayi;
 }
 else
 {
 kucuksayi[i] = sayi;
 }
 }
 
 Console.WriteLine("Büyük Sayılar");
 Console.WriteLine("-------------------------");
 for(i=0; i<=5; i++)
 {
 Console.WriteLine(buyuksayi[i]);
 }
 Console.WriteLine("Küçük Sayılar");
 Console.WriteLine("-------------------------");
 for (i = 0; i <= 5; i++)
 {
 Console.WriteLine(kucuksayi[i]);
 }
 Console.ReadKey();
