# ASP.NET MVC 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)](#)
[![ASP.NET](https://img.shields.io/badge/ASP.NET-5C2D91?style=flat&logo=dotnet&logoColor=white)](#)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](#)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white)](#)
[![Microsoft SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=flat&logo=microsoftsqlserver&logoColor=white)](#)
[![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat&logo=visualstudio&logoColor=white)](#)

Bu depo, **ASP.NET MVC (Model-View-Controller)** mimarisini öğrenme sürecimde geliştirdiğim web uygulamalarını, projeleri ve pratik çalışmalarımı içermektedir.

## 🎯 Proje Hakkında

Bu çalışma, modern web uygulamaları geliştirmek için Microsoft'un MVC tasarım desenini nasıl kullandığını kavramak amacıyla oluşturulmuştur. Projeler, arka uç (backend) mantığı ile kullanıcı arayüzünün (frontend) birbirinden nasıl izole edildiğini ve veritabanı işlemlerinin nasıl entegre edildiğini göstermektedir.

Proje temel olarak şu konuları kapsar:
1. **Model-View-Controller (MVC) Yapısı:** Veri (Model), Arayüz (View) ve İş Mantığı (Controller) arasındaki iletişimin kurulması.
2. **Entity Framework & LINQ:** Veritabanı işlemleri (CRUD) için ORM (Object-Relational Mapping) araçlarının kullanımı ve veri sorgulama.
3. **Routing (Yönlendirme):** SEO uyumlu ve kullanıcı dostu URL yapılarının oluşturulması.
4. **State Management:** Session, Cookie, ViewData, ViewBag ve TempData kullanımları.

## 📂 İçerik ve Klasör Yapısı

MVC mimarisinin standart klasör yapısına sadık kalınarak oluşturulmuştur:

* **`Controllers/`**: Gelen HTTP isteklerini işleyen, Model ve View arasındaki koordinasyonu sağlayan C# sınıfları.
* **`Models/`**: Veritabanı tablolarını temsil eden sınıflar (Entities) ve iş kuralları.
* **`Views/`**: Kullanıcıya gösterilecek olan HTML/Razor (`.cshtml`) arayüz dosyaları.
* **`wwwroot/` (veya `Content/` - `Scripts/`):** CSS, JavaScript, resimler ve Bootstrap gibi statik dosyalar.

## 🛠️ Kullanılan Teknolojiler

* **Backend:** C#, ASP.NET MVC
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap, Razor View Engine
* **Veritabanı:** Microsoft SQL Server
* **ORM:** Entity Framework (Code First / Database First)
* **Geliştirme Ortamı:** Visual Studio

## 🚀 Kurulum ve Çalıştırma

Projeyi yerel bilgisayarınıza klonlamak ve Visual Studio üzerinde çalıştırmak için:

1. **Repoyu klonlayın:**
   ```bash
   git clone https://github.com/halukcansarioz/Asp.Net-Mvc.git

2. **Projeyi Açın**: 
  Klasör içerisindeki .sln (Solution) dosyasına çift tıklayarak projeyi Visual Studio'da açın.

3. **Bağımlılıkları Yükleyin**: Eğer eksik NuGet paketleri varsa, Visual Studio bunları otomatik olarak indirecektir (veya projeye sağ tıklayıp Restore NuGet Packages seçeneğini kullanabilirsiniz).

4. **Veritabanı Bağlantısı**: appsettings.json veya Web.config dosyası içerisindeki ConnectionString ayarını kendi SQL Server ortamınıza göre güncelleyin.

5. **Çalıştırın**: Üst menüden IIS Express veya proje adınıza tıklayarak (kısayol: F5) projeyi tarayıcınızda başlatın.
