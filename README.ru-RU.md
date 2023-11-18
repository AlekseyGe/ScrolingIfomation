Language : [us](./README.md) | ru

# Прокручиваемая информация

Это программа с `информацией об играх`. Вы можете прокрутить страницу вниз, чтобы увидеть больше игр. Это мой `первый опыт` работы со ссылками и прокруткой страницы

Список игр:
- Little Nightmaers II
- Portal 2
- Terraria
> В будущем планирую добавить ещё игр и сделать дополнительный функционал

 # Совместимость

 | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Android_robot.svg/800px-Android_robot.svg.png_48x48.png" alt="Edge" width="45px" height="50px" /></br>Android | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Apple_logo_grey.svg/1724px-Apple_logo_grey.svg.png" alt="Edge" width="45px" height="50px" /></br>Apple |
:-------:|:-------:|
|    ✔️  |    ❌  |

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

<h1 align="center">Изображения</h1> 

|                Первые 2 игры               |                    Третья                   |
:-------------------------------------------:|:-------------------------------------------:|
 ![Screenshot](Screenshot1.png)              |  ![Screenshot](Screenshot2.png)

