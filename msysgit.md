## Установка GIT в Windows.  

Установка Git в Windows очень проста. У проекта msysGit процедура установки ― одна из самых простых. 
Просто скачайте файл exe-инсталлятора со страницы http://msysgit.github.io/ (или со [страницы загрузки](download.md)) и запустите его от имени администратора локального компьютера. После установки у вас будет как консольная версия (включающая SSH-клиент), так и стандартная графическая.  

### Экранные формы инсталлятора Git 2.6.3 для Windows:   

![Начало инсталляции Git.](/gtnn/msysgit1.jpg)   
Рисунок 1. Начало инсталляции Git.  
  

![GNU GPL.](/gtnn/msysgit2.jpg)  
Рисунок 2. Читаем GNU GPL.  


![Install Directory.](/gtnn/msysgit2-1.jpg)  
Рисунок 3. Оставляем по умолчанию путь для установки GIT.
  

![Advanced Context Menu.](/gtnn/msysgit3.jpg)  
Рисунок 4. Выбираем интеграцию ярлыков Git-Bash и Git-GUI в Windows Explorer и выносим на Рабочий стол и Меню Пуск ярлыки для запуска утилит GIT.   


![Start Menu.](/gtnn/msysgit3-1.jpg)  
Рисунок 5. Указываем название для папки с ярлыками для GIT в меню Пуск.
  

![PATH Envoronment.](/gtnn/msysgit4.jpg)  
Рисунок 6. Выбором третьей опции включаем в переменную PATH путь к Git и к Unix-утилитам (например нам понадобится далее ssh-keygen).  
  

![Converstions.](/gtnn/msysgit5.jpg)  
Рисунок 7. Выбираем Checkout as-is, commit as-is. Т.е. не допускаем преобразований CRLF, т.к. не разрабатываем кросс-платформенные приложения.  


![Use default windows cmd console.](/gtnn/msysgit5-1.jpg)  
Рисунок 8. Для работы с Git будем использовать стандартную командную оболочку "cmd.exe".


![Converstions.](/gtnn/msysgit5-2.jpg)  
Рисунок 9. Экспериментальную возможность кэширования файловой системы использовать не будем.

  
![Installing Git.](/gtnn/msysgit6.jpg)  
Рисунок 10. Процесс инсталляции.  
  

![Completing Installation Git.](/gtnn/msysgit7.jpg)  
Рисунок 11. Завершение установки.  

