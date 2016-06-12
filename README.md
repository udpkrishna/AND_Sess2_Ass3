<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="me.rk.linearlayoursess2ass3.MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Credit Card Helper"
        android:id="@+id/textView"
        android:layout_alignParentTop="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentEnd="true"
        android:background="@color/GG"
        android:textColor="@color/bright_foreground_inverse_material_light" />

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_below="@+id/textView"
        android:layout_alignParentStart="false"
        android:background="@color/abc_search_url_text_pressed"
        android:rowCount="30"
        android:columnCount="5">

        <CheckedTextView
            android:layout_width="wrap_content"
            android:layout_height="52dp"
            android:textAppearance="?android:attr/textAppearanceSmall"
            android:text="Enter Card Balance ($)"
            android:id="@+id/textView2"
            android:layout_row="2"
            android:layout_column="3"
            android:phoneNumber="true"
            android:textColor="@color/abc_primary_text_disable_only_material_dark"
            android:layout_alignParentLeft="true"
            android:layout_marginLeft="0dp"
            android:layout_alignParentTop="true"
            android:layout_marginTop="0dp" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="52dp"
            android:textAppearance="?android:attr/textAppearanceSmall"
            android:text="Enter Yearly Interest Rate (%)"
            android:id="@+id/textView3"
            android:layout_row="4"
            android:layout_column="3"
            android:phoneNumber="true"
            android:textColor="@color/abc_primary_text_disable_only_material_dark"
            android:layout_below="@+id/textView2"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="52dp"
            android:textAppearance="?android:attr/textAppearanceSmall"
            android:text="Enter Minimum Payment ($)"
            android:id="@+id/textView4"
            android:layout_row="6"
            android:layout_column="3"
            android:phoneNumber="true"
            android:textColor="@color/abc_primary_text_disable_only_material_dark"
            android:layout_below="@+id/textView3"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="52dp"
            android:textAppearance="?android:attr/textAppearanceSmall"
            android:text="Final Card Balance ($)"
            android:id="@+id/textView5"
            android:layout_row="10"
            android:layout_column="3"
            android:phoneNumber="true"
            android:textColor="@color/abc_primary_text_disable_only_material_dark"
            android:layout_below="@+id/textView4"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="52dp"
            android:textAppearance="?android:attr/textAppearanceSmall"
            android:text="Months Remaining"
            android:id="@+id/textView6"
            android:layout_row="12"
            android:layout_column="3"
            android:phoneNumber="true"
            android:textColor="@color/abc_primary_text_disable_only_material_dark"
            android:layout_centerVertical="true"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="52dp"
            android:textAppearance="?android:attr/textAppearanceSmall"
            android:text="Interest Paid Will Be ($)"
            android:id="@+id/textView7"
            android:layout_row="22"
            android:layout_column="3"
            android:phoneNumber="true"
            android:textColor="@color/abc_primary_text_disable_only_material_dark"
            android:layout_below="@+id/textView6"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true" />

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Compute"
            android:id="@+id/button"
            android:layout_above="@+id/button2"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true"
            android:layout_alignParentRight="true"
            android:layout_alignParentEnd="true" />

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Clear"
            android:id="@+id/button2"
            android:layout_alignParentBottom="true"
            android:layout_alignRight="@+id/editText6"
            android:layout_alignEnd="@+id/editText6"
            android:layout_marginBottom="28dp"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="number"
            android:ems="10"
            android:id="@+id/editText"
            android:layout_alignParentTop="true"
            android:layout_toRightOf="@+id/textView3"
            android:layout_toEndOf="@+id/textView3"
            android:layout_marginLeft="24dp"
            android:layout_marginStart="24dp"
            android:background="@color/G"
            android:layout_alignBottom="@+id/textView2"
            android:layout_marginBottom="10dp"
            android:layout_marginTop="5dp" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="number"
            android:ems="10"
            android:id="@+id/editText2"
            android:background="@color/G"
            android:layout_alignBottom="@+id/textView3"
            android:layout_alignLeft="@+id/editText"
            android:layout_alignStart="@+id/editText"
            android:layout_alignTop="@+id/textView3"
            android:layout_marginBottom="10dp" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="number"
            android:ems="10"
            android:id="@+id/editText3"
            android:background="@color/G"
            android:layout_below="@+id/textView3"
            android:layout_alignLeft="@+id/editText2"
            android:layout_alignStart="@+id/editText2"
            android:layout_alignBottom="@+id/textView4"
            android:layout_marginBottom="10dp" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="number"
            android:ems="10"
            android:id="@+id/editText4"
            android:background="@color/G"
            android:layout_below="@+id/editText3"
            android:layout_alignLeft="@+id/editText3"
            android:layout_alignStart="@+id/editText3"
            android:layout_above="@+id/textView6"
            android:layout_marginBottom="10dp" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="number"
            android:ems="10"
            android:id="@+id/editText5"
            android:background="@color/G"
            android:layout_below="@+id/textView5"
            android:layout_alignLeft="@+id/editText4"
            android:layout_alignStart="@+id/editText4"
            android:layout_above="@+id/textView7"
            android:layout_marginBottom="10dp" />

        <EditText
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:inputType="number"
            android:ems="10"
            android:id="@+id/editText6"
            android:background="@color/G"
            android:layout_alignBottom="@+id/textView7"
            android:layout_alignLeft="@+id/editText5"
            android:layout_alignStart="@+id/editText5"
            android:layout_alignTop="@+id/textView7"
            android:layout_marginBottom="10dp" />

    </RelativeLayout>

</RelativeLayout>
