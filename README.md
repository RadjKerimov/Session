# Session
Flash - основанный на сессиях компонент, для вывода флеш сообщений/уведомлений




С помошью Flash вы сможете выводит содержимое session а так же создавать session 


Метод create()
===========
Создает session 
принимает ключ и значение 
return array
```php
Session::create('error', 'Такого пользователя нет!');
```


Метод get()
===========
Выводит session 
принимает ключ
return array
```php
Session::get('error');
```



Метод exists()
===========
Проверяет если такая session 
принимает ключ
return bool
```php
Session::exists('error');
```



Метод delete()
===========
Удаляет session 
принимает ключ
return bool
```php
Session::delete('error');
```




Метод delFlashete()
===========
Создает сообщений/уведомлений
принимает ключ значение

```php
Session::Flash('error', 'string');
```
