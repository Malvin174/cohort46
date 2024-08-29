 - настройка Git на компьютере:
        - `git config --global -l` посмотреть текущие настройки
        - `git config --global user.name "Malvin174"` настройка имени
        - `git config --global user.email "geldo410@gmail.com"` настройка email

        - выгрузить публичный ключ на GitHub
        - просмотр публичного ключа (если ошибка, то надо сгенерировать)
            - `cat ~/.ssh/id_ed25519.pub`
            - `cat ~/.ssh/id_rsa.pub`
        - `ssh-keygen -t ed25519 -C 'email@example.org'` сгенирировать пару ключей (ВЫПОЛНИТЬ ТОЛЬКО В НАЧАЛЕ КАРЬЕРЫ)
        - скопировать публичный ключ на GitHub
        - `ssh -T git@github.com` проверить, что ключ выгружен на GitHub
        hello
        