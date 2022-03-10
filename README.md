TrackMySleepQuality - Starter Code
==================================

Starter code for Android Kotlin Fundamentals Codelab 6.1 Room

Introduction
------------

TrackMySleepQuality is an app for recording sleep data for each night. 
You can record a start and stop time, assign a quality rating, and clear the database. 

In this codelab, working from this starter app,
you will implement the Room database that holds the sleep data. 
You will then use instrumented tests to verify that this backend works. 


Pre-requisites
--------------

You need to know:

* Building a basic user interface (UI) for an Android app, 
  using an activity, fragments, and views.
* Navigating between fragments and using Safe Args (a Gradle plugin) 
  to pass data between fragments.
* View models, view-model factories, and LiveData and its observers. 
  These Architecture Components topics are covered in an earlier codelab in this course.
* A basic understanding of SQL databases and the SQLite language.


Getting Started
---------------

1. Download and run the app.

License
-------

Copyright 2019 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

------------------------------------------------------------

### CODELAB: Android Kotlin Fundamentals: Create a Room Database - https://developer.android.com/codelabs/kotlin-android-training-room-database#0

#### **What I learned:**</br>

- How to create and interact with a Room database to persist data.
- How to create a data class that defines a table in the database.
- How to use a data access object (DAO) to map Kotlin functions to SQL queries.
- How to test whether your database is working.


#### **What I did:**</br>

- Create a Room database with an interface for nightly sleep data.
- Test the database using the provided tests.


------------------------------------------------------------

### CODELAB: Android Kotlin Fundamentals: 6.2 Coroutines and Room - https://developer.android.com/codelabs/kotlin-android-training-coroutines-and-room#0

#### **What I learned:**</br>

- How threads work in Android.
- How to use Kotlin coroutines to move database operations away from the main thread.
- How to display formatted data in a TextView.

#### **What I did:**</br>

- Extend the TrackMySleepQuality app to collect, store, and display data in and from the database.
- Use coroutines to run long-running database operations in the background.
- Use LiveData to trigger navigation and the display of a snackbar.
- Use LiveData to enable and disable buttons.
