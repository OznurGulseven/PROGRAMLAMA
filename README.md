# PROGRAMLAMA
#Ödev 1


    x=int(input("finansman gelirini giriniz:"))
    y=int(input("pazar gelirini giriniz:"))
    z=int(input("kira gelirini giriniz:"))
    q=int(input("ücreti giriniz:"))
    w=int(input("pazar giderini giriniz:"))
    s=int(input("kira giderini giriniz:"))
    p=int(input("muhasebe giderini giriniz:"))
    n=(x+y+z)-(q+w+s+p)
    if (int(n)>1000):
    print("İşletme kar elde etmiştir.")
    elif (int(n)<1000):
    print("İşletme zarar elde etmiştir.")
    else:
    print("Ne kar ne de zarar etmiştir.")
    
#Ödev2


     def kullanilabilirlikHesapla ():
     x=int(input("planlanmış üretim süresi giriniz:"))
     y=int(input("plansız duruşu giriniz:"))
     kullanilabilirlik=((x-y)/x)
     return kullanilabilirlik

    def performansHesapla ():
    z=int(input("standart çevrim süresini giriniz:"))
    q=int(input("üretim miktarını giriniz."))
    x=int(input("planlanmış üretim süresi giriniz:"))
    y=int(input("plansız duruşu giriniz:"))
    performans=((z*q)/(x/y))
    return performans

     def kaliteHesapla ():
     s=int(input("sağlam ürün miktarını giriniz:"))
     p=int(input("toplam Üretim mitarını giriniz:"))
     kalite=(s/p)
     return kalite
    
     def OeeHesapla ():
     x=int(input("planlanmış üretim süresi giriniz:"))
     y=int(input("plansız duruşu giriniz:"))
     z=int(input("standart çevrim süresini giriniz:"))
     q=int(input("üretim miktarını giriniz."))
     s=int(input("sağlam ürün miktarını giriniz:"))
     p=int(input("toplam Üretim mitarını giriniz:"))
     Oee=(((x-y)/x)*((z*q)/(x/y))*(s/p)*100/100)
     return Oee
#Ödev3


     def ciroHesapla (x,y):
     print (x*y)
     #z=toplam ciro, q=toplam çalışan sayısı
     def AdambasiCiroHesapla (z,q):
     print (z/q)
     #x=satış miktarı, y=birim fiyatı
     def ciroHesapla (x,y):
     print (x*y)
     #z=toplam ciro, q=toplam çalışan sayısı
     def AdambasiCiroHesapla (z,q):
     print (z/q)
