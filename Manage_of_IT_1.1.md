Инвариантное самостоятельно задание №1.1
> Создать репозиторий в системе контроля версий Git (на сайте GitHub) и выполнить базовый набор действий по работе с ним: 
> * выполнить операцию commit, 
> * создать ветку, 
> * выполнить клонирование репозитория, 
> * выполнить слияние двух веток. 
> * Создание отчета-репозитория о проделанной работе в GitHub, оформление с использованием разметки Markdown.


**Репозиторий** — это место, где хранятся некие данные (файлы), можно сказать, что это просто директория или же папка.

Для **создания репозитория** были выполнены следующие шаги:
1. Кликнуть на логотип GITHUB в левом углу;
2. Выбрать команду "New";
3. Прописать имя репозитория;
4. При необходимости настроить желаемые функции;
5. После завершения нажать кнопку: "Создать репозиторий".

Для **создания ветки** репозитория были выполнены следующие шаги:
1. Перейти на созданный репозиторий;
2. Щелкнуть раскрывающийся список в вверхней частисписков файлов;
3. Ввести название ветки;
4. Выбрать синюю ветку в появившемся окне и нажать "Enter" на клавиатуре.

**Клонирование репозитория**
Клонирование репозитория происходит через использования кнопки "Clone".
При нажатии на нее, происходит полное клонирование репозитория. Вам будет предложено открыть получившийся 
клон на компьютере через специальное ПО по работе с технологией GitHub. Далее можно работать с клоном в режиме 
offline и при необходимости загружать изменения на удаленный репозиторий.

Для того, чтобы выполнить **слияние двух веток**: git merge выполняет слияние текущей и указанной ветки. 
Изменения добавляются в текущую ветку. $ git merge origin/ticket_1001_branch git pull забирает изменения 
из ветки на удаленном сервере и проводит слияние с активной веткой. $ git pull origin ticket_1001_branch git pull 
отличается от git merge тем, что merge только выполняет слияние веток, а pull прежде чем выполнить слияние - 
закачивает изменения с удаленного сервера. merge удобно использовать для слияния веток в локальном репозитории, 
pull - слияния веток, когда одна из них лежит на github.
