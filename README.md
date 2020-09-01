# layout_above_keyboard
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context="com.ehubstar.group.CreateGroupActivity">

    <androidx.appcompat.widget.Toolbar
        android:id="@+id/toolbar"
        android:layout_alignParentTop="true"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/white"
        android:minHeight="?attr/actionBarSize"
        android:elevation="@dimen/default_elevation"
        app:title=""
        app:navigationIcon="@drawable/ic_round_arrow_back_ios_24"
        app:theme="@style/ThemeOverlay.MaterialComponents.ActionBar"/>

    <ScrollView
        android:layout_below="@id/toolbar"
        android:layout_above="@id/linearBottom"
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical"
            android:padding="@dimen/margin_24dp">

            //your layout

        </LinearLayout>
    </ScrollView>


    <LinearLayout
        android:id="@+id/linearBottom"
        android:layout_alignParentBottom="true"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <Button
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="@string/create_group"
            android:textAllCaps="false"
            android:layout_margin="@dimen/margin_16dp" />
    </LinearLayout>
</RelativeLayout>
```
