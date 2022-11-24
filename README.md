__No of questions: 63__

__Kotlin Questions:__

Q. Explain all scope function and its usecase ?</br>
Ans -> https://www.youtube.com/watch?v=Vy-dS2SVoHk&ab_channel=PhilippLackner

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

Q. const, val, var, companion object and object (Use and difference)</br>
Ans -> var - mutable variables</br>
       val - immutable variable assigned at runtime</br>
       const val - assigned at compile time</br>
       companion object - Inside this block we can define static variables/function inside classes/files.</br>
       object - Used to make singleton classes ( inside this class all functions and variables will be static )</br>

Q. Use of open (Inheritence in kotlin vs java)

Q. Use of vararg

Q. is, as, as?, in 

Q. Extension vs inline vs inflix vs high order function there benefit in term of memory.

Q. if(i != null) vs i?.let{}

Q. use of ::

Q. Elvis operator

Q. Difference between volatile and syncronized.

Q. run{} vs runBlocking{}

Q. Anonymous classes

Q. enum vs sealed class

Q. external, internal, inner keyword

Q. Questions based on lamda function in different situations.

Q. Interface vs abstract 

Q. What is referential equality( === ) and structal equality( == )

Q. Questions based on coroutine scopes

Q. What is coroutines dispatchers there type and work.

Q. What is coroutines context.

Q. What is coroutines builder, its type and there work.

Q. async, await, awaitAll

Q. Flows vs live data, uses of flow when and when live data

Q. How to make singleton class in java?

Q. What is Delegates class used for

__General Questions:__

Q. SOLID Principles

__Android Questions:__

Q. Activity lifecycle when call comes?</br>
Ans -> onPause and onStop. After call cut onRestart onStart onResume

Q. Which activity life cycle method trigger when orientation change?</br>
Ans -> onPause() -> onSaveInstanceState() -> onStop() -> onDestroy()
       onCreate() -> onStart() -> onResume()
       
Q. Lets say we opened 3 activites (A,B,C) one after another and C is on top and A was the first activity. When we close activity C we want to send data to activity A. How can we do it in different ways.

Q. How recycler view works internally? Cons of recycler view.

Q. Why Single activity app?</br>
Ans -> https://oozou.com/blog/reasons-to-use-android-single-activity-architecture-with-navigation-component-36

Q. When onDestroy will get called before onPause or onStop?</br>
Ans -> When their is an exception in onCreate/onPause/onResume nothing gets called and when we call finish() only onDestroy is called.

Q. How room works internally

Q. What are interceptors

Q. In which project will you use data binding and in which viewBinding?

Q. Diff between MVVM and MVVM Clean

Q. Why MVVM, Difference between MVVM and other arch patterns

Q. Launch mode and there type and differences.

Q. Constraint layout groups

Q. Diff between virtual back button of android system and back button of toolbar inside the app.

Q. What are Intent Service

Q. What is pending intent

Q. How to inject interface

Q. DI Qualifiers

Q. Design and architecture patterns

Q. Types of Services?

Q. Broadcast receiver

Q. How to start a service through Broadcast receiver and vice versa

Q. How viewModel works internally and retain data during configuration change (Even after actiivty destroys and recreate in config change viewModels maintain itself)

Q. Concept of viewModel factory

Q. Concept of shared view model and how to implement it.

Q. ViewModel vs AndroidViewModel

Q. Activities, fragment back stack

Q. Passing data from activities to fragment

Q. Types of intent which is used when

Q. How to communicate between service and activity

Q. What is job scheduler and its work.

Q. Memory leaks identification

Q. Major factors app performance depends upon


