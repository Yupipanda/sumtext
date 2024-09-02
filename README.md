<h1 align="center">sumtext</h1>
<h3><p align="center">Консольная утилита краткого перессказа статей с ссылок или текста.</p></h3>
<p>Данная утилита является форком проекта <a href="https://github.com/tpai/summary-gpt-bot">Summary GPT Bot.</a></p>
<p>Она использует ИИ llama через обращение к API серверу <a href="https://console.groq.com/keys">Groq</a> "В РФ без впн или прокси не работает"</p>


Перед началом работы клонируйте репозиторий утилиты:

```sh
git clone https://github.com/Yupipanda/sumtext.git
cd sumtext
```

А дальше вам нужно получить API ключ в Groq(или можете переписать функцию call_gpt_api под свою задачу), который вам нужно вставить в файле sumtext.py в 5 строке и сохранить:
```python
aiapi = "<ВАШ КЛЮЧ GROQ API>"
```


Пример использования:
```sh
pip install -r requirements.txt
python sumtext.py 'ссылка на сайт со статьей, которую нужно сократить'
```
Или:
```sh
pip install -r requirements.txt
python sumtext.py 'текст, который нужно сократить'
```
[Telegram Канал](https://t.me/yupipanda_channel)
