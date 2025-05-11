# OmniTaskAndroid

🔍 **Genel Bakış**  
OmniTaskAndroid, günlük görevlerinizi ve notlarınızı yönetmenize yardımcı olan modern, basit ve kullanıcı dostu bir Android mobil uygulamasıdır. React Native ve yerel Android bileşenleri kullanılarak geliştirilen bu uygulama, verilerinizi yerel olarak saklar ve çevrimiçi bağlantı gerektirmez.  

✨ **Özellikler**  
- **Görev Yönetimi**: Kolay görev ekleme, düzenleme ve tamamlama.  
- **Kategori Sistemi**: Görevleri kategorilere ayırma ve filtreleme.  
- **Notlar**: Her görev için detaylı notlar tutma.  
- **LocalStorage**: Tüm veriler cihazda güvenli bir şekilde saklanır.  
- **Arama & Filtreleme**: Görevler ve kategoriler arasında hızlı arama.  
- **Tema Desteği**: Karanlık ve aydınlık tema seçenekleri.  
- **Mobil Optimizasyon**: Dokunmatik ekranlar ve mobil arayüz için tasarlanmış responsive tasarım.  
- **Bildirimler**: Görev hatırlatıcıları için yerel bildirim desteği.  
- **Cross-Device Uyumluluk**: Android cihazlarla sorunsuz çalışma.  

🔧 **Teknik Detaylar**  
OmniTaskAndroid aşağıdaki teknolojileri ve araçları kullanır:  

- **Frontend**:  
  - React Native  
  - Modern JavaScript (ES6+)  
  - CSS (Styled Components veya benzeri)  
  - Vector Icons  

- **Backend**:  
  - Yerel SQLite veritabanı (veya AsyncStorage)  
  - Cihazın yerel bildirim API’leri  

- **Diğer**:  
  - Android Studio (Geliştirme ve hata ayıklama)  
  - Gradle (Paketleme ve derleme)  
  - Context API (Durum yönetimi)  


🤝 **Katkıda Bulunma**  
- Kod katkısı yapmak için bir fork oluşturun ve pull request gönderin.  
- Hata bildirimleri veya öneriler için [Issues](https://github.com/muratalpaslan/OmniTaskAndroid/issues) bölümünü kullanın.  

📜 **Lisans**  
Bu proje MIT Lisansı ile lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasını inceleyin.

💡 **Geliştirici**  
- Geliştirici: Murat Alpaslan  
- İletişim: [GitHub Profilim](https://github.com/muratalpaslan)  

---

### **Gelecek Güncelle Notları**
1- Kategori ismi editlenmiyor.
2- Kategori alanında X tuşuna basıldığında direkt siliyor. Emin misin popup olsa iyi olur. 
3- Kategori içerisindeki bütün tasklar tamamlandıysa kategorinin üzeri otomatik çizilebilir ya da farklı bir şekilde renklendirilebilir.
4- Görev bölümlendirme alanında tamamlananlar/yapılacaklar gibi 'in progress 'state de eklenebilir.
5- Kategori bölümü de (görevler bölümü gibi) bölümlendirilendirilebilir.
6- Görevler arasında sıralama değişikliği yapılamıyor. (kullanıcı bakışıyla bug)
7- Görevler için alarm/timer eklenebilir. 
8- Kategoriler ve/veya görevler için deadline alanı eklenebilir.
