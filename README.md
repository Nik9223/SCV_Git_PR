## 11. Работа с удаленными репозиториями. 
 Чтобы добавить новый удаленный репозиторий, выполните команду **git remote add** в терминале в катологе, в котором хранится репозиторий.

Команда *git remote add* принимает два аргумента:

* имя удаленного репозитория,например,` origin`;
* URL-адрес удаленного репозитория, например,```https://github.com/OWNER/REPOSITORY.git```.

```
$ git remote add origin https://github.com/OWNER/REPOSITORY.git
# Set a new remote

$ git remote -v
# Verify new remote
> origin  https://github.com/OWNER/REPOSITORY.git (fetch)
> origin  https://github.com/OWNER/REPOSITORY.git (push)
```