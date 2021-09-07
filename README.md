# aciklab2021
Havelsan Pardus Liman Kampı Ödev
2- Kalıcı bir çevre değişkeni tanımlanmak için /etc/environment sistem dosyası kullanılabilir.
3- Var olan disklere eklenecek disk bölümlerinin modüler bir şekilde sonradan eklenebilmesini sağlar.
4- Ext4,Linux ta kullanılan dosya sistemidir ve bu dosya sisteminin çalışma mantığı Linux sistemlerde performans artışı sağlayabilir. NTFS, Microsoft tarafında kullanılan dosya sistemidir,diğer dosya sistemlerine göre daha güvenilir bir yapıya sahiptir.
1- fibo modülünü ne kadar denesemde import edemedim.
sorunun olması gereken mantığını yazıyorum;
import fibo
def fib(n):   
    a, b = 0, 1
    while a < n:
        print(a)
        a, b = b, a+b
    print()
fib(10)
Çıktı : 
0
1
1
2
3
5
8


