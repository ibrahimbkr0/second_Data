# README.md

## 📌 Görev #2: README.md Dosyasını Oluşturma

Bu belge, kullanılan Git komutları, yerel Git iş akışı ile GitHub iş akışı arasındaki farklar, süreç boyunca karşılaşılan zorluklar, commit yapma kararları ve yapay zekanın süreçteki rolüne dair bilgileri içermektedir.

---

## 🛠 Kullanılan Git Komutları

```bash
# Yeni bir Git deposu başlat
git init

# Var olan bir GitHub deposunu klonla
git clone <repo_url>

# Değişiklikleri sahneye al
git add <dosya>

# Sahneye alınan değişiklikleri commit et
git commit -m "mesaj"

# Commit edilen değişiklikleri uzak depoya gönder
git push origin main

# Uzak depodaki en son değişiklikleri çek
git pull origin main

# Yeni bir dal (branch) oluştur
git branch <dal_adi>

# Belirtilen dala geç
git checkout <dal_adi>

# Bir dalı mevcut dala birleştir
git merge <dal_adi>
```

---

## 🔄 Yerel Git İş Akışı vs. GitHub İş Akışı

### 🏠 Yerel Git İş Akışı:
- Kod değişiklikleri yerelde yapılır.
- `git add` komutu ile değişiklikler sahneye alınır.
- `git commit` ile değişiklikler kaydedilir.
- Depo, uzak bir depoya gönderilene kadar yerel olarak kalır.

### ☁️ GitHub İş Akışı:
- Değişiklikler `git push` ile GitHub’a gönderilir.
- İşbirliği, pull request'ler ve kod incelemeleri ile gerçekleşir.
- Birleştirmeler (merge) GitHub arayüzü veya `git merge` ile yapılır.
- Uzak depodaki güncellemeler `git pull` komutu ile alınır.

---

## ⚠️ Karşılaşılan Zorluklar
- Yerel ve uzak depolar arasındaki farkları anlamak.
- Farklı dallarla çalışırken merge (birleştirme) çakışmalarını çözmek.
- Git komutlarının doğru sırasını hatırlamak.
- Sahneye alınmış ve alınmamış değişiklikleri yönetmek.

---

## ✅ Commit Yapma Kararları
Commit işlemlerini şu önemli noktalarda gerçekleştirdim:
- Yeni bir özellik ekledikten veya bir hatayı düzelttikten sonra.
- Uzak depodan değişiklikleri çekmeden önce.
- Merge çakışmalarını çözdükten sonra stabil bir duruma ulaştığımda.
- Dal değiştirmeden önce veri kaybını önlemek için.

---

## 🤖 Yapay Zeka Kullanımı

### 🔍 Yapay Zeka Nasıl Yardımcı Oldu?
Yapay zekadan şu konularda destek aldım:
- Yerel ve uzak iş akışları arasındaki farkları anlamak.
- Merge çakışmaları ve hata mesajlarını çözmek.
- En iyi commit mesajı uygulamalarını öğrenmek.

### 📌 Kullanılan Platform:
**ChatGPT** kullanarak Git komutları, iş akışları ve hata giderme süreçleri hakkında sorular sordum.

### 📚 Öğrendiklerim:
- İşbirliği için etkili bir Git iş akışı nasıl yönetilir.
- Açıklayıcı commit mesajlarının önemi.
- Çakışmaları nasıl verimli bir şekilde çözeceğim.

---

## 📖 Ek Kaynaklar
- [Git Dokümantasyonu](https://git-scm.com/doc)
- [GitHub Dokümanları](https://docs.github.com/)

---

## 📷 Git İş Akışı Örneği

![Git İş Akışı](image.png)  
*Şekil: Örnek Git İş Akışı*

