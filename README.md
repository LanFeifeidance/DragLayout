###导入依赖
Add it in your root build.gradle at the end of repositories:
```markdown
allprojects {
	repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Add the dependency
```markdown
  dependencies {
	        implementation 'com.github.LanFeifeidance:DragLayout:DragLayout'
	}
```
###使用
```xml
<com.example.axiu.draylayout.DragView
    android:id="@+id/dragview"
    android:layout_height="match_parent"
    android:layout_width="match_parent"
    android:background="#00ffffff"
/>
```
```
mDragView.addDragView(R.layout.my_self_view, 0,400,380,760, true, false);
```

