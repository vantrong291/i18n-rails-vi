Hỗ trợ tiếng Việt cho dự án Ruby On Rails
=========================================

Vietnamese support for Ruby On Rails projects
Nguồn: https://github.com/svenfuchs/rails-i18n/blob/master/rails/locale/vi.yml  -- Đã chỉnh sửa để phù hợp hơn với tiếng Việt

## Cài đặt Gem:

Thêm một trong các dòng sau vào file Gemfile:

    gem 'rails-i18n', '~> 5.1' # Cho Rails 5.0.x, 5.1.x and 5.2.x
    gem 'rails-i18n', '~> 4.0' # Cho Rails 4.0.x
    gem 'rails-i18n', '~> 3.0' # Cho Rails 3.x
    gem 'rails-i18n', github: 'svenfuchs/rails-i18n', branch: 'master' # For 5.x
    gem 'rails-i18n', github: 'svenfuchs/rails-i18n', branch: 'rails-4-x' # For 4.x
    gem 'rails-i18n', github: 'svenfuchs/rails-i18n', branch: 'rails-3-x' # For 3.x

Hoặc chạy một trong các dòng lệnh sau:

    gem install rails-i18n -v '~> 5.1' # Cho Rails 5.0.x, 5.1.x and 5.2.x
    gem install rails-i18n -v '~> 4.0' # Cho Rails 4.0.x
    gem install rails-i18n -v '~> 3.0' # Cho Rails 3.x



Sau khi cài đặt i18n: Download file "vi.yml" đặt trong thư mục config/locales
    
    config.i18n.default_locale = :vi
    
Thêm dòng này vào config/application.rb
    

Chạy lại server "rais s".

