__This repository is for intern level interview questions for android role.__
__No of questions: 63__

__Kotlin Questions:__

Q1. Explain all scope function and its usecase ?</br>
Ans -> https://www.youtube.com/watch?v=Vy-dS2SVoHk&ab_channel=PhilippLackner

Q2. How to make singleton class in java?</br>
Ans -> Ans in SingletonClassInJavaAnswer file.

Q3. lazy vs lateinit

Q4. High order functions</br>
Ans -> https://www.youtube.com/watch?v=ZZuPgOhgQHc&ab_channel=SimplifiedCoding</br>
       https://proandroiddev.com/kotlin-pearls-lambdas-with-a-context-58f26ab2eb1d

Q5. What is Trailing lamda</br>
Ans -> https://youtu.be/ZZuPgOhgQHc?t=397

Q6. Unit, Nothing, Any</br>
Ans -> https://medium.com/proandroiddev/kotlin-pearls-7-unit-nothing-any-and-null-cbbbbca86c2d

Q7. What is internal keyword use?</br>
Ans -> Setting a declaration as internal means that it'll be available in the same module only.

Q8. Flows vs live data, uses of flow when and when live data

Q9. const, val, var, companion object and object (Use and difference)

Q10. Use of open (Inheritence in kotlin vs java)

Q11. Use of vararg

Q12. is, as, as?, in 

Q13. Extension vs inline vs inflix vs high order function there benefit in term of memory.

Q14. if(i != null) vs i?.let{}

Q15. use of ::

Q16. Elvis operator

Q17. Difference between volatile and syncronized.

Q18. run{} vs runBlocking{}

Q19. What is Delegates class used for

Q20. Anonymous classes

Q21. enum vs sealed class

Q22. external, internal, inner keyword

Q23. Questions based on lamda function in different situations.

Q24. Interface vs abstract 

Q25. What is referential equality( === ) and structal equality( == )

Q26. Questions based on coroutine scopes

Q27. What is coroutines dispatchers there type and work.

Q28. What is coroutines context.

Q29. What is coroutines builder, its type and there work.

Q30. async, await, awaitAll

__General Questions:__

Q31. SOLID Principles

__Android Questions:__

Q32. Activity lifecycle when call comes?</br>
Ans -> onPause and onStop. After call cut onRestart onStart onResume

Q33. Which activity life cycle method trigger when orientation change?</br>
Ans -> onPause() -> onSaveInstanceState() -> onStop() -> onDestroy()
       onCreate() -> onStart() -> onResume()

Q34. DI Qualifiers

Q35. How recycler view works internally? Cons of recycler view.

Q36. Why Single activity app?</br>
Ans -> https://oozou.com/blog/reasons-to-use-android-single-activity-architecture-with-navigation-component-36

Q37. When onDestroy will get called before onPause or onStop?</br>
Ans -> When their is an exception in onCreate/onPause/onResume nothing gets called and when we call finish() only onDestroy is called.

Q38. How room works

Q39. How retrofit works 

Q40. Memory leaks identification

Q41. In which project will you use data binding and in which viewBinding?

Q42. Diff between MVVM and MVVM Clean

Q43. Why MVVM

Q44. Launch mode and there type and differences.

Q45. Types of Services?

Q46. Broadcast receiver

Q47. How to start a service through Broadcast receiver and vice versa

Q48. How viewModel works internally and retain data during configuration change (Even after actiivty destroys and recreate in config change viewModels maintain itself)

Q49. Concept of viewModel factory

Q50. Concept of shared view model and how to implement it.

Q51. ViewModel vs AndroidViewModel

Q52. Activities, fragment back stack

Q53. Lets say we opened 3 activites (A,B,C) one after another and C is on top and A was the first activity. When we close activity C we want to send data to activity A. How can we do it in different ways.

Q54. Passing data from activities to fragment

Q55. Constraint layout groups

Q56. Types of intent which is used when

Q57. Diff between virtual back button of android system and back button of toolbar inside the app.

Q58. Intent Service

Q59. How to communicate between service and activity

Q60. What is job scheduler and its work.

Q61. How to inject interface

Q62. Design and architecture patterns

Q63. Major factors app performance depends on 

__Additional resources__

Kotlin all modifiers and keywords- https://kotlinlang.org/docs/keyword-reference.html#hard-keywords
