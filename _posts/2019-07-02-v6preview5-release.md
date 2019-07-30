---
title: Выпущена версия V6Preview5
layout: default
---
Помимо больших LTS-версий теперь ежеквартально будут выпускаться промежуточные preview-версии. Вместе с iikoRMS 6.4 выходит [V6Preview5](https://www.nuget.org/packages/Resto.Front.Api.V6Preview5).

Поскольку ждать релиза очередной LTS-версии приходилось слишком долго (до двух лет), а возможностей ранее выпущенной стабильной LTS-версии порой не хватало, фактически многие разработчики плагинов были вынуждены использовать незафиксированный интерфейс разрабатываемой LTS-версии, после изменений в котором плагины переставали работать.
Для решения этой проблемы вводятся preview-версии. Двухлетний цикл разработки LTS-версии разбивается на 8 трёхмесячных отрезков, в конце каждого отрезка выпускается новая версия: после первых 7 отрезков — промежуточные preview-версии, в конце последнего отрезка — сама LTS-версия.

Наглядный график выпуска можно посмотреть в статье об [управлении версиями]({{ site.baseurl }}/versioning).
Описанная схема релизов заработает, начиная с V7. Для V6 первой и последней публичной preview-версией является V6Preview5, после которой выйдет сама V6.

Кстати, вместе с выпуском V6 и началом разработки V7 прекратится поддержка V4. Просто [напоминаем]({{ site.baseurl }}/2019/04/19/api-v4-support-is-coming-to-end.html).