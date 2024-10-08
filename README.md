# Material Button Example for Attractive Android Apps-

Many beginner Android developers want their apps to look attractive and engaging. One effective way to enhance UI is through the use of buttons. The MaterialButton provides built-in attributes for customization, including a ripple effect, which can make your app more interactive.

There are many options to make a button in android but material button provides some attributes by which we donot have to make extra drawable files for making our button customized.
Here i am going to provide you the code to make a material button which makes our app very attractive whenever we perform a click on it.

-------------------------------------------------------------------------CODE-------------------------------------------------------
```
 <com.google.android.material.button.MaterialButton
        android:id="@+id/mb_started"
        android:layout_width="@dimen/_250sdp"
        android:layout_height="@dimen/_37sdp"
        android:backgroundTint="@color/green"
        app:cornerRadius="@dimen/_6sdp"
        android:layout_gravity="center"
        app:rippleColor="#12735D"
        android:text="@string/let_s_get_started"
        android:textColor="@color/white"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        />
        
-----------------------------------------------------------------------CODE--------------------------------------------------------


**EXPLANATION OF ATTRIBUTES**
backgroundTint: Sets the background color (green in this case).
cornerRadius: Rounds the corners of the button.
rippleColor: Changes the ripple effect color on click (dark green).
textColor: Specifies the color of the button's text.


**REQUIREMENTS**
Ensure you have the Material Components library added in your build.gradle file:

**Implementation**
implementation 'com.google.android.material:material:1.4.0'


**The way how it looks like**
**Copy this link and paste it in a new tab for a look that how a material button look like**
https://github.com/user-attachments/assets/f0961d85-adc6-4265-8b24-417b69f5b436






           
