Модуль позволит с легкостью добавить на ваш сайт оплату банковскими картами через платежный сервис CloudPayments. 
Для корректной работы модуля необходима регистрация в сервисе.

Порядок регистрации описан в [документации CloudPayments](https://cloudpayments.ru/Docs/Connect)
## Возможности
	
* Одностадийная схема оплаты;  
* Двухстадийная схема оплаты;  
* Выбор языка виджета;  
* Выбор валюты виджета; 
* Выбор дизайна виджета;  
* Поддержка онлайн-касс (ФЗ-54);
* Выбор тегов предмета и способа расчета;  
* Отправка чеков по email;  
* Отправка чеков по SMS;  

# Установка

Скачайте папку с модулем и заархивируйте ее (.zip).  
![0](Img/0.jpg) 

В панели управления сайтом через меню перейдите в "Модули" - "Модули и сервисы".  
![1](Img/1.jpg) 


Нажмите "Загрузить модуль", выберете архив с модулем, дождитесь загрузки и установки, затем нажмите "Настройка".  
![2](Img/2.JPG)   
![3](Img/3.JPG) 

# Настройка

В списке модулей найдите "CloudPayments" и нажмите "Установить", затем "Настроить".  
![4](Img/4.JPG) 


Введите "Public ID" и "Пароль для API" (их можно найти в Личном кабинете CloudPayments). Нажмите "Сохранить".
В личном кабинете CloudPayments зайдите в настройки сайта, пропишите ваши callback'и со страниц настроек модуля.
![5](Img/5.JPG) 
![6](Img/6.JPG) 

#### Changelog

= 1.2 = 

Добавление тегов предмета и способа расчета;
Исправление ошибок;

= 1.1 = 
* Добавление выбора языка виджета;  
* Добавление выбора валюты;  
* Добавление выбора дизайна виджета;   
* Правка значений ставок НДС;  

= 1.0 =
* Публикация модуля.