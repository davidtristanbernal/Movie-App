# Movie-App
An application for movies
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout
 xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent">
 <ImageView
 android:id="@+id/imageView"
 android:layout_width="150dp"
 android:layout_height="150dp"
 android:layout_marginEnd="8dp"
 android:layout_marginLeft="8dp"
 android:layout_marginRight="8dp"
 android:layout_marginStart="8dp"
 android:layout_marginTop="20dp"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toTopOf="parent"
 app:srcCompat="@drawable/logo" />
 <Button
 android:id="@+id/buttonCreateMovie"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentLeft="true"
 android:layout_alignParentTop="true"
 android:layout_marginEnd="8dp"
 android:layout_marginLeft="8dp"
 android:layout_marginRight="8dp"
 android:layout_marginStart="8dp"
 android:layout_marginTop="28dp"
 android:text="Create Movie"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/imageView" />
<TextView
 android:id="@+id/textViewRecordCount"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginEnd="8dp"
 android:layout_marginLeft="8dp"
 android:layout_marginRight="8dp"
 android:layout_marginStart="8dp"
 android:layout_marginTop="24dp"
 android:gravity="center"
 android:text="0 records found"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/buttonCreateMovie" />
 <ScrollView
 android:id="@+id/scrollViewMovies"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:layout_marginEnd="8dp"
 android:layout_marginRight="8dp"
 android:layout_marginTop="10dp"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/textViewRecordCount">
 <LinearLayout
 android:id="@+id/linearLayoutMovies"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:orientation="vertical" />
 </ScrollView>
</android.support.constraint.ConstraintLayout>
