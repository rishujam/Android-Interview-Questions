Hi I want to talk to you regarding your internship experience at Tax Salah or Insponce.
You can send msg on my linkedin or mail me.
Thank you.

__No of questions: 60+__

__Kotlin Questions:__

Q. Explain all scope function and its usecase ?</br>
Ans -> https://www.youtube.com/watch?v=Vy-dS2SVoHk&ab_channel=PhilippLackner

Q. lazy vs lateinit

Q. High order functions</br>
Ans -> https://www.youtube.com/watch?v=ZZuPgOhgQHc&ab_channel=SimplifiedCoding</br>
       https://proandroiddev.com/kotlin-pearls-lambdas-with-a-context-58f26ab2eb1d

Q. What is Trailing lamda</br>

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

Q. passing vararg as parameter vs passing a list

Q. is, as, as?, in, out

Q. Extension vs inline vs inflix vs high order function there benefit in term of memory.

Q. operator keyword

Q. if(i != null) vs i?.let{}

Q. use of ::</br>
Ans -> https://stackoverflow.com/questions/47400942/what-does-mean-in-kotlin

Q. Elvis operator

Q. Difference between volatile and syncronized.</br>
Ans -> https://blog.knoldus.com/difference-between-synchronized-and-volatile-in-java/

Q. run{} vs runBlocking{}

Q. what is use of Anonymous classes? Example</br>
Ans -> https://www.youtube.com/watch?v=1dKsPrEcUFY&ab_channel=PhilippLackner

Q. enum vs sealed class

Q. Normal nested class vs nested class with inner keyword</br>
Ans -> https://www.youtube.com/watch?v=3bCqDGcfpP0&ab_channel=PRABEESHRK

Q. external, internal</br>
Ans -> External: The external keyword in Kotlin is the same as the native keyword in Java. Both mean the implementation of the method comes from the native library.</br>
Internal: The internal visibility modifier means that the member is visible within the same module.

Q. Questions based on lamda function in different situations.

Q. Interface vs abstract 

Q. What is referential equality( === ) and structal equality( == )

Q. Questions based on coroutine scopes

Q. What is coroutines dispatchers there type and work.

Q. What is coroutines context.

Q. What is coroutines builder, its type and there work.

Q. Difference between Default and IO Dispatchers.

Q. async, await, awaitAll

Q. Flows vs live data, uses of flow when and when live data

Q. How to make singleton class in java?

Q. kotlin Deligation</br>
Ans -> https://www.youtube.com/watch?v=MfJB-JhRAoQ&ab_channel=PhilippLackner

__General Questions:__

Q. SOLID Principles

__Android Questions:__

Q. Activity lifecycle when call comes?</br>
Ans -> onPause and onStop. After call cut onRestart onStart onResume

Q. Which activity life cycle method trigger when orientation change?</br>
Ans -> onPause() -> onSaveInstanceState() -> onStop() -> onDestroy()
       onCreate() -> onStart() -> onResume()
       
Q. Lets say we opened 3 activites (A,B,C) one after another and C is on top and A was the first activity. When we close activity C we want to send data to activity A. How can we do it in different ways.

Q. How recycler view works internally? Cons of recycler view.</br>
Ans -> https://medium.com/1mgofficial/how-recyclerview-works-internally-71290de5d2c4

Q. Why Single activity app?</br>
Ans -> https://oozou.com/blog/reasons-to-use-android-single-activity-architecture-with-navigation-component-36

Q. When onDestroy will get called before onPause or onStop?</br>
Ans -> When their is an exception in onCreate/onPause/onResume nothing gets called and when we call finish() only onDestroy is called.

Q. How room works internally

Q. What are interceptors

Q. In which project will you use data binding and in which viewBinding?

Q. Diff between MVVM and MVVM Clean

Q. Why MVVM, Difference between MVVM and other arch patterns

Q. Launch mode and there type and differences.</br>
Ans -> https://medium.com/mindorks/android-launch-mode-787d28952959

Q. Lifetime of object class</br>
Short Ans -> Till the app lives</br>
Detailed Ans -> https://stackoverflow.com/questions/1944369/android-static-object-lifecycle/1944564#1944564

Q. Dagger Hilt @Singleton vs object class

Q. What is use of DI?
Ans -> Manage scope of object easily, easy testing, managing dependencies easily

Q. Constraint layout groups</br>
Ans -> https://stackoverflow.com/questions/42118674/how-to-group-multiple-views-in-a-constraintlayout

Q. Diff between virtual back button of android system and back button of toolbar inside the app.

Q. What are Intent Service

Q. What is pending intent

Q. How to inject interface</br>
Ans -> https://write.agrevolution.in/dependency-injection-with-hilt-part-2-ee5fea58bab2

Q. DI Qualifiers</br>
Ans -> https://blog.mindorks.com/dagger-hilt-tutorial

Q. Use of Application class

Q. Design and architecture patterns</br>
Ans -> Design: https://blog.mindorks.com/mastering-design-patterns-in-android-with-kotlin

Q. Types of Services?

Q. Broadcast receiver

Q. What is use of channels in android

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

Q. Desgin Patterns</br>
Ans -> https://blog.mindorks.com/mastering-design-patterns-in-android-with-kotlin/

Q. What is difference between using supportFragmentManager and nav component for navigation?

Q. How to clear all the activites in the backstack and open new


__Scenario based questions__

Q. Whats wrong in this code ?</br>
```
companion object {
    val retrofit = Retrofit.Builder()
        .baseUrl(BASE_URL)
        .addConverterFactory(GsonConverterFactory.create())
        .build()
    const val BASE_URL = "https://api.openai.com/"
}
```

Q. I am using nav component in my app there are 5 activities in my app 1 is the home activity (containing 4 buttons) where I am currently on. When i click on button multiple times all 3 buttons work fine and redirect me to their respective activity. But the 4th button creates multiple instances of the activity (implementation to navigation is same for all 4 buttons) What could be the possible cause of this bug?

