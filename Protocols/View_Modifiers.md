# A working list of my most used modifiers. 

+ [<font style="color:purple">.resizable()</font>](https://developer.apple.com/documentation/swiftui/image/resizable(capinsets:resizingmode:))
  In order to adjust the size of an image, this modifier is used first and subsequently in conjunction with other modifiers using dot notation. 
  <br>
  - [x] **Example**: ```
    Image("FriendAndGem")
            .resizable().scaledToFit()```