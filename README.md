# portfolio-feature-engineering

## Diabet

### İş problemi

Türkiye’nin en büyük online hizmet platformu olan Armut, hizmet verenler ile hizmet almak isteyenleri buluşturmaktadır. Bilgisayarın veya akıllı telefonunun üzerinden birkaç dokunuşla temizlik, tadilat, nakliyat gibi hizmetlere kolayca ulaşılmasını sağlamaktadır.

### Veri Seti Hikayesi

Veri seti ABD'deki Ulusal Diyabet-Sindirim-Böbrek Hastalıkları Enstitüleri'nde tutulan büyük veri setinin parçasıdır. ABD'deki Arizona Eyaleti'nin en büyük 5. şehri olan Phoenix şehrinde yaşayan 21 yaş ve üzerinde olan Pima Indian kadınları üzerinde yapılan diyabet araştırması için kullanılan verilerdir. 

Hedef değişken **"outcome"** olarak belirtilmiş olup; **1** diyabet test sonucunun **pozitif** oluşunu, **0** ise **negatif** oluşunu belirtmektedir.

  Değişkenler;

* Pregnancies: Hamilelik sayısı
* Glucose: Glikoz
* BloodPressure: Kan basıncı (Diastolic(Küçük Tansiyon))
* SkinThickness: Cilt Kalınlığı
* Insulin: İnsülin.
* BMI: Beden kitle indeksi.
* DiabetesPedigreeFunction: Soyumuzdaki kişilere göre diyabet olma ihtimalimizi hesaplayan bir fonksiyon.
* Age: Yaş (yıl)
* Outcome: Kişinin diyabet olup olmadığı bilgisi. Hastalığa sahip (1) ya da değil (0)

## TelCo

### İş problemi

Şirketi terk edecek müşterileri tahmin edebilecek bir makine öğrenmesi modeli geliştirilmesi istenmektedir. Modeli geliştirmeden önce gerekli olan veri analizi ve özellik mühendisliği adımlarını gerçekleştirmeniz beklenmektedir.

### Veri Seti Hikayesi

Telco müşteri kaybı verileri, üçüncü çeyrekte Kaliforniya'daki 7043 müşteriye ev telefonu ve İnternet hizmetleri sağlayan hayali bir telekom şirketi hakkında bilgi içerir. Hangi müşterilerin hizmetlerinden ayrıldığını, kaldığını veya hizmete kaydolduğunu gösterir.

  Değişkenler;

CustomerId       : Müşteri İd’si
Gender           : Cinsiyet
SeniorCitizen    : Müşterinin yaşlı olup olmadığı (1, 0)
Partner          : Müşterinin bir ortağı olup olmadığı (Evet, Hayır) ? Evli olup olmama
Dependents       : Müşterinin bakmakla yükümlü olduğu kişiler olup olmadığı (Evet, Hayır) (Çocuk, anne, baba, büyükanne)
tenure           : Müşterinin şirkette kaldığı ay sayısı
PhoneService     : Müşterinin telefon hizmeti olup olmadığı (Evet, Hayır)
MultipleLines    : Müşterinin birden fazla hattı olup olmadığı (Evet, Hayır, Telefon hizmeti yok)
InternetService  : Müşterinin internet servis sağlayıcısı (DSL, Fiber optik, Hayır)
OnlineSecurity   : Müşterinin çevrimiçi güvenliğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
OnlineBackup     : Müşterinin online yedeğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
DeviceProtection : Müşterinin cihaz korumasına sahip olup olmadığı (Evet, Hayır, İnternet hizmeti yok)
TechSupport      : Müşterinin teknik destek alıp almadığı (Evet, Hayır, İnternet hizmeti yok)
StreamingTV      : Müşterinin TV yayını olup olmadığı (Evet, Hayır, İnternet hizmeti yok) 
                   Müşterinin, bir üçüncü taraf sağlayıcıdan televizyon programları yayınlamak için 
                   İnternet hizmetini kullanıp kullanmadığını gösterir
StreamingMovies  : Müşterinin film akışı olup olmadığı (Evet, Hayır, İnternet hizmeti yok) 
                   Müşterinin bir üçüncü taraf sağlayıcıdan film akışı yapmak için 
                   İnternet hizmetini kullanıp kullanmadığını gösterir
Contract         : Müşterinin sözleşme süresi (Aydan aya, Bir yıl, İki yıl)
PaperlessBilling : Müşterinin kağıtsız faturası olup olmadığı (Evet, Hayır)
PaymentMethod    : Müşterinin ödeme yöntemi 
                   (Elektronik çek, Posta çeki, Banka havalesi (otomatik), Kredi kartı (otomatik))
MonthlyCharges   : Müşteriden aylık olarak tahsil edilen tutar
TotalCharges     : Müşteriden tahsil edilen toplam tutar
Churn            : Müşterinin kullanıp kullanmadığı (Evet veya Hayır)
                   Geçen ay veya çeyreklik içerisinde ayrılan müşteriler
