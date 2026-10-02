# Studio2Prod — отчёты покрытия тестами

Этот репозиторий автоматически публикует статический HTML-отчёт о покрытии тестами проекта [Studio2Prod](https://github.com/EvgeniBondarev/Studio2Prod).

## Актуальная сводка

<!-- COVERAGE_DASHBOARD:START -->
## Текущая метрика

| Метрика | Значение |
| --- | ---: |
| Line coverage | **14.4%** (43449 из 301427) |
| Branch coverage | **22.6%** (20088 из 88540) |
| Сборки / классы / файлы | 5 / 2771 / 1985 |
| Период измерения | 10/02/2026 - 08:17:58 - 10/02/2026 - 08:20:42 |

## Динамика покрытия

```mermaid
xychart-beta
    title "Покрытие тестами, %"
    x-axis ["24.09", "25.09", "26.09", "27.09", "01.10", "02.10"]
    y-axis "Покрытие" 0 --> 100
    line [10.9, 12.6, 12.1, 12.9, 14.4, 14.4]
    line [14.6, 18.1, 18.2, 20.2, 22.6, 22.6]
```

_Первая линия — строки, вторая — ветви. Хранится до 90 последних измерений._
<!-- COVERAGE_DASHBOARD:END -->

## Открыть подробный HTML-отчёт

[Перейти к актуальному отчёту покрытия](https://evgenibondarev.github.io/coverage-report/report/)

Сводка и график обновляются ежедневно после ночного CI-прогона ветки [`local-deploy`](https://github.com/EvgeniBondarev/Studio2Prod/tree/local-deploy). Полный HTML-отчёт доступен по ссылке выше.

## Что внутри

- покрытие строк и ветвей по производственным сборкам;
- разбивка по модулям, классам и исходным файлам;
- список участков с высоким риском и низким покрытием.

HTML-отчёт собирается инструментами Coverlet и ReportGenerator. Исходный код Studio2Prod и тесты остаются в приватном репозитории; здесь размещается только готовая статическая визуализация метрик.

## Ссылки

- [Исходный проект Studio2Prod](https://github.com/EvgeniBondarev/Studio2Prod)
- [CI/CD и исходный workflow](https://github.com/EvgeniBondarev/Studio2Prod/actions)
- [Документация о покрытии](https://github.com/EvgeniBondarev/Studio2Prod/blob/local-deploy/docs/test-coverage.md)
