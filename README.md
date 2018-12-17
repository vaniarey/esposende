# esposende
Aplicação de Esposende
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:layout_behavior="@string/appbar_scrolling_view_behavior"
    tools:context=".Esposende"
    tools:showIn="@layout/activity_esposende">

    <ImageView
        android:id="@+id/imageView8"
        android:layout_width="382dp"
        android:layout_height="814dp"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@mipmap/ic_launcher_foreground"
        tools:layout_editor_absoluteX="1dp" />

    <ImageButton
        android:id="@+id/imageButton"
        style="@style/Widget.AppCompat.ImageButton"
        android:layout_width="213dp"
        android:layout_height="218dp"
        android:background="@mipmap/ic_launcher_background"
        android:contentDescription="@string/app_name"
        tools:layout_editor_absoluteX="91dp"
        tools:layout_editor_absoluteY="44dp" />

</android.support.constraint.ConstraintLayout>
