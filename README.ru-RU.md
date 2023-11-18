Language : 🇺🇸 | [🇷🇺](./README.ru-RU.md)

# Прокручиваемая информация

Это программа с `информацией об играх`. Вы можете прокрутить страницу вниз, чтобы увидеть больше игр. Это мой `первый опыт` работы со ссылками и прокруткой страницы
<h1 align="center">Важные моменты кода</h1> 

```
<TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="8dp"
            android:autoLink="web"
            android:text="https://www.little-nightmares.com/" />
```
`android:autoLink="web"` -  создание ссылок на веб-сайт

### И конечно же работа с изображениями
```
<ImageView
            android:id="@+id/imageViewa"
            android:layout_width="390dp"
            android:layout_height="150dp"
            tools:srcCompat="@drawable/terraria"
            android:scaleType="centerCrop"
            android:adjustViewBounds="true"
            android:layout_marginTop="8dp"/>
```
`android:scaleType="centerCrop"`

`android:adjustViewBounds="true"`

`android:layout_marginTop="8dp"`

Эти важные строки заменяют изображение "в соответствии с размером экрана`

#Pictures
|                Первые 2 игры               | Третья |
:-------------------------------------------:|:--------|
 ![Screenshot](Screenshot1.png) |  ![Screenshot](Screenshot2.png)

