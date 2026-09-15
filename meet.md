# Pocket Rocket Meet - Privacy Policy

Effective date: September 15, 2026

Pocket Rocket Meet ("the extension") is a Chrome extension that saves Google Meet captions as text transcripts and, when you ask for it, analyzes them with an AI service you choose. This policy explains what data the extension handles and where it goes.

Русская версия ниже.

## Summary

- Transcripts and settings stay in your browser. The developer has no servers and never receives your data.
- There are no accounts, analytics, tracking or ads.
- Transcript text leaves your browser only when you press Analysis, and only to the AI service you configured yourself.

## Data the extension handles

1. Call transcripts. While you are in a Google Meet call that is being recorded, the extension reads the captions of that call: speaker names, spoken text, timestamps, the meeting title and the meeting code.
2. Settings. Recording preferences, caption and interface language, the analysis prompt.
3. AI service credentials, if you set up AI analysis. The service address, model name, API key, or sign-in tokens when you sign in with an OpenAI account.
4. Folder access, if you choose a folder for .txt files. Chrome keeps a handle to that folder so the extension can write files into it.

## Where it is stored

All of this is stored locally on your device, in the extension storage of Chrome (chrome.storage.local and IndexedDB). It is not synced to other devices and is not sent to the developer.

Transcript files are written only where you tell the extension to write them: the Downloads folder when you press Download, or the folder you picked in the settings.

## When data leaves your browser

Only in these cases, and only after your action:

- AI analysis. When you press Analysis, the transcript text and the analysis prompt are sent directly from your browser to the AI service you configured: for example OpenAI (api.openai.com, or chatgpt.com and auth.openai.com when you sign in with an OpenAI account), Anthropic (api.anthropic.com), Google Gemini (generativelanguage.googleapis.com), OpenRouter, Ollama, a local gateway or another OpenAI-compatible address you entered. Your API key or sign-in token is sent to that same service to authorize the request. The privacy policy of that service applies to the data it receives.
- Checking the connection or loading the model list sends your key or token to the configured service, without transcript text.

The extension asks Chrome for access to the address of the AI service only when you set it up, and does not contact any other address.

## What the extension does not do

- It does not sell or transfer your data to third parties, except to the AI service you chose, as described above.
- It does not use or transfer data for purposes unrelated to its single purpose, and not to determine creditworthiness or for lending.
- It does not collect browsing history, and it runs only on meet.google.com.

The use of information received by the extension adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Retention and deletion

Transcripts stay until you delete them in the history page. AI analysis results are stored together with their transcript. Signing out removes the sign-in tokens, clearing the key field removes the key. Removing the extension from Chrome deletes all of its stored data. Files you saved to disk stay where you saved them.

## Children

The extension is not directed at children under 13 and does not knowingly collect their data.

## Changes

If this policy changes, the new version is published at the same address with a new effective date.

## Contact

pocketrocket@verych.ru

---

# Pocket Rocket Meet - Политика конфиденциальности

Дата вступления в силу: 15 сентября 2026

Pocket Rocket Meet (далее расширение) это расширение Chrome, которое сохраняет субтитры Google Meet в текстовые стенограммы и по вашему запросу анализирует их выбранным вами AI-сервисом. Здесь описано, какие данные обрабатывает расширение и куда они попадают.

## Коротко

- Стенограммы и настройки остаются в вашем браузере. У разработчика нет серверов, и он не получает ваши данные.
- Нет аккаунтов, аналитики, отслеживания и рекламы.
- Текст стенограммы покидает браузер только когда вы нажимаете Анализ, и только в тот AI-сервис, который вы сами настроили.

## Какие данные обрабатываются

1. Стенограммы звонков. Во время записываемого звонка в Google Meet расширение читает субтитры этого звонка: имена говорящих, текст, время реплик, название и код встречи.
2. Настройки. Параметры записи, язык субтитров и интерфейса, промпт анализа.
3. Данные доступа к AI-сервису, если вы настроили анализ. Адрес сервиса, название модели, API-ключ или токены входа, если вы вошли через аккаунт OpenAI.
4. Доступ к папке, если вы выбрали папку для .txt. Chrome хранит ссылку на папку, чтобы расширение могло записывать в неё файлы.

## Где хранятся

Всё это хранится локально на вашем устройстве, в хранилище расширения Chrome (chrome.storage.local и IndexedDB). Данные не синхронизируются с другими устройствами и не передаются разработчику.

Файлы стенограмм записываются только туда, куда вы укажете: в папку загрузок по кнопке Скачать или в папку, выбранную в настройках.

## Когда данные покидают браузер

Только в этих случаях и только после вашего действия:

- AI-анализ. По кнопке Анализ текст стенограммы и промпт отправляются из браузера напрямую в настроенный вами AI-сервис: например OpenAI (api.openai.com, или chatgpt.com и auth.openai.com при входе через аккаунт OpenAI), Anthropic (api.anthropic.com), Google Gemini (generativelanguage.googleapis.com), OpenRouter, Ollama, локальный шлюз или другой OpenAI-совместимый адрес, который вы ввели. Для авторизации запроса туда же отправляется ваш API-ключ или токен. К полученным данным применяется политика конфиденциальности этого сервиса.
- Проверка подключения и загрузка списка моделей отправляют в настроенный сервис ключ или токен, без текста стенограмм.

Доступ к адресу AI-сервиса расширение запрашивает у Chrome только при его настройке и не обращается ни к каким другим адресам.

## Чего расширение не делает

- Не продаёт и не передаёт ваши данные третьим лицам, кроме выбранного вами AI-сервиса, как описано выше.
- Не использует и не передаёт данные в целях, не связанных с его единственным назначением, в том числе для оценки кредитоспособности.
- Не собирает историю браузера и работает только на meet.google.com.

Использование полученной расширением информации соответствует Chrome Web Store User Data Policy, включая требования Limited Use.

## Хранение и удаление

Стенограммы хранятся, пока вы не удалите их на странице истории. Результаты AI-анализа хранятся вместе со стенограммой. Выход из аккаунта удаляет токены, очистка поля ключа удаляет ключ. Удаление расширения из Chrome удаляет все его данные. Файлы, сохранённые на диск, остаются там, куда вы их сохранили.

## Дети

Расширение не предназначено для детей младше 13 лет и сознательно не собирает их данные.

## Изменения

Если политика изменится, новая версия будет опубликована по тому же адресу с новой датой.

## Контакт

pocketrocket@verych.ru
