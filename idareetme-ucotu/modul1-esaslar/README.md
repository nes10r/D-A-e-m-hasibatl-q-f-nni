# 📚 Modul 1: İdarəetmə Uçotunun Əsasları

<div align="center">

![Modul 1](https://img.shields.io/badge/Modul_1-Əsaslar-blue?style=for-the-badge&logo=book-open)
![Müddət](https://img.shields.io/badge/Müddət-3_Həftə-green?style=for-the-badge&logo=calendar)
![Səviyyə](https://img.shields.io/badge/Səviyyə-Başlanğıc-yellow?style=for-the-badge&logo=star)

</div>

## 🎯 Modulun Məqsədləri

```mermaid
mindmap
  root((Modul 1 Məqsədləri))
    [Nəzəri Əsaslar]
      İdarəetmə Uçotunun Mahiyyəti
      Tarix və İnkişaf
      Müasir Trendlər
    [Praktik Anlayışlar]
      Məlumat Növləri
      Hesabat Sistemləri
      Qərar Qəbuletmə
    [E-Mühasibat Giriş]
      Rəqəmsal Transformasiya
      Avtomatlaşdırma
      Cloud Texnologiyalar
    [Peşəkar Bacarıqlar]
      Analitik Düşüncə
      Kommunikasiya
      Excel Əsasları
```

## 📊 Həftəlik Proqram

```mermaid
gantt
    title Modul 1 - Detallı Təqvim
    dateFormat  X
    axisFormat %w
    
    section Həftə 1: Giriş
    İdarəetmə uçotunun mahiyyəti     :1, 2
    Maliyyə vs İdarəetmə uçotu       :2, 1
    Praktik nümunələr               :2, 1
    
    section Həftə 2: E-Mühasibat
    Rəqəmsal transformasiya         :3, 2
    Cloud platformaları             :4, 1
    Avtomatlaşdırma faydaları       :4, 1
    
    section Həftə 3: Praktik
    Excel əsasları                  :5, 2
    İlk layihə                      :6, 1
    Qiymətləndirmə                  :6, 1
```

## 🧠 Əsas Anlayışlar

```mermaid
graph TD
    A[İdarəetmə Uçotu] --> B[Daxili İstifadə]
    A --> C[Qərar Dəstəyi]
    A --> D[Planlaşdırma]
    A --> E[Nəzarət]
    
    B --> B1[Menecerlər]
    B --> B2[Departament Rəhbərləri]
    B --> B3[İcraçı Heyət]
    
    C --> C1[Büdcə Qərarları]
    C --> C2[İnvestisiya Seçimi]
    C --> C3[Qiymətsistemində]
    
    D --> D1[Strateji Planlar]
    D --> D2[Əməliyyat Büdcələri]
    D --> D3[Performans Hədəfləri]
    
    E --> E1[Faktiki vs Plan]
    E --> E2[Sapma Təhlili]
    E --> E3[Düzəldici Tədbirlər]
    
    style A fill:#e1f5fe
    style B1 fill:#c8e6c9
    style C1 fill:#fff3e0
    style D1 fill:#f3e5f5
    style E1 fill:#e8f5e8
```

## 📈 İdarəetmə Uçotu vs Maliyyə Uçotu

```mermaid
flowchart LR
    A[Mühasibat Məlumatları] --> B{İstifadə Məqsədi}
    
    B -->|Daxili İdarəetmə| C[İdarəetmə Uçotu]
    B -->|Xarici Hesabatlar| D[Maliyyə Uçotu]
    
    C --> C1[Planlaşdırma]
    C --> C2[Qərar Qəbuletmə]
    C --> C3[Performans Ölçmə]
    C --> C4[Nəzarət]
    
    D --> D1[Maliyyə Vəziyyəti]
    D --> D2[Fəaliyyət Nəticələri]
    D --> D3[Pul Axınları]
    D --> D4[Kapital Dəyişiklikləri]
    
    C1 --> E[Daxili Hesabatlar]
    C2 --> E
    C3 --> E
    C4 --> E
    
    D1 --> F[Xarici Hesabatlar]
    D2 --> F
    D3 --> F
    D4 --> F
    
    style C fill:#4caf50
    style D fill:#2196f3
    style E fill:#ffeb3b
    style F fill:#ff9800
```

## 🎯 Həftə 1: İdarəetmə Uçotunun Mahiyyəti

### 📚 Nəzəri Hissə

**İdarəetmə Uçotunun Tərifі:**
> İdarəetmə uçotu - təşkilatın daxili idarəetmə ehtiyacları üçün məlumat toplama, emal etmə və təqdim etmə prosesidir.

```mermaid
pie title İdarəetmə Uçotunun Funksiyaları
    "Planlaşdırma" : 25
    "Qərar Dəstəyi" : 20
    "Performans Ölçmə" : 20
    "Nəzarət" : 15
    "Koordinasiya" : 12
    "Motivasiya" : 8
```

### 🛠️ Praktik Tapşırıqlar

**Tapşırıq 1.1: Şirkət Analizi**
```
📋 Kiçik bir şirkət seçin və analiz edin:
   ✅ Şirkətin əsas fəaliyyəti
   ✅ İdarəetmə strukturu
   ✅ Mövcud hesabat sistemləri
   ✅ İdarəetmə uçotunun tətbiq sahələri
```

**Tapşırıq 1.2: Müqayisəli Cədvəl**
```
📊 İdarəetmə vs Maliyyə Uçotu cədvəli hazırlayın:
   📈 İstifadəçilər
   📈 Məqsədlər  
   📈 Hesabat tezliyi
   📈 Məlumat növləri
```

## 💻 Həftə 2: E-Mühasibat və Rəqəmsal Transformasiya

### 🌟 Rəqəmsal Transformasiyanın Mərhələləri

```mermaid
journey
    title Rəqəmsal Transformasiya Yolculuğu
    section Ənənəvi Dövrü
      Kağız sənədlər: 2: Şirkət
      Manual hesablamalar: 1: Şirkət
      Gecikmələr: 1: Şirkət
    section Keçid Mərhələsi
      Excel-ə keçid: 4: Şirkət
      İlk avtomatlaşdırma: 3: Şirkət
      Hibrid sistem: 3: Şirkət
    section Rəqəmsal Dövr
      Cloud sistemlər: 5: Şirkət
      Real-time məlumat: 5: Şirkət
      AI/ML inteqrasiyası: 5: Şirkət
```

### ☁️ Cloud Texnologiyalarının Faydaları

```mermaid
graph LR
    A[Cloud E-Mühasibat] --> B[Fəxriyyətlər]
    
    B --> B1[💰 Xərc Azalması]
    B --> B2[🔒 Təhlükəsizlik]
    B --> B3[📱 Mobility]
    B --> B4[🔄 Avtomatik Yenilənmə]
    B --> B5[📊 Real-time Məlumat]
    
    B1 --> C1[Server xərcləri yox]
    B1 --> C2[IT dəstək azalması]
    
    B2 --> C3[Professional backup]
    B2 --> C4[Kibertəhlükəsizlik]
    
    B3 --> C5[Harada olursa olsun giriş]
    B3 --> C6[Mobil tətbiqlər]
    
    B4 --> C7[Həmişə son versiya]
    B4 --> C8[Texniki dəstək]
    
    B5 --> C9[Canlı dashboard]
    B5 --> C10[Ani hesabatlar]
    
    style A fill:#4285f4
    style B1 fill:#34a853
    style B2 fill:#ea4335
    style B3 fill:#fbbc04
    style B4 fill:#9c27b0
    style B5 fill:#ff6d01
```

### 🛠️ Praktik Tapşırıqlar

**Tapşırıq 2.1: Cloud Platformaları Tədqiqi**
```
🔍 Aşağıdakı platformaları araşdırın:
   ☁️ Google Workspace
   ☁️ Microsoft 365
   ☁️ Xero (mühasibat)
   ☁️ QuickBooks Online
   
📝 Hər birinin xüsusiyyətlərini müqayisə edin
```

## 📊 Həftə 3: Excel Əsasları və İlk Layihə

### 📈 Excel-də İdarəetmə Uçotu Alətləri

```mermaid
graph TD
    A[Excel İdarəetmə Alətləri] --> B[Məlumat Analizi]
    A --> C[Vizuallaşdırma]
    A --> D[Avtomatlaşdırma]
    A --> E[Hesabatlar]
    
    B --> B1[PivotTable]
    B --> B2[Power Query]
    B --> B3[Data Analysis]
    B --> B4[Solver]
    
    C --> C1[Charts]
    C --> C2[Conditional Formatting]
    C --> C3[Sparklines]
    C --> C4[Dashboard]
    
    D --> D1[Macros]
    D --> D2[VBA]
    D --> D3[Form Controls]
    D --> D4[Data Validation]
    
    E --> E1[Financial Templates]
    E --> E2[KPI Reports]
    E --> E3[Budget vs Actual]
    E --> E4[Variance Analysis]
    
    style A fill:#217346
    style B fill:#2f5f8f
    style C fill:#c55a11
    style D fill:#7030a0
    style E fill:#833c0c
```

### 🎯 İlk Layihə: Sadə Büdcə Sistemi

**Layihə Təsviri:**
```
🏢 Kiçik kafeya üçün aylıq büdcə sistemi yaradın:
   
   📊 Gəlir Hissəsi:
   - Məhsul satışları
   - İçki satışları  
   - Əlavə xidmətlər
   
   💰 Xərc Hissəsi:
   - Xammal
   - Əmək haqqı
   - İcarə
   - Utilities
   - Marketing
   
   📈 Təhlil:
   - Profit/Loss hesablaması
   - Break-even nöqtəsi
   - Variance analysis
```

## ✅ Modulu Bitirmə Tələbləri

```mermaid
flowchart TD
    A[Modul 1 Başlangıcı] --> B{Həftəlik Tapşırıqlar}
    
    B -->|Tapşırıq 1.1| C[Şirkət Analizi]
    B -->|Tapşırıq 1.2| D[Müqayisəli Cədvəl]
    B -->|Tapşırıq 2.1| E[Cloud Tədqiqi]
    
    C --> F{Qiymətləndirmə}
    D --> F
    E --> F
    
    F -->|70%+| G[İlk Layihə]
    F -->|<70%| H[Təkrar Tapşırıq]
    
    G --> I[Excel Büdcə Sistemi]
    H --> B
    
    I --> J{Final Qiymətləndirmə}
    
    J -->|Uğurlu| K[✅ Modul Tamamlandı]
    J -->|Təkmilləşdirmə| L[📝 Əlavə İş]
    
    K --> M[Modul 2-yə Keçid]
    L --> I
    
    style A fill:#e1f5fe
    style K fill:#c8e6c9
    style M fill:#fff3e0
```

## 📚 Oxu Materialları

### 📖 Məcburi Ədəbiyyat:
1. **Rayburn, L.G.** - "Principles of Cost Accounting" - Chapter 1-2
2. **Əhmədov, N.** - "İdarəetmə Uçotunun Əsasları" - Bölmə 1
3. **Garrison, R.** - "Managerial Accounting" - Chapter 1

### 🌐 Onlayn Mənbələr:
- [Khan Academy - Accounting Basics](https://khanacademy.org/accounting)
- [Coursera - Introduction to Management Accounting](https://coursera.org)
- [Excel Campus - Management Reporting](https://excelcampus.com)

### 📹 Video Dərslər:
- "İdarəetmə Uçotuna Giriş" - YouTube playlist
- "Excel for Management Accounting" - Udemy kursu
- "Cloud Accounting Basics" - LinkedIn Learning

## 🎯 Növbəti Addımlar

```mermaid
roadmap
    title Moduldən Sonrakı Yol
    section Bilik Təsdiqi
        Əsas anlayışları: done
        Excel bacarıqları: done
        Cloud awareness: done
    section Praktik Tətbiq
        İlk layihə: done
        Portfolio başlanğıcı: active
    section Hazırlıq
        Modul 2 üçün: active
        Maliyyə bilgiləri: milestone
```

---

<div align="center">

![Progress](https://img.shields.io/badge/Tərəqqi-33%25-brightgreen?style=for-the-badge)
![Next](https://img.shields.io/badge/Növbəti-Modul_2-blue?style=for-the-badge&logo=arrow-right)

**🎉 Modul 1-i uğurla tamamladınız!**

*Modul 2: Maliyyə İdarəetməsinə hazır olun! 🚀*

</div> 