# Interpreter

Учебный интерпретатор на C++, реализующий полный цикл обработки исходного кода:  
лексический анализ, синтаксический разбор, выполнение семантических действий и интерпретацию программ на простом императивном языке.

Educational interpreter in C++ implementing the full pipeline of source code processing:  
lexical analysis, syntax parsing, semantic actions execution, and interpretation of programs in a simple imperative language.

---

## 🚀 Возможности / Features

### Лексический анализатор (Lexical Analyzer)
- Построен на таблицах переходов состояний  
- Поддерживает ключевые слова: `int`, `real`, `if`, `else`, `while`, `input`, `output`  
- Распознаёт:
  - идентификаторы / identifiers  
  - целые и вещественные числа / integers and reals  
  - арифметические операции `+ - * /`  
  - операции сравнения `== < > !`  
  - скобки `() [] {}` и `;`  
  - присваивание `=`  

### Синтаксический анализатор (Syntax Analyzer)
- Основан на LL-анализе с таблицей правил грамматики  
- Поддерживает:
  - объявления переменных и массивов / variable and array declarations  
  - присваивания / assignments  
  - условные конструкции `if ... else` / conditional statements  
  - циклы `while` / loops  
  - блоки `{ ... }` / code blocks  
  - ввод/вывод данных / input & output  

### Семантический анализатор (Semantic Analyzer)
- Выполняет генерацию и интерпретацию операций:
  - арифметика (`+ - * /`) / arithmetic operations  
  - сравнения (`== < > !`) / comparison operations  
  - работа с массивами / array operations  
  - ввод/вывод / I/O operations  

---

## 📂 Структура проекта / Project Structure

- `Interpreter.cpp` — основной файл  
  - таблицы для лексического анализатора / lexical analyzer tables  
  - структуры токенов / token structures  
  - функции разбора и интерпретации / parsing & execution functions  

---

## 📝 Пример программы / Example Program

- `test.txt` — файл с тестовым кодом на "выдуманном" языке
