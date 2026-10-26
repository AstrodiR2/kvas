# Квас APK

Положи свой HTML в `www/index.html` (если ещё не лежит), потом:

```sh
git init -b main
git add .
git commit -m "kvas apk"
gh repo create kvas --private --source=. --push
gh run watch
gh run download -n kvas-apk
```

Файл `app-debug.apk` появится в текущей папке. Ставь на телефон.
