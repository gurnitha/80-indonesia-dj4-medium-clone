# 80-indonesia-dj5-medium-clone
Membuat Aplikasi Blog MEDIUM CLONE Menggunakan Django Versi 5
Github:https://github.com/gurnitha/80-indonesia-dj5-medium-clone
Lokal:C:\Users\ING\Desktop\workspace\80-indonesia-dj5-medium-clone


## 00. PENDAHULUAN

## 01. GETING READY TO BLOG

## 02. DASAR-DASAR DJANGO

#### 1. Membuat proyek Django dengan nama config

        modified:   README.md
        new file:   config/config/__init__.py
        new file:   config/config/asgi.py
        new file:   config/config/settings.py
        new file:   config/config/urls.py
        new file:   config/config/wsgi.py
        new file:   config/manage.py

        config
        ├── config
        │   ├── __init__.py
        │   ├── asgi.py
        │   ├── settings.py
        │   ├── urls.py
        │   └── wsgi.py
        └── manage.py

#### 2. Merestrukturisasi struktur proyek

        modified:   README.md
        renamed:    config/config/__init__.py -> config/__init__.py
        renamed:    config/config/asgi.py -> config/asgi.py
        renamed:    config/config/settings.py -> config/settings.py
        renamed:    config/config/urls.py -> config/urls.py
        renamed:    config/config/wsgi.py -> config/wsgi.py
        renamed:    config/manage.py -> manage.py

#### 3. Membuat apliksi blog di dalam folder apps

        modified:   README.md
        new file:   apps/blog/__init__.py
        new file:   apps/blog/admin.py
        new file:   apps/blog/apps.py
        new file:   apps/blog/migrations/__init__.py
        new file:   apps/blog/models.py
        new file:   apps/blog/tests.py
        new file:   apps/blog/views.py

#### 4. Mendefinisikan path untuk aplikasi pada proyek

        # settings.py
        import os, sys
        APPS_DIR = os.path.join(BASE_DIR, 'apps')
        sys.path.insert(0, APPS_DIR)

        modified:   README.md
        modified:   config/settings.py

#### 5. Register aplikasi blog pada proyek

        modified:   README.md
        modified:   config/settings.py

#### 6. Halo Dunia! - urls, views, templates

        modified:   README.md
        new file:   apps/blog/urls.py
        modified:   apps/blog/views.py
        modified:   config/settings.py
        modified:   config/urls.py
        new file:   templates/blog/index.html

        :)

#### 7. Added html template to home page

        modified:   README.md
        modified:   templates/blog/index.html

#### 8. Added and loaded static files

        modified:   config/settings.py
        new file:   static/css/bootstrap.min.css
        new file:   static/css/bootstrap.min.css.map
        new file:   static/css/style.css
        new file:   static/css/tagify.css
        new file:   static/js/axios.min.js
        new file:   static/js/bootstrap.bundle.min.js
        new file:   static/js/bootstrap.bundle.min.js.map
        new file:   static/js/tagify.js
        new file:   static/js/tagify.polyfills.min.js
        new file:   static/js/tinymce.min.js
        modified:   templates/blog/index.html

        :)

#### 9. Membuat template inheritance

        modified:   README.md
        modified:   templates/blog/index.html
        new file:   templates/components/hero.html
        new file:   templates/components/posts_latest.html
        new file:   templates/components/posts_trend.html
        new file:   templates/inc/navbar.html

#### 10. Membuat base tamplate

        modified:   README.md
        new file:   templates/base.html
        modified:   templates/blog/index.html

#### 11. Membuat page title dinamis

        modified:   README.md
        modified:   templates/base.html
        modified:   templates/blog/index.html