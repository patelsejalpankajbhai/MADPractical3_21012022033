# MADPractical3_21012022033

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


![Screenshot_20220916_123848](https://user-images.githubusercontent.com/110646988/190580221-8d4ca688-4e15-4049-bf89-16d954b3d0e0.png)


![Screenshot_20220916_123856](https://user-images.githubusercontent.com/110646988/190580239-63c6d8a5-3840-48c9-bc97-5a052c33725c.png)


![Screenshot_20220916_123902](https://user-images.githubusercontent.com/110646988/190580252-214ac5b7-1159-486d-8aa4-0829f69c2f72.png)



![Screenshot_20220916_123659](https://user-images.githubusercontent.com/110646988/190580275-9f97e928-7822-4a8e-a54b-73b9005ac666.png)


![Screenshot_20220916_123803](https://user-images.githubusercontent.com/110646988/190580291-f05b3507-1538-4f3b-9bae-fb7c0a7c2420.png)


![Screenshot_20220916_123814](https://user-images.githubusercontent.com/110646988/190580303-0d26853d-4060-4847-b4ce-4ebc07316852.png)
