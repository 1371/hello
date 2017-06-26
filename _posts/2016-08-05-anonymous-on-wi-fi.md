---
layout: post
date: 2016-08-05 14:50:00 +0300
title: "Анонимность в Wi-Fi сетях"
description: Маскируем свое устройство при взломе Wi-Fi. Несколько практических советов по анонимизации устройства в беспроводных сетях.
keywords: wi-fi, анонимность, смена mac
mood: happy
comments: true
category:
- security
tags:

---

<figure>
    <img src="http://dubkov.xyz/assets/img/wi-fi-free.png" alt="Wi-Fi" />
</figure>

Как обезопасить свой компьютер при взломе и нахождении (работе и подключении) в чужой сети Wi-Fi? Я решил поделиться некоторыми приемами для маскировки компьютера, при которых компьютер будет иметь поддельные данные в логах и интерфейсе соединений большинства роутеров. 
<!--more-->
<h2>Анонимность при взломе Wi-Fi</h2>
<h3>Меняем MAC и маскируемся под iPhone или Android</h3>

<blockquote>Данные практические советы актульаны для любых компьютеров с операционной системой Windows</blockquote>

Всем прекрасно известно, как определить чужое устройство в логах или консоли роутера. Абсолютно любой, даже самый древний роутер, имеет в админке раздел мониторинга поключившихся устройств в рельном времени.
Что обычно известно роутеру о подключившимся к нему устройствах? Это уникальный MAC-адрес устройства и его имя.
Нас интересует беспроводное подключение, по большому счету эти приемы подойдут и для других подключений.

Для того, чтобы остататься неизвестным и безнаказанным, необходимо предоствить роутеру поддельные данные о своем устройстве.

Нам необходимо:

* Изменить MAC-адрес устройства
* Изменить имя компьютера

Смену уникального MAC-адреса, очень просто осуществить с помощью утилиты TMAC. 
Устанавливаем утилиту, ищем свое устройство, с помощью которого осуществляется подключение к роутеру, и нажатием одной кнопки изменяем MAC-адрес.
Для пущей уверенности, можно изменить адреса всех имеющихся на устройстве сетевых карт и беспроводных адаптеров.

![Смена MAC-адреса](/assets/img/mac-changer.png)

Многие, наверняка замечали, как называются мобильные устройства в логах роутера (пример на изображении ниже). И наша задача состоит в том, чтобы наш пк или ноутбук отображался имеено так.
Как это сделать? Заходим в свойства компьютера и просто изменяем название компьютера.

![Имя компьютера](/assets/img/rename-pc.png)

Теперь компьютер будет отображаться в логах роутера с фейковым MAC и названием, как у смартфона.

![Админка роутера](/assets/img/admin-router.png)
