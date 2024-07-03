# Filament Admin Panel

Bu proje, Laravel tabanlı bir uygulama için geliştirilmiş bir admin panelidir. Filament Admin Panel, Laravel'in güçlü özelliklerini kullanarak kullanıcı dostu ve özelleştirilebilir bir yönetim arayüzü sağlar.

## Başlangıç

Bu kılavuz, Filament Admin Panel'i yerel makinenizde nasıl çalıştıracağınızı ve yapılandıracağınızı gösterir.

### Gereksinimler

- PHP >= 7.4
- Composer
- Laravel >= 8.x
- Node.js & NPM (isteğe bağlı, ön uç varlıkları için)

### Kurulum

1. **Depoyu Klonlayın:**

   ```bash
   [git clone https://github.com/your-username/filament-admin-panel-example.git](https://github.com/musttoprak/filament-admin-panel-example.git)
   cd filament-admin-panel-example
2. **Bağımlılıkları Kurun:**
   ```bash
   composer install
3. **.env Dosyasını Oluşturun:**
   .env.example dosyasını kopyalayın ve .env olarak adlandırın
   .env dosyasındaki veritabanı ayarlarını yapın:
   ```bash
    DB_CONNECTION=mysql
    DB_HOST=localhost
    DB_PORT=3306
    DB_DATABASE=your_database
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
4. **Uygulama Anahtarını Oluşturun:**
   ```bash
   php artisan key:generate
5. **Veritabanını Ayarlayın:**
   ```bash
   php artisan migrate
6. **Projeyi Çalıştırın:**
   ```bash
   php artisan serve
