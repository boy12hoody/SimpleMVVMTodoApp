<h1 align="center">Simple MVVM ToDo App</h1>
<p align="center">
A simple todo app based on MVVM architecture.<br>
Re-upload of the old project for demonstration purposes.

</p>

<p align="center">
  <a href="https://android-arsenal.com/api?level=21"><img alt="API" src="https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat"/></a>
  <a href="https://github.com/boy12hoody/SimpleMVVMTodoApp/actions/workflows/android.yml"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/boy12hoody/SimpleMVVMTodoApp/Build%20&%20Publish%20Debug%20APK"/></a>
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/github/license/boy12hoody/SimpleMVVMTodoApp"/></a>
  <a href="https://t.me/boywonder"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-@BoyWonder-blue.svg?style=flat&logo=telegram"/></a>
</p>

### Screenshots
<p align="center">
<img src="https://user-images.githubusercontent.com/70273198/128517050-b8ba0d21-9977-4fe2-b90e-5a8126b2f9cd.jpg" width="30%"/>
<img src="https://user-images.githubusercontent.com/70273198/128517059-a288d9c1-21cb-4a72-b485-0ff6ce31c8cc.jpg" width="30%"/>
<img src="https://user-images.githubusercontent.com/70273198/128517062-c9ae4e60-0453-4fc7-91bf-ccef56d35d3c.jpg" width="30%"/>
<img src="https://user-images.githubusercontent.com/70273198/128517063-9219a3de-76ce-4d31-bce4-98ede3e9d2d6.jpg" width="30%"/>
<img src="https://user-images.githubusercontent.com/70273198/128517067-2b6517ef-57fe-40e8-a1db-41938c878a80.jpg" width="30%"/>
</p>

## Download
Go to the [Releases](https://github.com/boy12hoody/SimpleMVVMTodoApp/releases) to download the latest APK.

## 🛠 Tech stack & Open-source libraries
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more..
- [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/-flow/) - A cold asynchronous data stream that sequentially emits values and completes normally or with an exception.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [Jetpack](https://developer.android.com/jetpack) -
    - [DataStore](https://developer.android.com/topic/libraries/architecture/datastore)
    - [Navigation](https://developer.android.com/guide/navigation)
    - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - Data objects that notify views when the underlying database changes.
    - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes.
    - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
    - [Room](https://developer.android.com/topic/libraries/architecture/room) - SQLite object mapping library.
- [Dependency Injection](https://developer.android.com/training/dependency-injection) -
  - [Hilt-Dagger](https://dagger.dev/hilt/) - Standard library to incorporate Dagger dependency injection into an Android application.
  - [Hilt-ViewModel](https://developer.android.com/training/dependency-injection/hilt-jetpack) - DI for injecting `ViewModel`.
- [Material Components for Android](https://material.io/develop/android/docs/getting-started/) - Modular and customizable Material Design UI components for Android.

## Architecture
This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

## MAD Score
![jetpack](https://user-images.githubusercontent.com/70273198/128502827-e473c313-6403-4c0a-81c6-c0e21af7772a.png)
![kotlin](https://user-images.githubusercontent.com/70273198/128502828-7ed38c7c-d891-4245-9d38-ff6440c5ca97.png)

## Contact
If you have questions or need any help, contact me on
[![Telegram](https://img.shields.io/badge/Telegram-@BoyWonder-blue.svg?style=flat&logo=telegram)](https://t.me/boywonder)

# License
```
MIT License

    Copyright (c) 2021 Ismatov Xurshid

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
```
