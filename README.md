# Django-Docker-Sample

略して DDS

## チュートリアル

https://docs.djangoproject.com/ja/4.2/intro/tutorial01/

## 開発用サーバの起動

```bash
python3 manage.py runserver
```

## ディレクトリ追加

```bash
python3 manage.py startapp {:SOMETHING_FEATURE}
```

## DB のマイグレ

- 作成
  ```bash
  python3 manage.py makemigrations
  ```
- 反映
  ```bash
  python3 manage.py migrate
  ```
