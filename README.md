 Language : us | [ru](./README.ru-RU.md)

# Scroling information

This is a program with `information about games`. You can scroll down the page to see more games. This is my `first experience` with links and scrolling page

List of games:
- Little Nightmaers II
- Portal 2
- Terraria
> In the future I plan to add more games and make additional functionality

 # Compatibility

<h1 align="center">Important code moments
 | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Android_robot.svg/800px-Android_robot.svg.png_48x48.png" alt="Edge" width="24px" height="24px" /></br>Android | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Apple_logo_grey.svg/1724px-Apple_logo_grey.svg.png" alt="Edge" width="24px" height="24px" /></br>Apple |
:-------:|:-------:|
|    ✔️  |    ❌  |
</h1> 
  
<h1 align="center">Important code moments</h1> 

```
<TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="8dp"
            android:autoLink="web"
            android:text="https://www.little-nightmares.com/" />
```
`android:autoLink="web"` - is create links to the website

### And offcourse works with images
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

This important lines are substitute the image `according to the size of the screen`

<div align="center">

# Images

|                First 2 game                |                    The Third                   |
:-------------------------------------------:|:----------------------------------------------:|
 ![Screenshot](Screenshot1.png)              |  ![Screenshot](Screenshot2.png)




