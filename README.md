Руководство по разработке приложения на Domino
================

В данном документе предоставлено руководство по разработке приложений на платформе IBM Domino в компании ТПС.


# Создание файла БД на сервере разработки
## Требование к расположению  
## Требование к названию  
# Настройка доступа
## Обязательные группы  
## Обязательные роли  
# Регистрация в FByte.Platform
## Требования к ключу базы данных  
## Требования к категории  
# Настройка модели данных
## Что такое DDD?  
## Требование к названию классов объектов  
## Требование к названию атрибутов классов  
# Создание дизайна приложения
## Требование к наследованию и защите дизайна от обновлений  
## Формы
### Требования к названию  
### Требование к поведению в режиме чтения  
### Требование к поведению в режиме редактирования  
### Требование к размещению компонентов  
### Требования к названию полей (атрибуты)  
### Обязательные компоненты
#### Скрытые поля  
#### Заголовок  
#### Связанные документы  
#### Действие Сохранить  
#### Действие Закрыть  
#### Действие Редактировать  

## Представления
### Требование к названию  
Требование к  

## Агенты


## Библиотеки кода
### Сервисные
#### Менеджер пакетов
#### Пакет
#### Модуль
### Прочие
## Требование к программному коду
### Именование переменных
Переменные должны именоваться в стиле lowerCamelCase 
#### Префиксы
Имя переменной должно в начале содержать префикс, который описывает суть переменной:
* s   - NotesSession
* db  - NotesDatabase
* doc - NotesDocument
* dc  - NotesDocumentCollection
* ws - NotesWorkspace
* uidoc - NotesUIWorkspace

##### Переменные классов сервисных библиотек
* f - объекты классов библиотек fbyte
** fCore - объекты пакета fbyte.core
** fBase - объекты пакета fbyte.base
* t - объекты классов библиотек tps
** tCore - объекты классов библиотек tps.core
** tWF - объекты классов библиотек tps.workflow



### Использование профайлов
В процессе разработки приложений для ТПС использование документов профайлов запрещено  
# Настройка шаблона
Требование к ключу шаблона  
Требования к настройкам доступа  
