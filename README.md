# FramelessQmlWindow
Frameless application window template qml, resizeable, maximalizable, minimalizable, draggable, ready to be more customized.
Buttons colors are animated on hover and pressed. When window is dragged on top of the screen it is auto maximalized. <br/>

Just open Application.qml in DesignStudio and write your code in this place:
```
.
.
.
    Item {
        anchors{
            top: topBar.bottom
            left: parent.left
            right: parent.right
            bottom: parent.bottom
        }
        /*Your content here*/
    }
.
.
.
```
# ScreenShoots
## Top bar
![Bar](ScreenShots/Bar.png)
## Normal
![normal](ScreenShots/Normal.png)
## Bigger
![Bigger](ScreenShots/Bigger.PNG)
## Maximalized
![Maximalized](ScreenShots/Maximalized.PNG)
