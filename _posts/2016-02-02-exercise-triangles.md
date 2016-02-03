---
title:  "Что за треугольник?"
categories: JavaScript
date:   2016-02-02 12:50:58 +0300
type: exercise
identifier: exercise-triangles

description: "Всего существует 3 вида треугольников: остроугольные, прямоугольные и тупоугольные. В задаче требуется написать функцию, которая будет тестировать треугольники и сообщать, к какому виду они относятся."
---

Напишите функцию `triangle`, которая тестирует переданный ей треугольник и возвращает его тип. Треугольники бывают: остроугольными, прямоугольными и тупоугольными. Функция принимает три числа, которые соответствуют длине каждой стороны.
{% highlight javascript %}
triangle(2, 4, 6); // Не существует
triangle(7, 3, 2); // Не существует
triangle(8, 5, 7); // Остроугольный
triangle(3, 4, 5); // Прямоугольный
triangle(7, 12, 8); // Тупоугольный
{% endhighlight %}

### Решение
Будет опубликовано завтра вечером