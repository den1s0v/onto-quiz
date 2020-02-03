# onto-quiz
Semantic technologies in domain-specific teaching

## 0. Структура репозитория

```
core\			- ядро вопросной системы (предметно-независимое)
	db\		- БД для хранения студентов/вопросов/ответов/... (подсистема ядра)
domains\		- плагины для предметных областей
	control structures\	- Алгоритмы и Трассы
	data elements\		- Переменные, Данные, и пр.
strategies\		- плагины стратегий для выбора вопроса в рамках упражнения, и пр.
frontends\		- плагины для подключения различных интерфейсов пользователя
backends\		- плагины для подключения различных рассуждателей
```

(доп. репозиторий, где ведутся эксперименты с онтологиями: https://github.com/den1s0v/c_owl)

## 1. Выработка архитектуры

#### Глоссарий и вводные положения [устарело]
См. документ [QuizOnto_intro.docx](/core/QuizOnto_intro.docx)

#### Схемы и диаграммы общей архитектуры [устарело]
См. файл Astah [OntoQuiz_diagrams.asta](/core/OntoQuiz_diagrams.asta)

Изображения диаграмм Astah:

Внешние Интерфейсы
<img src="/domains/control_structures/img/OntoQuiz_diagrams/ВнешниеИнтерфейсы.png">

Внутренние Интерфейсы
<img src="/domains/control_structures/img/OntoQuiz_diagrams/ВнутренниеИнтерфейсы.png">
