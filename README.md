# cyberimmunity_course_files
## ДЗ1 Проектирование кибериммунной системы
В качестве проектируемой системы выбрана система резервного копирования данных. 

Система предназначена для копирования личных данных пользователя в облачное хранилище/восстановления данных из копии по его запросу. Для системы не требуется доступность 24/7 (допустимо проведение технических работ).

### Активы продукта
1. Хранимые данные пользователя
2. Возможность создания резервной копии
3. Возможность восстановления данных из резервной копии
4. Предоставление только авторизованного доступа к данным пользователя

### Возможные риски
1. Нарушение целостности данных пользователя
2. Нарушение конфиденциальности данных пользователя
4. Нарушение доступности системы
5. Нарушение надежности системы
6. Нарушение устойчивости системы

### Ущерб
1. Утрата хранимых данных пользователя
2. Раскрытие конфиденциальных данных пользователя
4. Невозможность создания резервной копии
5. Невозможность восстановления данных из резервной копии

### Негативные сценарии
1. Злоумышленник получает несанкционированный (неавторизованный) доступ к данным пользователя 
2. Злоумышленник ограничивает пользователю доступность системы 
3. Злоумышленник нарушает целостность данных пользователя

### Сценарии использования
1. Пользователь регистрируется в системе
2. Пользователь создает резервную копию данных
3. Пользователь восстанавливает данные из резервной копии

### Цели безопасности
1. Данные пользователя, передающиеся в систему при создан резервной копии, а также данные, передаваемые пользователю при восстановлении из резервной копии, ни при каких условиях не раскрываются для иных лиц.
2. Не существует технически осуществимого сценария компрометации данных аутентификации и авторизации.
3. Данные пользователя сохра

### Предположения безопасности
1. Пользователь не сообщает иным лицам данные, необходимые для аутентификации.
2. Ответственность за целостность данных до загрузки в систему лежит на пользователе.
