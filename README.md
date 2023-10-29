# Небольшой конспектик 


## Схема создания репозитория


```mermaid
graph LR;
git init             -- "initialization"               --> git add;
git add              -- "the file has been prepared"   --> git commit -m message;
git commit -m text -- "sending to github"            --> git push;
```


---

## Выделение кода


```bash
 _..._ #- _курсив_

__...__ #- __жирный__
```

---

## Локальный репозиторий


_HEAD_ - указывает на коммит, который сделан последним

_git init_ - инициализация репозитория  

_rm -rf .git_ - удаление подпапки git:  

    1. _-r_ удаляет все папки рекурсией  

    2. _-f_ удаляет без вопросов  

_git add_ - готовит файл к сохранению в репозиторий(-all все файлы)  

_git commit -m "message"_ - коммит с сообщением, то есть сохранение    

_git log_ - показыает историю 

---

## Github


_git remote add origin_ - привязать удаленный репозиторий  

    1. переходим на github и создаём репозиторий  

    2. копируем код SSH   

**Ctrl+Shift+V** - копирование  

_git remote -v_ - показывает что репозитории связаны  

_git push -u origin main_ - первый вызов push   

_git push_ - последующие вызовы  

