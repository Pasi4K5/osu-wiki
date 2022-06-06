---
no_native_review: true
needs_cleanup: true  # нужно заново перевести
---

# Публикация карты

[Карты](/wiki/Beatmap) могут быть загружены на сайт osu! с помощью [внутриигрового редактора](/wiki/Client/Beatmap_editor). Публикация карты позволит ей получить внимание от других игроков и даже возможно получить статус [Рейтинговой](/wiki/Beatmap/Category#ranked) или [Любимой](/wiki/Beatmap/Category#loved).

![](img/bss_warning.png "Окно Beatmap Submission System")

Нажатие на `Выгрузить на сервер...` из выпадающего списка `Файл` в редакторе (горячая клавиша: `Ctrl` + `Shift` + `U`) откроет окно **Beatmap Submission System** (***BSS***). Это окно сразу предоставляет вам список полезных ресурсов, которые могут помочь вам с вопросами по созданию карт, получить отзыв на вашу карту, а также убедиться в том, что карта готова к ранкингу. Если у вас возникли проблемы в работе BSS, изучите [проблемы с BSS](/wiki/Guides/BSS_Issues).

Если пользователь публикует новую карту, которая еще не имеется на сайте osu!, окно BSS покажет сколько еще карт он может загрузить. В том случае если карта номинирована, пользователь будет предупрежден о том, что номинированный статус будет сброшен, если он обновит карту. Если карта имеет статус Заброшенной, BSS также предупредит о том, что карта будет перемещена в Ожидающие.

## Варианты публикации

![](img/bss_submitting.png "Экран загрузки карты")

Как только пользователь нажмет на кнопку `Опубликовать новую карту` или `Обновить карту`, ему будет предоставлен выбор между категориями `Незаконченные карты` и `Законченные карты`. Незаконченные карты не могут быть номинированы, в то время как законченные могут.

Поле `От автора` даёт автору возможность пользователю ввести описание своей карты, которое отображается на ее странице на сайте. Описание поддерживает форматирование типа [BBCode](/wiki/BBCode).

В нижней части окна располагаются два переключателя. Первый предлагает `Получать уведомления при ответах`, что добавит карту в [подписки на карты](https://osu.ppy.sh/beatmapsets/watches). Второй переключатель гласит `Открыть в браузере после публикации`, что в последствии загрузит страницу карты в браузере после завершения загрузки.

## Ограничения

Карты не могут быть опубликованы, если они превышают ограничения по размеру файла или количеству сложностей. В данный момент ограничение на размер файла 5 МБ, к которому прибавляется по 10 МБ на каждую минуту карты, и может достигать 100 МБ. Ограничение по количеству сложностей на данный момент является 128.

Пользователи не могут загрузить больше карт, если они достигли своего лимита по количеству карт в категории Ожидающие. Предел зависит от количества Рейтинговых карт у пользователя, а также является ли он [саппортером](/wiki/osu!supporter). Пользователи без саппортера могут загрузить до 4 ожидающих карт, получая дополнительные слоты за каждый ранк (до 2 слотов). Пользователи имеющие статус саппортера могут одновременно загрузить до 8 карт, а также могут увеличить это число на 1 за каждый ранк (до 12) получив в итоге максимум 20 карт.

Скорость загрузки карты может меняться и зависит от измененных файлов. В том случае, если были изменены только `.osu` файлы, только они будут обработаны и обновлены. Если были затронуты любые другие файлы, то BSS загрузит все файлы в папке с картой.