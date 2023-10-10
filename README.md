# Техническое задание




## **Структура репозитория**
> **[Graphs](https://github.com/Lamardo43/JMeter_Test_Load_11.10.2023/tree/master/Graphs)** - Папка с графиками

> **[SpringApp](https://github.com/Lamardo43/JMeter_Test_Load_11.10.2023/tree/master/SpringApp)** - Папка с файлами заглушки (Java)

> **[HTTP Request.jmx](https://github.com/Lamardo43/JMeter_Test_Load_11.10.2023/blob/master/HTTP%20Request.jmx)** - Файл скрипта

> **[task.txt](https://github.com/Lamardo43/JMeter_Test_Load_11.10.2023/blob/master/task.txt)** - Файл задания


## **Заглушка**
### **Адрес для отправки POST-запроса:**

`http://localhost:8081/post-message`

### **Команда сборки, используя Maven:**

`mvn spring-boot:run`


### **Пример запроса:**

`curl -X POST -H "Content-Type: application/json" -d '{"msg_id":"121212"}' http://localhost:8081/post-message`


### **Пример возвращаемого json:**

```json
{
    "msg_id": "121212",
    "timestamp": "1070936100",
    "method": "POST",
    "url": "/post-message"
}
```

## Скрипт
### Приложение
[`Apache JMeter`](https://jmeter.apache.org/)

### Плагины
- 3 Basic Graphs
- 5 Additional Graphs

## Графики
### Инструмент
 - Получены с использованием плагинов на JMeter (установлены при помощи [`JMeter Plugins Manager`](https://jmeter-plugins.org/wiki/PluginsManager/), указаны выше)
 
