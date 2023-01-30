# python-developer-theory
**Table of contents:**

<!-- toc -->
- [Переменные](#переменные)
  * [Что надо ответить](#что-надо-ответить)
<!-- tocstop -->

## Переменные
Переменные предназначены для хранения данных. Название переменной в Python должно начинаться с алфавитного символа или со знака подчеркивания и может содержать алфавитно-цифровые символы и знак подчеркивания. И кроме того, название переменной не должно совпадать с названием ключевых слов языка Python. Ключевых слов не так много, их легко запомнить:

Переменные

### Что надо ответить
It's a good idea to define a `BaseModel`, that you can inherit.

Usually, fields like `created_at` and `updated_at` are perfect candidates to go into a `BaseModel`.

Defining a primary key can also go there. Potential candidate for that is the [`UUIDField`](https://docs.djangoproject.com/en/dev/ref/models/fields/#uuidfield)

Here's an example `BaseModel`:
