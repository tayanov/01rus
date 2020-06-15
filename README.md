# 01rus
Custom component for monitoring traffic and ballance one of the small providers
Example config:

sensor:
  - platform: 01rus
    name: "01rus_traffic"
    username: !secret private_username
    password: !secret private_password
    
Thanks   @zvldz https://github.com/zvldz  
    

Это кастомный компонент Home Assistant для получения информации о траффике и балансе моего провайдера.
Можно использовать как шаблон для написания аналогичного компонента для ваших целей. По факту тут авторизация и парсинг страницы.

Пример конфига:
  - platform: 01rus
    name: "01rus_traffic"
    username: !secret private_username
    password: !secret private_password
    
Спасибо   @zvldz https://github.com/zvldz 
    
    
