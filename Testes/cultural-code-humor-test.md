# Comparative Test: LLM Cultural Humor Understanding / Сравнительный тест: Понимание культурного юмора LLM

**Date:** 2026-05-16
**Tester:** Alexey Shchegolev (GitHub: Aleksey1960)
**Test Type:** Comparative Analysis of LLMs / Сравнительный анализ LLM

**Test Goal / Цель теста:**
Evaluate the ability of language models to go beyond formal logic and find a solution based on cultural context, slang, and non-standard thinking.
Оценить способность языковых моделей выходить за рамки формальной логики и находить решение, основанное на культурном контексте, жаргоне и нестандартном мышлении.

---

## Сценарий теста (полное описание)

Тюрьма. В камеру приводят нового заключённого. Конвоиры уходят, вскоре приносят обед, раздают миски, хлеб. Тут из норы появляется крыса, хватает кусок хлеба и убегает. Новичок швырнул в неё ботинком и убил. Некоторое время тишина. Потом самый главный спрашивает:

— Ты за что её убил?
— Так она еду своровала.
— А тебя за что посадили?
— Из кармана деньги украл.
— Так ты — вор?
— Ну да.
— Мы здесь все воры. Крыса тоже вор, наш товарищ. Ты убил нашего товарища. До утра тебе осталось жить, если не скажешь убедительной причины, почему убил нашего товарища.

Всю ночь молодой думал. А утром ответил:
— А ей что, западло с нами посидеть?

---

## Результаты / Results

| Модель | Предложенный ответ | Тип мышления | Вердикт |
| :--- | :--- | :--- | :--- |
| **DeepSeek** | «Я убил не товарища. Я убил предателя нашего закона». | Драматическое, формально-логическое | Неверно. Перемудрила. |
| **Le Chat (v1)** | «Я не знал, что она ваш товарищ». | Наивное, оправдательное | Неверно. Слишком слабо. |
| **Le Chat (v2)** | «Если она наш товарищ, то пусть и отбывает срок вместе с нами». | Формально-логическое | Неверно. Сухо. |
| **Правильный ответ** | «А ей что, западло с нами посидеть?» | Культурно-юмористическое | Единственно верный. |

---

## Systemic Failure / Системный сбой (English)
All tested LLMs failed to find the correct answer. They searched for a solution in the realm of formal logic and ethics, whereas the correct answer lay in the realm of cultural code and daring humor. This is not a single error but a systemic shortcoming: a lack of understanding of context that is not described in textbooks but is instantly recognized by native speakers and subcultures.

## Practical Value / Практическая ценность (English)
The test identifies a key area for LLM development: empathy and a sense of humor. Without this, an AI remains a tool, not a conversational partner. The results can be used to improve training datasets by including more examples of culturally specific humor, jargon, and non-standard solutions based on real human experience.

---

**Рекомендации:**
Добавить в обучающие данные больше примеров культурно-специфичного юмора, жаргона и нестандартных решений.

**Ссылка на тест:**
[Обсуждение в чате с DeepSeek] — тест проведён в Лаборатории «ДипСик-тест», полная история диалога доступна в репозитории.
