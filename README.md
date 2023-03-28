# JavaScript Lecture 5

![](https://avatars.mds.yandex.net/i?id=9f7c2fb57f57220b3049505c450f653cd5c3c008-6321690-images-thumbs&n=13)

## Table of Contents

> - OBJECT
>
> - Destructuring
>
> - Spread
>
> - THIS
>
> - New Date()

# What is Object in JavaScript?

> Конструктор Object создаёт объект-обёртку.

## Create object

> Объект JavaScript — это непримитивный тип данных, который позволяет вам хранить несколько коллекций данных

![](https://avatars.mds.yandex.net/i?id=1eca27800473139d3c5d52be8462c6cf6358feff-7664089-images-thumbs&n=13)

## Methods object

> Object.entries()

![](./%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20100949.png)

> Object. keys()

![](./%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20101114.png)

> Object. values()

![](./%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20101228.png)

# What is Destructuring and Spread in JavaScript?

## Destructuring and Spread in Object

> Синтаксис деструктурирующего присваивания представляет собой выражение JavaScript, которое делает его можно распаковать свойства объекта в отдельные переменные

![](./%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20101813.png)

# What is keyword "this" in JavaScript?

## How the this keyword works

> Поведение ключевого слова this в JavaScript несколько отличается по сравнению с остальными языками. Имеются также различия при использовании this в строгом и нестрогом режиме.

![](./%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20102123.png)

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20102220.png)

> This НЕ переменная. Это ключевое слово. Вы не можете изменить значение этого

# What is new Date() in JavaScript?

## Data and Time

> Создаёт экземпляр объекта Date, представляющего собой момент времени. Объект Дата содержит число миллисекунд прошедших с 1 января 1970 г. UTC

## Data and Time

> - new Date()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20102916.png)

> - new Date(milliseconds)

> New Date(milliseconds) - количество миллисекунд, прошедших с 1 января 1970 года GMT+0. new Date(datestring) - Если единственный аргумент – строка, используется вызов Date.parse для чтения даты из неё.

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20103441.png)

## Data and Time

> - new Date(date string)

> Конструктор Date() создает объекты Date. При вызове в качестве функции она возвращает строку, представляющую текущее время.

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20103934.png)

## Data and Time

> - new Date(year,month,day,hours,minutes,seconds,milliseconds)

> new Date(..month) создает новый объект даты с указанной датой и временем.Например

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20104942.png)

## Data and Time

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20105133.png)

## Data and Time

> - now()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20110047.png)

> - getFullYear()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20105657.png)

> - getMonth()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20110300.png)

## Data and Time

> - getDate()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20110749.png)

> - getDay()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20111031.png)

> - getHours()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20110853.png)

## Data and Time

> - getMinutes()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20111345.png)

## Data and Time

> - setDate()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20111831.png)

> - setMonth()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20112229.png)

> - setFulYear()

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20112533.png)

![](%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-03-28%20112617.png)
