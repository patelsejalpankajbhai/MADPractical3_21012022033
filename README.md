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



![Screenshot_20220916_123848](https://user-images.githubusercontent.com/110646988/190578784-4be96f03-21a7-4efb-a305-6cd38c8ecaaa.png)

![Screenshot_20220916_123856](https://user-images.githubusercontent.com/110646988/190578802-bcbdcfc0-2d2f-4e9e-8e64-6b03eac76ff3.png)

![Screenshot_20220916_123902](https://user-images.githubusercontent.com/110646988/190578820-8e0eac63-1127-4c82-93f6-2a617d2de128.png)



![Screenshot_20220916_123659](https://user-images.githubusercontent.com/110646988/190578846-9419d50b-18b2-4d94-bd4f-d686afb4eb7b.png)

![Screenshot_20220916_123803](https://user-images.githubusercontent.com/110646988/190578866-391406bb-3bc8-48bc-9492-3f8f9d48b159.png)

![Screenshot_20220916_123814](https://user-images.githubusercontent.com/110646988/190578897-801c29e1-a92b-4f74-b05b-364d6c9e9e08.png)
