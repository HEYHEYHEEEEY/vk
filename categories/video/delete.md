---
layout: default
title: Метод Video.Delete
permalink: video/delete/
comments: true
---
# Метод Video.Delete
Удаляет видеозапись со страницы пользователя.

Страница документации ВКонтакте [video.delete](https://vk.com/dev/video.delete).
## Синтаксис
``` csharp
public bool Delete(long videoId, long? ownerId = null, long? targetId = null)
```

## Параметры
+ **videoId** - Идентификатор видеозаписи. положительное число, обязательный параметр
+ **ownerId** - Идентификатор пользователя или сообщества, которому принадлежит видеозапись. Обратите внимание, идентификатор сообщества в параметре owner_id необходимо указывать со знаком "-" — например, owner_id=-1 соответствует идентификатору сообщества ВКонтакте API (club1)  целое число, по умолчанию идентификатор текущего пользователя
+ **targetId** - Идентификатор пользователя или сообщества, для которого нужно удалить видеозапись. 
Обратите внимание, идентификатор сообщества в параметре target_id необходимо указывать со знаком "-" — например, target_id=-1 соответствует идентификатору сообщества ВКонтакте API (club1)  целое число

## Результат
После успешного выполнения возвращает **true**.

## Пример
``` csharp
// Пример кода
```

## Версия Вконтакте API v.5.44
Дата обновления: 26.01.2016 14:50:41