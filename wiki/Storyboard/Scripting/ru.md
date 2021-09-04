---
outdated: true
outdated_since: 048320d762fbf8472b04389126e719d219bc41f3
---

# Storyboard Scripting

![Пример скрипта в .osb](img/SBS_Base.jpg "Пример скрипта в .osb")

Помимо [встроенного редактора](/wiki/Beatmap_Editor/Design), для создания [сторибордов](/wiki/Storyboard) можно применять простой текстовый редактор (к примеру, Блокнот, [Notepad++](http://www.notepad-plus-plus.org/) или [Visual Studio Code](https://code.visualstudio.com/)). Это называется *скриптингом* (storyboarding by scripting, SBS) и позволяет более точно (до пикселей и миллисекунд) описывать время и место появления спрайтов, их поведение и так далее.

## Обзор

Для понимания основ скриптинга можно посмотреть видеообзор от [Doomsday](https://osu.ppy.sh/users/18983): [osu! - Storyboard Scripting for Beginners (12:22)](https://www.youtube.com/watch?v=UJ1YLDs-bZg "YouTube").

## Полная спецификация

*Предупреждение: сохраняйте сториборд сначала во встроенном редакторе (он оптимизирует некоторые инструкции), и только потом — в текстовом редакторе. **Сохраняйтесь чаще**, чтобы избежать случайной потери изменений.*

Скриптинг в первую очередь основывается на [официальных спецификациях](https://osu.ppy.sh/community/forums/topics/1869) и опыте создания больших сторибордов. Несмотря на наличие простых примеров, статьи про сториборды на osu! wiki — это не пошаговые гайды: они лишь объясняют, как базовые команды скриптового языка влияют на происходящее на экране в osu!.

Перед тем, как писать скрипты, ознакомьтесь с [основными терминами и понятиями скриптинга](/wiki/Storyboard/Scripting/General_Rules): это избавит от возможных проблем в будущем. Подробные описания можно найти в отдельных статьях:

- [Объекты в сторибордах](/wiki/Storyboard/Scripting/Objects)
- [Команды сторибордов](/wiki/Storyboard/Scripting/Commands)