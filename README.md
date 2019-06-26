## Preview
![sample](https://github.com/Maggie-Wan/StrokTextView/blob/master/sample.png?raw=true)
## Gradle：

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


 Add the dependency

	dependencies {
	        implementation 'com.github.Maggie-Wan:StrokTextView:v1.0'
	}

## Usage：

 Add add stroke and stroke color in your xml.

 stroke setting： app:stroke="your stroke(float)"

 stroke color setting: app:strokeColor="your color(Hex Code)"

 You can see the example in [app file](https://github.com/Maggie-Wan/StrokTextView/blob/master/app/src/main/res/layout/activity_main.xml "app file").

    <com.maggie.stroketextviewlibrary.StrokeTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello Android!"
        android:textSize="40sp"
        android:textColor="#00BCD4"
        app:stroke="20.0"
        app:strokeColor="#F44336"
        android:paddingBottom="20dp"/>
