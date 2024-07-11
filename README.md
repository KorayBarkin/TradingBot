# tradingview-webhook


python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python app.py

TR

-- Binance api key alıp margin ve futures check boxlarını aktif etmeniz gerekiyor.
-- Telegramdan bot oluşturduktan sonra mesajlaşabilmek için bota ilk önce bir mesaj yazmanız gerekiyor (/start dedikten sonra)
-- Kodun içerisindeki usdt variable'ı sizin açacağınız pozisyonun büyüklüğünü gösterir örneğin usdt = 300 yapıp change leverage'dan kaldıracı da 10x yaparsanız 30 dolarlık bir pozisyon açılır 30x10 = 300 şeklinde işliyor.
-- isIsolated kısmı izole işlem açmak istiyorsanız true olarak kalmalı eklemezseniz pozisyonunuz cross açılacaktır.

ENG

--Binance API Key and Enabling Margin and Futures Checkboxes:
You need to obtain a Binance API key and enable the margin and futures checkboxes.

--Creating a Bot on Telegram:
After creating a bot on Telegram, you need to send an initial message to the bot to start messaging (type /start first).

--USDT Variable in the Code:
The usdt variable in the code indicates the size of the position you will open. For example, if you set usdt = 300 and the leverage is set to 10x from the change leverage, a position of 30 dollars will be opened, calculated as 30x10 = 300.

--Isolated Trading:
The isIsolated part should remain true if you want to open an isolated trade. If you do not include it, your position will be opened as cross.
