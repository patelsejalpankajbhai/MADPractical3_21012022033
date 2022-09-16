# MADPractical3_21012022022

Study: Resource, Theme, Color, Layout, Explicit Intent, BottomNavigationView, Gradle File structure, Material Design 3

LinearLayout, RelativeLayout, ConstraintLayout, Card View, Image View, BottomNavigationView, Navigation Menu in res/menu folder, ScollView, MaterialToolBar, Light Theme, Dark Theme, jpg & png image in drawable folder, Data binding, Color in theme, string in xml file, TextInputLayout, TextInputEditText

android:noHistory="true" in manifest file,

setOnItemSelectedListener() method,

selectedItemId of Bottom NavgationView,

app:layout_scrollFlags="scroll|enterAlways|snap",

android:fitsSystemWindows="true",

<item name= "android:navigationBarColor" > @android:color/transparent </item>,

<item name= "android:statusBarColor" > @android:color/transparent </item>,

android:layout_gravity="bottom",

app:layout_behavior = "@string/hide_bottom_view_on_scroll_behavior"

Add Drawable Resource in android project

AIM: Create following UI by using ConstraintLayout, LinearLayout, in one android Application. Create two activities for each layout & use BottomNavigationBar & Explicit Intent to move from one activity to another activity. Don't use LinearLayout in ConstraintLayout and vice versa.

Step-1: Add Data Binding in gradle file and sync.

Step-2: Open Themes.xml and themes.xml (night) and change to Material3 Theme and keep navigationbar transparent as shown in code hint.

Step-3: Open activity_main.xml file and add code of CoordinatorLayout with toolbar as shown in code hint

Step-4: Open MainActivity.kt file and add binding code as shown in code hint

Step-5: Add android:noHistory="true" in activity in manifest file as shown in code hint

Repeat Above steps whenever you are adding activity in android application or creating new project for new practical.


![Screenshot_20220916_123848](https://user-images.githubusercontent.com/110646988/190579959-4368261b-4719-4b7b-97d7-bfbdcaf01b88.png)


![Screenshot_20220916_123856](https://user-images.githubusercontent.com/110646988/190579969-a65c0f58-5468-4222-a1a7-e1fd5fad54f1.png)


![Screenshot_20220916_123902](https://user-images.githubusercontent.com/110646988/190579987-2b73864e-0b7e-495d-9959-2b1da23451b0.png)





![Screenshot_20220916_123659](https://user-images.githubusercontent.com/110646988/190580028-22999a78-5289-45c4-bd8a-868829a8cb04.png)


![Screenshot_20220916_123803](https://user-images.githubusercontent.com/110646988/190580037-e39f921b-12d1-4830-b260-7d8c24253ad9.png)


![Screenshot_20220916_123814](https://user-images.githubusercontent.com/110646988/190580044-fc2d50d2-55f4-490f-ad36-c6cd679465c0.png)
