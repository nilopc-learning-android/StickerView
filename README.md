# StickerView
A view which can add sticker and zoom,drag,delete it

###screenshots
![](https://github.com/nilopc-learning-android/StickerView/blob/master/screenshots/stickerview.gif)

###usage
StickerView extends ImageView
in layout
```xml
<com.xiaopo.flying.sticker.StickerView
        android:id="@+id/sticker_view"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_gravity="center"
        android:src="@drawable/haizewang_215" />
```
add sticker, support bitmap and drawable.
if the sticker is drawable, it's intrinsic width and height can not be zero.

```java
stickerView.addSticker(bitmap)
stickerView.addSticker(drawable)
```
