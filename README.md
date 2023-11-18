 Language : us | [ru](./README.ru-RU.md)

# Scroling information

This is a program with `information about games`. You can scroll down the page to see more games. This is my `first experience` with links and scrolling page
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

|                First 2 game                | The third |
:-------------------------------------------:|:----------|
 ![Screenshot](Screenshot1.png) |  ![Screenshot](Screenshot2.png)

