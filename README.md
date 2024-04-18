# tgButlerBot
Telegram bot for Public admin's with payments

A few years ago, I hired a programmer who developed this bot for me, but then he disappeared, and I don't have the knowledge to further improve it. Also, I don't have much time. That's why I'm releasing the code for public access; maybe someone can finish it and make it easy to install on new servers. Currently, I have to transfer it via rsync.

Writing Docs is welcome.

What this bot has and can do:

The bot has an admin panel in Django and Dashboard. The Dashboard contains some dummy data that is not connected, while others seem to be working. Also, through the Dashboard, you can respond to messages from "Feedback"/tickets and send messages to all or specific users in bulk.

In the admin panel, you can build multi-level menus with non-inline buttons. Additionally, in the admin panel, channels are added to which the bot provides access after payment. The bot also accepts payments and tracks them via txid in USDT-TRC20, checking the amount and time. / Modest protection against abuse.

I will continue to add more, so stay tuned.


--------------------------------------------------------------------------------------------


Несколько лет назад я нанял програмиста который разработал для меня этого бота, но потом он потерялся и моих знаний не хватает для того чтобы доводить его до ума дальше. Да и времени особо нет. По этому я выкладываю код в свободный доступ, может кто-то сможет его доделать и сделать так чтобы его можно было легко устанавливать на новые серверы, сейчас мне приходится переносить его через rsync. 

Написание Docs  приветствуется

Что имеет и умеет этот бот:

У бота есть админка на Django и Dashboard 
Dashboard - половина данных просто dummy не подключены, другие вроде работают
так же через Dashboard можно отвечать на сообщения из "Обратная связь"/ тикеты и рассылать массово сообщения всем или конкретному пользователю

В админке можно выстраивать многоуровневые меню с кнопками не инлайн, так же в админке добавляются каналы в которые бот дает доступ после оплаты, так же бот умеет принимать оплату и отслеживать по txid  в USDT-TRC20 проверяет сумму и время  / скромная защита от абуза. 

Буду еще дописывать оставайтесь на связи
