# layout_above_keyboard
```
<RelativeLayout
	xmlns:android="http://schemas.android.com/apk/res/android"
	android:orientation="vertical"
	android:layout_height="fill_parent"
	android:layout_width="fill_parent">
	<ScrollView
		android:id="@+id/scrollview"
		android:layout_height="fill_parent"
		android:layout_width="fill_parent"
		android:layout_above="@+id/m_table_menu">
... stuff here ....
        </ScrollView>
	<TableLayout
		android:id="@+id/m_table_menu"
		android:layout_height="wrap_content"
		android:layout_width="wrap_content"
		android:layout_alignParentBottom="true"
		android:padding="0dp"
		android:background="#000000"
		android:stretchColumns="*">
... bottom row floating stuff here ...
        </TableLayout>
</RelativeLayout>
```
