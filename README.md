# 实验内容

此实验为表格布局的练习

# 关键代码

<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

​    <TableRow
​        android:layout_width="wrap_content"
​        android:layout_height="match_parent">

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="4"
​            android:text="@string/open" />

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="1"
​            android:text="@string/Ctrlo" />
​    </TableRow>

​    <TableRow
​        android:layout_width="wrap_content"
​        android:layout_height="match_parent">

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="4"
​            android:text="@string/save" />

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="1"
​            android:text="@string/ctrls" />
​    </TableRow>

​    <TableRow
​        android:layout_width="wrap_content"
​        android:layout_height="match_parent">

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="4"
​            android:text="@string/saveas" />

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="1"
​            android:text="@string/ctrlshifts" />
​    </TableRow>

​    <TableRow
​        android:layout_width="wrap_content"
​        android:layout_height="match_parent">

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="4"
​            android:text="@string/Import" />
​    </TableRow>

​    <TableRow
​        android:layout_width="wrap_content"
​        android:layout_height="match_parent">

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="4"
​            android:text="@string/export" />

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="1"
​            android:text="@string/ctrle" />
​    </TableRow>

​    <TableRow
​        android:layout_width="wrap_content"
​        android:layout_height="match_parent">

​        <TextView
​            android:layout_width="wrap_content"
​            android:layout_height="50dp"
​            android:layout_weight="4"
​            android:text="@string/quit" />
​    </TableRow>

</TableLayout>

# 结果截图

![1552651144092](https://i.loli.net/2019/03/16/5c8d145f3fad4.png)