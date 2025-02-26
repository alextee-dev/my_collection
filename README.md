# Ansible Collection: `my_collection`

Это Ansible коллекция, которая включает роль, выполняющую создание файла с определенным содержимым.

## Описание

Коллекция предоставляет роль `my_role`, которая использует модуль `my_own_module`. Модуль создает файл по указанному пути и записывает в него заданное содержимое.

## Переменные роли

`file_path`: Путь к файлу, который нужно создать.

`file_content`: Содержимое, которое будет записано в файл.

## Модуль

Модуль: my_own_module

Модуль my_own_module создает файл по указанному пути и записывает в него содержимое.

## Параметры модуля

`path` (обязательный): Путь к файлу.

`content` (обязательный): Содержимое файла.


Скриншоты выполнения:

4 ![image](https://github.com/user-attachments/assets/2cb76f3e-4244-4fdb-9a62-6fae9bb4a4bc)

6 ![image](https://github.com/user-attachments/assets/d6324388-b80a-49da-8772-3090fffeac4b)
 
15 ![image](https://github.com/user-attachments/assets/786053f2-7e4a-4308-a762-4e1d48858436)

16 ![image](https://github.com/user-attachments/assets/eb0f1ad4-936a-4f59-93b0-897b9e257bab)
