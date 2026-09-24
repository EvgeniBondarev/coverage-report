# Studio2Prod — отчёты покрытия тестами

Этот репозиторий автоматически публикует статический HTML-отчёт о покрытии тестами проекта [Studio2Prod](https://github.com/EvgeniBondarev/Studio2Prod).

## Открыть отчёт

[Перейти к актуальному отчёту покрытия](https://evgenibondarev.github.io/coverage-report/)

Отчёт обновляется после успешного CI-прогона ветки [`local-deploy`](https://github.com/EvgeniBondarev/Studio2Prod/tree/local-deploy) в исходном репозитории.

## Что внутри

- покрытие строк и ветвей по производственным сборкам;
- разбивка по модулям, классам и исходным файлам;
- список участков с высоким риском и низким покрытием.

HTML-отчёт собирается инструментами Coverlet и ReportGenerator. Исходный код Studio2Prod и тесты остаются в приватном репозитории; здесь размещается только готовая статическая визуализация метрик.

## Ссылки

- [Исходный проект Studio2Prod](https://github.com/EvgeniBondarev/Studio2Prod)
- [CI/CD и исходный workflow](https://github.com/EvgeniBondarev/Studio2Prod/actions)
- [Документация о покрытии](https://github.com/EvgeniBondarev/Studio2Prod/blob/local-deploy/docs/test-coverage.md)
