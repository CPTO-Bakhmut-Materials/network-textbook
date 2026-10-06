---
title: Головна
nav_order: 0
---

# Вступ до Інтернету: архітектура та протоколи

_Автор — [Peyrin Kao](https://peyrin.github.io), на основі лекцій [Sylvia Ratnasamy](https://www2.eecs.berkeley.edu/Faculty/Homepages/ratnasamy.html), [Rob Shakir](https://rob.sh/) та інших._

Це конспект курсу [CS 168: Introduction to the Internet](https://cs168.io/) в [UC Berkeley](https://eecs.berkeley.edu/).

Ось офіційний опис курсу:

<p class="blue">
	Цей курс є вступом до архітектури Інтернету. Ми зосередимося на концепціях і фундаментальних принципах проєктування, які забезпечили масштабованість і надійність Інтернету, а також оглянемо різні протоколи та алгоритми, що використовуються в межах цієї архітектури. Теми охоплюють розбиття на рівні, адресацію, внутрішньодоменну маршрутизацію, міждоменну маршрутизацію, надійну доставку, керування перевантаженням, основні протоколи (наприклад, TCP, UDP, IP, DNS і HTTP) та мережеві технології (наприклад, Ethernet, бездротові мережі).
</p>


## Застереження: бета-версія

Ці матеріали не проходили вичитку. Імовірно, вони містять помилки.

Якщо ви студент CS 168 у Берклі, то в разі будь-яких розбіжностей правильним джерелом істини є офіційні лекції курсу.


## Діаграми

У цьому українському перекладі текст на діаграмах залишено англійською мовою.

[Версії цих матеріалів у вигляді слайдів із діаграмами доступні тут.](https://drive.google.com/drive/folders/13RnAGH1OrsOVvXdmQC73WkmoVD9r5lzd)


## PDF-версія

[Ці матеріали доступні у форматі PDF тут.](https://drive.google.com/file/d/1PPSkHOnFsOI9noWWMuJnaxmsOzM6RIKX/view?usp=sharing)

PDF-версія не завжди актуальна. Востаннє її оновлювали в листопаді 2024 року.


## Виправлення

Станом на осінній семестр 2024 року цей підручник активно підтримується та оновлюється.

Якщо ви помітили частини, які потребують виправлення, будь ласка, створіть issue на GitHub [тут](https://github.com/berkeley-cs168/textbook/issues).


## Вихідний код і журнал змін

Вихідний код підручника та журнал усіх змін [доступні на GitHub](https://github.com/berkeley-cs168/textbook).


## Ліцензія

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Ліцензія Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Цей <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">твір</span> ліцензовано за ліцензією <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
