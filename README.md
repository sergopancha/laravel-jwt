## Демо JWT-аутентификация в Laravel 9

JWT: JSON Web Token

Реализация через [tymondesigns/jwt-auth](https://github.com/tymondesigns/jwt-auth).

Описание API в swagger (OpenAPI) формате в файле [openapi.yaml](openapi.yaml).
Структура YAML протестирована в [https://editor.swagger.io/](editor.swagger.io)

Способ документирования для автоматической генерации через laravel может быть реализован пакетом [https://github.com/DarkaOnLine/L5-Swagger](github.com/DarkaOnLine/L5-Swagger).
В этому случае php-код перегружается @OAi-тэгами в описании методов и свойств, которые необходимы для программного (через консольную artisan команду)
генерирования страницы в openApi формате.

В данном проекте был выбран способ yaml-вёрстки, чтобы не нагружать программный код комментариями
