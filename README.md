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