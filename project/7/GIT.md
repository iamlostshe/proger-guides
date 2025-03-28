#### **Содержание:**

- **[[#Про GIT]]**
    - **[[#Установка]]**
- **[[#На этом шаге необходимо изучить]]**

#### **Про GIT**

GIT - инструмент для контроля версий, очень удобная штука для твоих проектов, позволяет:

- Работать над проектом в команде.
- Структурировать разработку.
- В случае если что-то пошло не так дает возможность вернуться к предыдущей версии.

Есть отличная [статья](https://proglib.io/p/git-for-half-an-hour) по GIT, поэтому, чтобы не повторяться просто оставлю ссылку:

https://proglib.io/p/git-for-half-an-hour

##### Установка

- **Linux**

``` bash
sudo apt-get install git
```

- **OS X** - проще всего воспользоваться **homebrew**.

``` bash
brew install git
```

- **Windows**

Можно установить **.exe** с [официального сайта](https://git-scm.com/download/win)

#### **На этом шаге необходимо изучить**

- Что такое **репозиторий** и как его создать (из под командной строки)
- Что такое **комит** и как его создать (из под командной строки)
- Что такое **ветка** и как его создать (из под командной строки)
- **.gitignore** (файл, в котором описаны файлы, которые не будут добавлены в репозиторий при коммите)
- **.env** (файл в котором хранятся секретные конфигурационные данные, например, токен для тг бота), который заносится в .gitignore
- **.env.dist** (тот же самый **.env**, но который остается в репозитории и содержит пустые поля с секретными данными, чтобы тот, кто читает твой код мог его запустить)