
**Фамилия: Минсафин**   
**Имя: Айвар**  
**Группа: 11-903**  

## Запуск системы
1. Загрузите фотографию формата .jpg и весом менее 1 мб в Object Storage `aivar-bucket-10.09.2022` (пришлось использовать старый бакет из-за невозможности создать новые из-за лимита)
2. Напишите боту [vvot27-bot](https://t.me/vvot27_bot) команду из списка:   
/start   
/getface   
/find {name}

## Сервисный аккаунт
vvot27-aivar

## Объекты
### Бакеты
- aivar-bucket-10.09.2022 (пришлось использовать единственный старый бакет из-за невозможности создать новые из-за лимита)
### БД
- vvot27-db-photo-face
### Очереди
- vvot27-tasks
### Триггеры
- vvot27-photo-trigger 
- vvot27-task-trigger 
### Функции
- vvot27-face-detection
- vvot27-boot 
### Контейнер
- vvot27-face-cut
### Api gateway
- itis-2022-2023-vvot27-api


