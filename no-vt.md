### Если виртуалка не запускается и пишет про отсутствие VT:
1. Перезагружаем хост-машину, заходим в BIOS (нажимая del), в вкладке «настройки BIOS» выставляем
	* запрет выполнения программ из области данных – выключено
	* технология Intel Virtualization – включено.
	* VT-d – включено.
1. Сохраняем и выходим.
1. После загрузки ОС хоста не логинимся, а нажимаем завершить работу (не перезагрузка, а выключение).
1. Включаем хоста, виртуалка должна запускаться.