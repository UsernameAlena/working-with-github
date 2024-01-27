# working-with-github
Задание от Практикума по созданию репозитория и описания с помощью файла README.md

# Как работать с GitHub

## Рассмотрим несколько основных команд для добавления коммитов

**Коммитом** называют фиксацию состояния файлов. От английского commit — совершать, фиксировать. Сделать коммит — значит сохранить текущую версию файла. 
Выполняется это командой **git commit** c ключом **-m** («сообщение»), который присваивает коммиту сообщение. Обычно в нём поясняется, в чём именно состояли изменения. Сообщение пишется после ключа в кавычках. <br>

```html
git commit -m "Мой первый коммит." 
```

Перед тем, как делать коммит, убедитесь, что Git понимает, какие именно файлы вы хотите сохранить и какую версию. Поэтому для начала используйте комманду **git add** с указанием необходимого файла или используйте **git add --all**, чтобы Git отслеживал состояние всех файлов.

```html
git add NeedFile.txt
or
git add --all
```
 
Получается, что сначала команда add сообщает Git, какие именно файлы вы хотите сохранить, а затем с помощью команды commit происходит само сохранение. <br>

Чтобы увидеть коммиты в репозитории, введите команду **git log** (в переводе «журнал записей»).<br>

Используйте команду **git push**, чтобы отправить коммит на удаленный репозиторий. 

