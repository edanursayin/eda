# Görev 1 - Geliştirme Ortamı Raporu

## 1. Tercih Edilen İşletim Sistemi ve Kurulum Yöntemi
- **İşletim Sistemi / Ortam:** Windows üzerinde VirtualBox sanal makinesi ile Ubuntu Linux.
- **Kurulum Yöntemi:** VirtualBox ISO imajı ile sanal makine kurulumu.

## 2. Karşılaşılan Sorunlar ve Çözümler
- **Sorun:** HTTPS protokolü üzerinden `git clone` yaparken GitHub kullanıcı adı ve şifre kimlik doğrulaması hatası (`Password authentication is not supported`) alındı.
- **Çözüm:** SSH anahtarı (`ssh-keygen`) oluşturulup GitHub hesabına eklendi ve repo SSH adresi (`git@github.com:...`) üzerinden başarıyla klonlandı.

## 3. Terminal Sistem Bilgisi Çıktısı (`uname -a`)
```text
Linux edanur-VirtualBox 7.0.0-30-generic #30-Ubuntu SMP PREEMPT_DYNAMIC Fri Jul 31 18:22:54 UTC 2026 x86_64 GNU/Linux
