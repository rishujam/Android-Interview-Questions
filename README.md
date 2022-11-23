__This repository is for intern level interview questions for android role.__

__Kotlin Questions:__

Q. Explain all scope function and its usecase ?</br>
Ans -> https://www.youtube.com/watch?v=Vy-dS2SVoHk&ab_channel=PhilippLackner

Q. How to make singleton class in java?</br>
Ans -> Ans in SingletonClassInJavaAnswer file.

Q. lazy vs lateinit

Q. High order functions</br>
Ans -> https://www.youtube.com/watch?v=ZZuPgOhgQHc&ab_channel=SimplifiedCoding</br>
       https://proandroiddev.com/kotlin-pearls-lambdas-with-a-context-58f26ab2eb1d

Q. What is Trailing lamda</br>
Ans -> https://youtu.be/ZZuPgOhgQHc?t=397

Q. Unit, Nothing, Any</br>
Ans -> https://medium.com/proandroiddev/kotlin-pearls-7-unit-nothing-any-and-null-cbbbbca86c2d

Q. What is internal keyword use?</br>
Ans -> Setting a declaration as internal means that it'll be available in the same module only.

Q. Flows vs live data, uses of flow when and when live data

Q. const, val, var, companion object and object (Use and difference)

Q. Use of open (Inheritence in kotlin vs java)

Q. Use of vararg

Q. is, as, as?, in 

Q. inline, infix

Q. if(i != null) vs i?.let{}

Q. use of ::

Q. Elvis operator

Q. Different classes in kotlin (sealed, object, data, etc.)

Q. external, internal, inner keyword

Q. Questions based on lamda function in different situations.

Q. Interface vs abstract 

Q. Extention functions

Q. Coroutines uses in different situation like using coroutine scope block, async block, await, await all, etc.

__General Questions:__

Q. SOLID Principles

__Android Questions:__

Q. Activity lifecycle when call comes?</br>
Ans -> onPause and onStop. After call cut onRestart onStart onResume

Q. Which activity life cycle method trigger when orientation change?</br>
Ans -> onPause() -> onSaveInstanceState() -> onStop() -> onDestroy()
       onCreate() -> onStart() -> onResume()

Q. DI Qualifiers

Q. Things you thinks recyclerview can improve on

Q. Why Single activity app?</br>
Ans -> https://oozou.com/blog/reasons-to-use-android-single-activity-architecture-with-navigation-component-36

Q. When onDestroy will get called before onPause or onStop?</br>
Ans -> When their is an exception in onCreate/onPause/onResume nothing gets called and when we call finish() only onDestroy is called.

Q. How room works

Q. How retrofit works 

Q. In which project will you use data binding and in which viewBinding?

Q. Diff between MVVM and MVVM Clean

Q. Why MVVM

Q. Types of Services?

Q. Broadcast receiver

Q. How to start a service through Broadcast receiver and vice versa

Q. Work of ViewModel

Q. Activities, fragment back stack

Q. passing data between activities present in backstack

Q. Constraint layout groups

Q. Types of intent

Q. Intent Service

Q. How to inject interface

Q. Design and architecture patterns

Q. Async Await 

__Additional resources__

Kotlin all modifiers and keywords- https://kotlinlang.org/docs/keyword-reference.html#hard-keywords
