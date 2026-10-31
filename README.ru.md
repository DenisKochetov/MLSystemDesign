# Проектирование систем машинного обучения

> Практическая подборка сквозных дизайн-документов ML-систем, шаблонов и чек-листов к книге [*Machine Learning System Design*](https://www.manning.com/books/machine-learning-system-design) Валерия Бабушкина и Арсения Кравченко (Manning).

[English](README.md) · [Глоссарий](GLOSSARY.ru.md) · [О переводе](TRANSLATION.ru.md)

[![Лицензия: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Принимаем PR](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Книга](https://img.shields.io/badge/book-Manning-blue.svg)](https://www.manning.com/books/machine-learning-system-design)

В репозитории собраны структура и примеры дизайн-документов, на которые можно опираться при работе над собственными системами. Материалы дополняют книгу: показывают на конкретных примерах, как выглядит продуманный дизайн ML-системы.

## Структура репозитория

| Путь | Содержание |
| --- | --- |
| [templates/](templates/) | Шаблоны и рекомендации |
| [templates/basic_ml_design_doc.ru.md](templates/basic_ml_design_doc.ru.md) | Русский шаблон дизайн-документа |
| [templates/design_doc_checklist.ru.md](templates/design_doc_checklist.ru.md) | Русский чек-лист ревью |
| [Design_Doc_Examples/Examples/EN/](Design_Doc_Examples/Examples/EN/) | Примеры на английском, вдохновлённые реальными задачами |
| [Design_Doc_Examples/Mock/EN/](Design_Doc_Examples/Mock/EN/) | Учебные примеры на английском |
| [skills/](skills/) | Скиллы для AI-агентов; пока на английском |
| [BookOutline.ru.md](BookOutline.ru.md) | Русский конспект глав и основных понятий |
| [GLOSSARY.ru.md](GLOSSARY.ru.md) | Англо-русский глоссарий с пояснениями |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Правила участия на английском |
| [LICENSE](LICENSE) | Лицензия MIT |

## С чего начать

1. **Только знакомитесь с ML System Design?** Начните с [конспекта глав](BookOutline.ru.md). Затем изучите полный пример [прогнозирования спроса в ретейле](Design_Doc_Examples/Examples/EN/Retail_Demand_Forecasting_Design.md) и возьмите [шаблон](templates/basic_ml_design_doc.ru.md) для своего проекта.
2. **Пишете собственный дизайн-документ?** Скопируйте [шаблон](templates/basic_ml_design_doc.ru.md), заполните разделы и пройдите [чек-лист](templates/design_doc_checklist.ru.md) перед отправкой на ревью. Сверяйтесь с примерами по глубине проработки и стилю.
3. **Ищете примеры?** В [Design_Doc_Examples/](Design_Doc_Examples/) есть документы для разных областей и уровней сложности: [прогнозирование спроса](Design_Doc_Examples/Examples/EN/Retail_Demand_Forecasting_Design.md) и учебный [RAG-чат с версиями документов](Design_Doc_Examples/Mock/EN/RAG_Chat_With_Doc_Versions/RAG_Chat_With_Doc_Versions_Design.md). Эти примеры пока не переведены.

## Скилл для ревью дизайна

Скилл [`ml-system-design-review`](skills/README.md) применяет подход книги к проверке ML/AI-систем. Он выдаёт заключение, оценки с учётом стадии проекта, список проблем по серьёзности и план исправлений. Проверять можно дизайн-документ, репозиторий или оба источника вместе.

```bash
npx skills add ML-SystemDesign/MLSystemDesign
```

Подробности и инструкции — в [skills/README.md](skills/README.md). Скиллы в этой версии остаются на английском.

## Шаблоны

1. [basic_ml_design_doc.ru.md](templates/basic_ml_design_doc.ru.md) — шаблон с вопросами для каждого раздела дизайн-документа.
2. [design_doc_checklist.ru.md](templates/design_doc_checklist.ru.md) — чек-лист для проверки документа перед согласованием.

## Как разделы шаблона связаны с книгой

| Раздел шаблона | Главы книги |
| --- | --- |
| I. Постановка задачи | 2. Есть ли проблема?; 3. Предварительное исследование; 4. Дизайн-документ |
| II. Метрики и функции потерь | 5. Функции потерь и метрики |
| III. Датасет | 6. Сбор датасетов |
| IV. Схема валидации | 7. Схемы валидации |
| V. Базовое решение | 8. Базовое решение |
| VI. Анализ ошибок | 9. Анализ ошибок |
| VII. Пайплайн обучения | 10. Пайплайны обучения |
| VIII. Признаки | 11. Признаки и их конструирование |
| IX. Оценка и представление результатов | 12. Оценка и представление результатов |
| X. Интеграция | 13. Интеграция |
| XI. Мониторинг | 14. Мониторинг и надёжность |
| XII. Обслуживание запросов и инференс | 15. Обслуживание запросов и оптимизация инференса |
| Ответственность на всех этапах | 16. Ответственность и сопровождение |

## Участие в проекте

Правила участия описаны в [CONTRIBUTING.md](CONTRIBUTING.md). Особенно полезны новые примеры, улучшения шаблонов, документация практик, ревью и обратная связь.

## Лицензия

Репозиторий распространяется по лицензии MIT. Подробности — в [LICENSE](LICENSE).

## Благодарности

- Авторам [*Machine Learning System Design*](https://www.manning.com/books/machine-learning-system-design), на чьих идеях основаны материалы.
- Участникам, подготовившим примеры и шаблоны.
- ML-сообществу за отзывы и улучшения.
