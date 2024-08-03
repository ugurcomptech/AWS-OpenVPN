# AWS OpenVPN

Bir önceki yazımızda Ubuntu sunucu üzerinde nasıl OpenVpn servisini kurabileceğiniz anlattık. Gayet basit bir kurulumdu. Bu yazımızda AWS üzerinden OpenVPN kullanacağız. Bu yöntem daha basit ve diğer sunuculara göre daha yüksek hız sağlamaktadır.

İlk öncelikle bir AWS hesabı oluşturmanız gerekmektedir. AWS hesabını oluşturduysanız adımlara geçelim.

## Open VPN Access Server

AWS Pazar Yeri AMI'leri sayfası üzerinden OpenVPN'i seçiyoruz.

![image](https://github.com/user-attachments/assets/dcdebb5e-a87f-4994-802e-1e5ff11a85e5)

![image](https://github.com/user-attachments/assets/9c242032-e1ad-46a4-a256-357dda638aaf)


"Subrice Now" butonuna tıklayo devam ediyoruz.



Bu sayfa üzerinden sadece bir key oluştuyoruz onun dışnda hiçbir ayara ellemiyoruz. 

![image](https://github.com/user-attachments/assets/0164f7e7-384a-4ebf-a6ad-1da2940587fe)

![image](https://github.com/user-attachments/assets/3a8eff0d-8cb9-42f7-bd86-0934a4844035)

![image](https://github.com/user-attachments/assets/8d30184b-515a-477b-baec-0732452a0b40)


Bulut sunucusunu başlat deyip ilerliyoruz.

![image](https://github.com/user-attachments/assets/cf7ae1d9-02b1-4652-b249-a546cc1762bc)


Sunucumuz oluştu.

Buradan sunucularımızı görüntüleyebiliyoruz. Bağlan butonuna basıyoruz.



![image](https://github.com/user-attachments/assets/ccd210dc-6986-44e4-b9e6-0327ad713ed3)


E2C Bulut Bağlantısını seçip bağlan diyoruz.

![image](https://github.com/user-attachments/assets/44e225e7-a8d0-4b6d-9543-fb68215d4eab)



## Kurulum

Aşağıda bulunan ekran görüntüsündeki adımları takip edin:

![image](https://github.com/user-attachments/assets/6f9ae963-875a-44c7-9688-faf85d332c98)
![image](https://github.com/user-attachments/assets/b43afe33-f857-468b-a935-47ef5876d4a9)


Kurulum tamamlandıktan sonra aşağıdaki gibi sizlere Web admin sayfasının adresi çıkacaktır:

![image](https://github.com/user-attachments/assets/e98282b0-4695-43b1-baf6-8ae6272324e9)

![image](https://github.com/user-attachments/assets/912d344e-35be-4b6b-82f1-b4c61e151d63)


Giriş sağladıktan sonra sol tarafta bulunan VPN ayarlarına girelim

![image](https://github.com/user-attachments/assets/ce517a4b-8991-4fae-b2e5-d996063fd211)

İlgili ayarı "YES" konumuna getirelim

![image](https://github.com/user-attachments/assets/02d0bf9e-3a67-47f0-8623-167cdadb88a9)


Kaydedelim

![image](https://github.com/user-attachments/assets/983a5b9f-feb2-4de9-bc0e-ceab4934afd8)

Kaydettikten sonra buraya tıklayalım

![image](https://github.com/user-attachments/assets/9037fd9b-185b-43cc-b87e-dd16618a8b41)


## OpenVPN İstemci Ayarı

OpenVPN istemcisini indirip aşağıdaki gibi bağlantı sağlayabilirsiniz.

![image](https://github.com/user-attachments/assets/27ede77f-093c-4144-92dc-c65f1dcea070)

İleriye gitmek istediğinizde karşınıza bir uyaru çıkacak onu kabul edip devam ediniz.

Gerekli yerleri dolduktan sonra butona tıklayınız.

![image](https://github.com/user-attachments/assets/c561f2dd-6925-4d0a-b341-eed26248f0dd)


Bağlanmaya çalıştığımda tekrar şifre soruyor. Şifremizi girip ilerliyoruz.


![image](https://github.com/user-attachments/assets/56e443f0-6e74-4657-b9f7-c5fa4851d998)


Şifremizi girdikten sonra başarılı bir şekilde bağlanmış oluyoruz.

![image](https://github.com/user-attachments/assets/620ea507-df08-4bc4-8e6a-2e53cd290e21)


![image](https://github.com/user-attachments/assets/8254f1ed-a59f-4eae-aacf-1ca4e87394cc)



## Teşekkür

Okudunuz için teşekkürler.




