---
marp: true
theme: default
paginate: true
footer: 'Лабораторная работа №9 · НПИбд-03-25, Чжу Ино'
style: |
  section {
    font-family: "Times New Roman", serif;
    font-size: 24px;
    padding: 50px 70px;
    line-height: 1.5;
    color: #1a1a1a;
  }
  h1 {
    font-size: 38px;
    color: #003366;
    border-bottom: 3px solid #003366;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }
  h2 {
    font-size: 30px;
    color: #003366;
    margin-bottom: 15px;
  }
  ul {
    margin-top: 10px;
  }
  li {
    margin-bottom: 8px;
  }
  section.lead {
    text-align: center;
    justify-content: center;
  }
  section.lead h1 {
    border: none;
    font-size: 46px;
    margin-bottom: 40px;
  }
  section.lead p {
    font-size: 26px;
    margin: 6px 0;
  }
  section.chapter {
    text-align: center;
    justify-content: center;
    background: #f4f7fb;
  }
  section.chapter h1 {
    border: none;
    font-size: 44px;
  }
  footer {
    font-size: 14px;
    color: #666;
  }
---

<!-- _class: lead -->

# Лабораторная работа №9. Редактор vi

НПИбд-03-25, Чжу Ино

---

# Содержание

1. Титульный слайд
2. Введение
3. Создание каталога и файла
4. Установка прав и запуск скрипта
5. Редактирование и повторный запуск
6. Заключение
7. Список литературы

---

<!-- _class: chapter -->

# 1. Титульный слайд

---

- Лабораторная работа №9
- Редактор vi
- НПИбд-03-25
- Чжу Ино

---

<!-- _class: chapter -->

# 2. Введение

---

- Знакомство с операционной системой Linux
- Получение практических навыков работы с редактором vi
- Создание и редактирование файлов

---

<!-- _class: chapter -->

# 3. Создание каталога и файла

---

- Создание каталога: `mkdir -p ~/work/os/lab06`
- Создание файла `hello.sh` через `cat > ... << 'EOF'`
- Содержимое: переменные, функции, вывод

---

<!-- _class: chapter -->

# 4. Установка прав и запуск скрипта

---

- Установка прав: `chmod +x ~/work/os/lab06/hello.sh`
- Проверка прав: `ls -la`
- Запуск скрипта: `~/work/os/lab06/hello.sh`

---

<!-- _class: chapter -->

# 5. Редактирование и повторный запуск

---

- Открытие файла: `nano ~/work/os/lab06/hello.sh`
- Внесение изменений
- Повторный запуск и проверка результата

---

<!-- _class: chapter -->

# 6. Заключение

---

- Получены навыки работы с редактором vi (nano)
- Освоены создание и редактирование файлов
- Изучена установка прав на выполнение
- Освоен запуск скриптов

---

<!-- _class: chapter -->

# 7. Список литературы

---

1. Neil N. J. Learning CentOS: A Beginners Guide to Learning Linux. — CreateSpace Independent Publishing Platform, 2016.
2. Vugt S. van. Red Hat RHCSA/RHCE 7 cert guide. — Pearson IT Certification, 2016.
3. Unix и Linux: руководство системного администратора / Э. Немет и др. — 5-е изд. — СПб. : ООО «Диалектика», 2020.