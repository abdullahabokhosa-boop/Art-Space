# Art-Space
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center_horizontal"
    android:orientation="vertical"
    android:padding="16dp">

    <TextView
        android:id="@+id/tvCounter"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/_1_6"
        android:textSize="18sp"
        tools:ignore="VisualLintSystemUi" />

    <ImageView
        android:id="@+id/ivArtwork"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_marginTop="16dp"
        android:layout_marginBottom="16dp"
        android:layout_weight="6"
        android:contentDescription="@string/artwork"
        android:scaleType="centerCrop" />

    <TextView
        android:id="@+id/tvTitle"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/artwork_title"
        android:textSize="22sp" />

    <TextView
        android:id="@+id/tvArtistYear"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="6dp"
        android:layout_marginBottom="16dp"
        android:text="@string/artist_name_year"
        android:textSize="16sp" />

    <LinearLayout
        style="?android:attr/buttonBarStyle"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:id="@+id/btnPrevious"
            style="?android:attr/buttonBarButtonStyle"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginEnd="8dp"
            android:layout_weight="1"
            android:text="@string/previous"
            tools:ignore="VisualLintButtonSize" />

        <Button
            android:id="@+id/btnNext"
            style="?attr/borderlessButtonStyle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="@string/next" />


    </LinearLayout>

</LinearLayout>
