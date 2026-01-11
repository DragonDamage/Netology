### 1. Работа с облачными решениями

В CMD на Windows делаем
```bash
$ ssh-keygen -t rsa -b 4096
```

Видим в какую директорию сохранился файл
```C:\Users\DragonDamage/.ssh/id_rsa```

Берём файл ```id_rsa.pub```

Вставляем в Console.Yandex.Cloud при создании ВМ

Логин: admin
Ждём пока создастся ВМ, и подключаемся:
```bash
$ ssh -l admin 178.154.221.208
```

Проверка установлен ли Docker:
```bash
$ sudo docker --version
Docker version 20.10.21, build 20.10.21-0ubuntu1~22.04.3
```
---

### 2. NEXT
