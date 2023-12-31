---
draft: false
date: 2024-01-01
slug: how-to-connect-google-analytics
categories:
  - how-to
tags:
  - docs
---
# Инструкция по подключению и настройке Google Analytics к Just Collect
![|640](_attachments/dce9afa98e916c015e2cee50d88ebd47.png)
Это руководство поможет вам быстро подключить статистику событий из GA4 в интерфейсе Just Collect
<!-- more -->
Прежде чем выполнить подключение Google Analytics 4 к Just Collect, необходимо
[Организовать доступ сервисного аккаунта Just Collect к Google Analytics](Организовать%20доступ%20сервисного%20аккаунта%20Just%20Collect%20к%20Google%20Analytics).
Затем можно переходить к действиям перечисленным ниже.
1. Перейдите на страницу [Analytics | Home](https://analytics.google.com/analytics/web)  и откройте окно администрирования
   ![](_attachments/326b99d5a3b5582486cdcce252764d1d.png)

2. Выберите вкладку **Account access managment**
   ![](_attachments/aceace01ab1daa43e7e6104691bdda0d.png)
3. Затем добавьте сервисный аккаунт just-collect-etl-dev@just-collect-dev.iam.gserviceaccount.com с ролью **editor** или **analyst**. Теперь можно настроить экспорт статистики в интерфейс Just Collect
	![](_attachments/97aa0883dfdf15cf98e62ac47e277349.png)
4. Кликните по ссылке Property details
   ![](_attachments/8b2b7e1db6bbabf494b37fa9242b5ad2.png)
   5. Скопируйте ваш property id
      ![](_attachments/4ed10ff578f79bc3b89441cf4e0d008b.png)
   6. Вернитесь в [Just Collect](http://just-collect.ru/) на вкладку **Settings**
      ![](_attachments/785bc5484d8f1efd952592444e52279f.png)
5. Добавьте ваш **GA property id** в проект
	![](_attachments/960c935110a6e3200ece00d60eef6a19.png)
6. Перейдите на вкладку **Overview** и проверьте что статистика передается в интерфейс
	![](_attachments/62121d78f2acf2e0f730e8f118e898f0.png)