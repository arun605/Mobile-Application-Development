# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:
```

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.
```

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by:DHANUSH.G.R.
Registeration Number :212221040038
*/ep 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.


PROGRAM:
/*
Program to print the text “Hello World”.
Developed by:ARUN KUMAR.V.P
Registeration Number :212221040019
*/```
## activity_main.xml :
```
<?xml version="1.0" encoding="utf-8"?>

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    
    xmlns:app="http://schemas.android.com/apk/res-auto"
    
    xmlns:tools="http://schemas.android.com/tools"
    
    android:layout_width="match_parent"
    
    android:layout_height="match_parent"
    
    android:rotationX="8"
    
    tools:context=".MainActivity">

    <TextView
    
        android:id="@+id/textView"
        
        android:layout_width="271dp"
        
        android:layout_height="54dp"
        
        android:layout_marginStart="156dp"
        
        android:layout_marginEnd="176dp"
        
        android:text="HELLO WORLD"
        
        android:textSize="40dp"
        
        app:layout_constraintEnd_toEndOf="parent"
        
        app:layout_constraintHorizontal_bias="0.491"
        
        app:layout_constraintStart_toStartOf="parent"
        
        tools:layout_editor_absoluteY="312dp" />


</androidx.constraintlayout.widget.ConstraintLayout>
```

## MainActivity.java :
```
package com.example.androidlifecycle;

import androidx.appcompat.app.AppCompatActivity;

import android.annotation.SuppressLint;

import android.os.Bundle;

import android.widget.Toast;

public class MainActivity extends AppCompatActivity

{

    @Override
    
    protected void onCreate(Bundle savedInstanceState)
    
    {
    
        super.onCreate(savedInstanceState);
        
        setContentView(R.layout.activity_main);
        
        Toast.makeText(getApplicationContext(), "On Create Called", Toast.LENGTH_SHORT).show();
    
    }
    
    protected void onStart()
    
    {
    
        super.onStart();
        
        Toast.makeText(getApplicationContext(), "On Start Called ", Toast.LENGTH_SHORT).show();



    }
    
    protected void onRestart()
    
    {
    
        super.onRestart();
        
        Toast.makeText(getApplicationContext(), "On Restart Called", Toast.LENGTH_SHORT).show();
    }
    
    
    protected void onResume()
    
    {
    
        Toast.makeText(getApplicationContext(), "On Resume Called", Toast.LENGTH_SHORT).show();
        super.onResume();
    }
    
    
    protected void onStop()
    {
    
        super.onStop();
        
        Toast.makeText(getApplicationContext(), "On Stop Called", Toast.LENGTH_SHORT).show();
    }
    
    
    protected void onPause()
    
    {
    
        super.onPause();
        
        Toast.makeText(getApplicationContext(), "On Pause Called", Toast.LENGTH_SHORT).show();
    }
    
    
    protected void onDestroy()
    
    {
    
        super.onDestroy();
        
        
        Toast.makeText(getApplicationContext(), "On Destroy Called", Toast.LENGTH_SHORT).show();
    }
    
}
```

## OUTPUT

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/acec8471-12b0-4d60-9613-9d8c5cfc3915)

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/f2a4d23c-1f6f-4715-ab21-576a77e01b99)

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/dc20dbf7-bfb8-4cd1-8cd8-68e7912e8b6f)

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/7dcf301d-347b-4f33-a377-158796431fad)

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/cfba464f-78a6-47b8-834a-bc744bca66bc)

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/a077eb70-e681-4b33-b79e-1b37e16294fe)

![image](https://github.com/arun605/Mobile-Application-Development/assets/118738931/842148a5-f9d5-40f9-86ce-ea12ad0f50aa)


## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
