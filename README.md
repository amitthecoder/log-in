## Screenshot

![Demo](https://raw.githubusercontent.com/amitthecoder/log-in/main/screenshot.jpg "Demo")

## XML Code

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:layout_gravity="center"
    android:gravity="center"
    tools:context=".MainActivity"
    android:padding="20dp">


    <com.google.android.material.textfield.TextInputLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:startIconDrawable="@drawable/username"
        app:endIconMode="clear_text"
        android:hint="@string/username">
        <com.google.android.material.textfield.TextInputEditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"/>
    </com.google.android.material.textfield.TextInputLayout>

    <com.google.android.material.textfield.TextInputLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="30dp"
        app:startIconDrawable="@drawable/password"
        app:endIconMode="password_toggle"
        android:hint="@string/password">
        <com.google.android.material.textfield.TextInputEditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:inputType="textPassword"/>
    </com.google.android.material.textfield.TextInputLayout>

    <com.google.android.material.button.MaterialButton
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textColor="@color/white"
        android:backgroundTint="@color/black"
        android:text="@string/log_in"
        android:clickable="true"
        android:layout_marginTop="30dp"
        android:focusable="true" />

</LinearLayout>
```
