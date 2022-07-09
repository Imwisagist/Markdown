#Markdown homework

##Оповещения
######Синтаксис из документации не работает, как исправить?
> [!NOTE]
> Информация, которую пользователь должен заметить даже при беглом просмотре.

> [!TIP]
> Дополнительные сведения, помогающие пользователю лучше решить задачу.

> [!IMPORTANT]
> Важные сведения для успешного решения задачи.

> [!CAUTION]
> Потенциальные негативные последствия действия.

> [!WARNING]
> Опасные последствия действия.

##Угловые скобки
Если в тексте файла используются угловые скобки (например, для обозначения заполнителя), <br>
их нужно кодировать вручную. В противном случае разметка Markdown считает их HTML-тегами. <br>
Их можно экранировать, например - \<script name>

##Цитирование

Блоки цитирования создаются с помощью символа >:

> print("Цитата")

##Полужирное, курсив и зачеркивание
Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:<br>

> **Полужирный текст**  -  **текст который следует сделать полужирным\**<br>
> (скопируйте и удалите слэш)

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:<br>
> *Курсивный текст*  -  *текст который следует сделать курсивным\*<br>
> (скопируйте и удалите слэш)

Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные звездочки:<br>
> ***Курсивный и полужирный текст***  -  ***текст который следует сделать курсивным и полужирным\***<br>
> (скопируйте и удалите слэш)

Чтобы зачеркнуть текст оберните его в 2 тильды
~~Зачеркните это немедленно~~

##Фрагменты кода

```python
a = 'Код'
print(a)
```

##Комментарии
Документация поддерживает комментарии HTML, если необходимо закомментировать разделы статьи:<br>
Начинается комментарий с <!---, а заканчивается на --->
<!--- Мой комментарий --->

##Заголовки
Существуют 6 уровней:
Осуществляются через символ решетки, чем больше символов решетки идёт подряд тем<br>
меньше размер заголовка например
> #Заголовок H1
> ##Заголовок H2
> ###Заголовок H3
> ####Заголовок H4
> #####Заголовок H5
> ######Заголовок H6

##Изображения
Чтобы показать изображение используйте следующий синтаксис<br>
![<Путь>](<path.jpg>) <br>
Где alt text это краткое описание изображение, а folder path это относительный путь к нему.<br>
![<Космос>](<kosmos.jpg>)

##Списки

###Нумерованные списки
Пишете цифру после этого точку и пробел,<br>следом текст
1. Элемент
2. Элемент
3. Элемент

###Ненумерованные списки
Пишете символ звёздочи, следом пробел <br> и за ним текст
* Элемент
* Элемент
* Элемент

#Ссылки
Пишете текст в квадратных скобрках,следом без отступа ссылку в круглых скобках<br> 
Для более детальной информации обратитесь к [автору](https://github.com/Imwisagist?tab=repositories).