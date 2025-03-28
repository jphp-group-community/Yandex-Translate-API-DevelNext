# Yandex Translate API (DevelNext)

Скачать уже собранный пакет: [YandexTranslate.DN_Module.zip](https://github.com/jphp-group-community/Yandex-Translate-API-DevelNext/releases/download/0.1/YandexTranslate.DN_Module.zip)

Этот файл есть в лелизе 0.1

Подключить пакет "Yandex Translate API" и "HTTP Client".

ps. API стал платным. https://translate.yandex.ru/developers/stat

##### Пример использования:

```php
$yandex = new YandexTranslate('youre token');
$yandex->translate("Hello yandex!", "en-ru"); // Вернет переведенный текст или произойдет иключение
```

Токен можно получить [тут](https://tech.yandex.ru/keys/get/?service=trnsl)
