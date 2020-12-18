[![CodeFactor](https://goreportcard.com/badge/github.com/averyanalex/nnm)](https://www.codefactor.io/repository/github/averyanalex/garold)
# NNM
Ne Nuzhno Messenger.
Что это такое?
Продвинутый мессенджер, в котором не просто групповые чаты
и админы, а группы с любым колчеством чатов, закреплением
сообщений, настриваемыми правами и ролями пользователей
(на конкретном сервере). Так же должны быть личные сообщения.
По факту, свободный клон Discord.
Данный проект является Just Fo Fun свободной заменой Discord.
Оно будет (ну или нет) состоять из: API на GO и фронтенды.
Сначала тестовый CLI, потом чего-нибудь на QT. Данные будет
хранить в MySQL, работать в Docker, наверное. Сначала напишем
храение сообщений, их отправку и получение (вообще без
авторизаций). Возможно система "уведомлений" о сообщениях
будет работать на MQTT.
# Как это работает
Во фронтенде есть менеджмень аккаунтов. Можно зайти в
несколько аккаунтов на нескольких серверах. По умолчанию
предлагается войти/зарегестрироваться на официальном.
На каждом сервере есть ЛС и группы (сервера дискорда).
В группах чаты. Так же группа имеет роли и возможность
назначать пользоватеям роли с различными правами.
