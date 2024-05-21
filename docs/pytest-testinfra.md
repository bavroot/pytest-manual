[pypi](https://pypi.org/project/pytest-testinfra/)
[github](https://github.com/pytest-dev/pytest-testinfra)

Плагин для pytest позволяющий тестировать "инфраструктуру"

Точка входа - использование фикстуры [host](https://github.com/pytest-dev/pytest-testinfra/blob/main/testinfra/plugin.py#L35)
- Без инициализации параметрами коммандной строки - работает с локальным хостом
- Поддерживает различные backendы (testinfra/backend) - то где будет использоваться
- Для хоста становяться доступны все модули из testinfra/modules, осталось правильно вызвать их, методы смотрим в документации

==Есть проблема с поддержкой python'a - теперь поддерживает начиная с 3.9==



