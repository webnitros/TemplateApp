## TemplateApp

Заготовка для создания пакетов для composer

### Настройка папок

В phpStorm настроить "Directories" для папок

```http request
src = App\
tests = App\Tests\
```

## Подключения в composer.json

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/webnitros/app"
    }
  ],
  "require": {
    "webnitros/app": "^1.0.0"
  }
}
```

# phpunit

Переменные для env задаются в файле phpunit.xml
