# NotificationCount

- [background_filled_red_radius.xml](https://github.com/gzeinnumer/NotificationCount/blob/master/app/src/main/res/drawable/background_filled_red_radius.xml)
 
- activity_main.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <androidx.constraintlayout.widget.ConstraintLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent">

        <ImageView
            android:id="@+id/btn_notifikasi"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:src="@drawable/ic_baseline_notifications_active_24"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintLeft_toLeftOf="parent"
            app:layout_constraintRight_toRightOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <TextView
            android:id="@+id/btn_notifikasi_count"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@drawable/background_filled_red_radius"
            android:paddingLeft="2dp"
            android:paddingRight="2dp"
            android:textColor="@color/white"
            android:textSize="11sp"
            android:visibility="gone"
            app:layout_constraintRight_toRightOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            tools:text="1"
            tools:visibility="visible" />
    </androidx.constraintlayout.widget.ConstraintLayout>
</androidx.constraintlayout.widget.ConstraintLayout>
```

![](https://github.com/gzeinnumer/NotificationCount/blob/master/preview/example1.jpg.png)

---

```
Copyright 2021 M. Fadli Zein
```