---
title: Введение
---

# **Добро пожаловать!**  

Перед вами то, что я, [Groosha](https://mastergroosha.github.io/), называю книгой по созданию Telegram-ботов на языке Python с помощью 
фреймворка [aiogram 3.x](https://github.com/aiogram/aiogram). Её \[книгу\] можно воспринимать как учебный материал, 
обращаясь к отдельным главам по необходимости, но для первого прочтения рекомендую это делать в том порядке, в котором 
указаны главы слева от этого текста.

Возможно, вы ранее читали [первую версию](https://mastergroosha.github.io/telegram-tutorial/), 
написанную в 2015-2017 годах для библиотеки [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI). С тех пор 
много чего изменилось как в Python, так и в Bot API, да и я, как программист, стал сильнее. В 2019 году перешёл на 
aiogram, о чём не жалею, и написал гайд по ботам уже под aiogram, но версии 2.x.

В этой, обновлённой версии книги, мы будем использовать фреймворк aiogram 3.х, который на момент создания этого текста 
находится в состоянии beta-версии, однако уже вполне готовой для повседневного использования.

**Для кого эта книга?**  
Предполагается, что вы знакомы с программированием в целом и языком Python в частности, знаете, что такое "venv" и "pip", 
а также способны понять и исправить "детские" ошибки вроде _SyntaxError_ и _IndentationError_. Найдите в интернете пару
курсов по Python, пройдите их, а лишь затем принимайтесь за написание ботов, сэкономите себе время и нервные клетки.

Во всех главах в качестве операционной системы мы будем использовать что-нибудь семейства GNU/Linux, 
например, [Ubuntu](https://ubuntu.com/), Python 3.9 (в Virtual Environment) и среду разработки 
[PyCharm](https://www.jetbrains.com/ru-ru/pycharm/download/), впрочем, не возбраняется и [Visual Studio Code](https://code.visualstudio.com/).
При этом пользователи Windows не в пролёте: всё, что касается кода, будет спокойно работать и у вас, а для специфичных вещей
вроде systemd вы можете использовать Ubuntu в [VirtualBox](https://www.virtualbox.org).

Текст книги и исходные тексты в [соответствующем репозитории](https://github.com/MasterGroosha/aiogram-3-guide) 
полностью бесплатны, издаются под лицензией MIT и доступны любому для скачивания, модификации и использования в любых целях. 

**Донаты**  
На написание и актуализацию книги я потратил очень много времени и сил. Если вы из России и хотите 
отблагодарить автора материально, можете сделать это через [Ю.Money](https://yoomoney.ru/to/41001515922197) 
(пожалуйста, указывайте в комментариях, что это за книгу).  
На всякий случай уточню, что любое пожертвование является **добровольным и не даёт никаких преимуществ**, кроме плюсика в карму.

**Благодарности**  
За то, что эта книга в её текущем виде возникла и существует по сей день, спасибо создателю aiogram 
[Alex JRootJunior](https://github.com/JrooTJunior), чатику [@aiogram_ru](https://t.me/aiogram_ru), 
моему собственному [чатику](https://t.me/joinchat/TsftDfnevFLQS1ts), а также вам, дорогим читателям!