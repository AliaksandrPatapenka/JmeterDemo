# Jmeter Demo
### Данный репозиторий содержит: 
- demo-скрипт для нагрузочного тестирования
- Отчет по проведенному нагрузочному тестированию (Важно! Отчёт написан не по приложенному скрипту. Приложенный скрипт писался не для НТ, а для тренировки. В нем сложнее корреляция и параметризация. Есть функции и jsr223 процессоры)

  
### Требования к среде использования:
- JDK, Java 1.8+
- ApacheJmeter 5.6.3
- InfluxDB 1.8
- Grafana 7.0.0


#### Цели и методологию тестирования, описание тестового сценария, результаты тестирования см. в [Peport(Demo)](https://github.com/AliaksandrPatapenka/JmeterDemo/blob/main/Peport(Demo)%20.docx)


##### Ниже приведены примеры реализации тестового сценария:
1. Общая структура тестового сценария
![S1](https://github.com/user-attachments/assets/c4e8fe2d-51fa-4cdd-8ec8-72c8a5f321c8)


2. Пример параметризации через User Defined Variables
![S2](https://github.com/user-attachments/assets/a1303c6d-9a44-4b28-ba2d-3b91436409ca)


3. Пример реализации процесса авторизации на  тестовом портале
![S3](https://github.com/user-attachments/assets/6004fa55-42e1-4f8a-bc12-67eb95af717f)


4. Пример параметризации через Regular Expression Extractor
![S4](https://github.com/user-attachments/assets/f6a50414-c4d4-4ca2-a46f-e6fdeb029648)


5. Пример параметризации через JSON Extractor
![S5](https://github.com/user-attachments/assets/84536b48-530d-47db-a2d0-65c590d55c40)
![S6](https://github.com/user-attachments/assets/2f49adec-7d8e-4026-91f8-08fdd70ff305)


6. Пример параметризации через глобальные переменные
![image](https://github.com/user-attachments/assets/97dff8a5-05c8-41cb-a2aa-28d147f53876)


7. Пример реализации задачи (взять последний id сущности. При этом неизвестно сколько id сущности выводится в теле запроса. Их может быть от 0 до 20) через JSR223 PreProcessor
![S8](https://github.com/user-attachments/assets/7fe19274-8a58-4af6-9d48-5272f5f0e0b2)
![S9](https://github.com/user-attachments/assets/1f5da924-54d3-4d4d-8b3e-f84f76922a32)


8. Пример настройки интеграции JMeter+InfluxDb+Grafana
![S10](https://github.com/user-attachments/assets/4feb1cc0-bdda-4789-8903-8647cf07bb5b)
   





