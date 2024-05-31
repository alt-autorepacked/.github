Репозитории c перепакованными пакетами для ALT Linux с помощью [epm](https://github.com/Etersoft/eepm).

Перепаковываются пакеты для (sisyphus/p11/p10) (arm64/x86_64)

## Добавление репозитория

Универсальная команда:

```
# epm repo add "rpm https://alt-autorepacked.slipenko.com/repo/$(epm print info -r) $(epm print info -a) addon"
```
