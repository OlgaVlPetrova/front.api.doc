---
title: Уведомление об удалении сущностей
layout: default
---
Начиная с V6 события об изменении сущностей (например, `INotificationService.OrderChanged`) содержат также и тип изменения (`EntityEventType`), что позволяет узнать об удалении объекта.