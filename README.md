# Что нужно для работы
Для работы Вам потребуется [Git](https://git-scm.com/downloads).

(нажмите для перехода на страницу загрузки)

____

## Начало работы
Сперва хочу подметить, что Вам необязательно создавать папку. Git сам за Вас создаст и загрузит все нужные файлы.

### Шаг 1 
Для начала зайдите на Github в [репозиторий с проектом](https://github.com/maripetrova/tele-hub) и справа вверху нажмите кнопку _Fork_.
![Пикча](https://teletype.in/files/67/5f/675f9214-9a01-433a-a51f-1153642f9169.png "Где здесь Fork")

У вас создастся копия этого репозитория.

### Шаг 2
Как только у Вас создался форк, скопируйте ссылку на этот репозиторий.
![Пикча](https://teletype.in/files/65/be/65bef9f5-763c-4a1c-963d-a46b56cd74de.png "Да")

### Шаг 3
Откройте терминал (в Windows — командная строка, в MacOS — так и называется терминал), и перейдите в нём в нужную Вам папку.
```
cd <путь к файлу>
```

Введите в терминал следующую команду:
```
git clone <ссылка на репозиторий>
```

У вас склонируются все файлы.

____

## Принцип работы
### Шаг 1
__ВСЕГДА перед работой нужно актуализировать все файлы следующей командой__:
```
git pull https://github.com/maripetrova/tele-hub.git master
```

### Шаг 2
Для того, чтобы отправить свои изменения на проверку, напишите следующие команды:
```
git pull https://github.com/maripetrova/tele-hub.git master
git add .
git commit -am "подробный комментарий о ваших изменениях"
git push origin master
```

### Шаг 3
Далее Вам надо зайти на СВОЙ репозиторий Github и зайти во вкладку _Pull requests_ и нажать на _New pull request_:

![Пикча](https://teletype.in/files/dd/6a/dd6aaec5-a120-457a-a3e2-d140f73a6570.png "Да")

### Шаг 4
Нажмите _Create pull_ request.

![Пикча](https://teletype.in/files/e2/6b/e26b5937-ff5c-4d10-8f91-52bb184677e5.png "Да")

### Шаг 5
Распишите ПОДРОБНО что вы изменили.

![Пикча](https://teletype.in/files/98/f0/98f0f868-ca57-4807-a362-68d6623b224e.png "Да")

И нажмите _Create pull request_.

## Описание команд
```
git pull
```

Обновляет файлы до последних изменений.
```
git add .
```

Находит новые файлы и подготавливает их к пушу.
```
git commit
```

Сравнивает Ваши файлы с репозиторием, находит изменения, и фиксирует коротким комментарием.
```
git push
```

Ссылка в Сибирь.
