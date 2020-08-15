# Android_Espresso

Object:
table view , spinner view , list view , grid view , swipe up or down , recycle view

Locate current element:
1.Hamcrest Match + ID , text, classname , contentdiscription
2.Custom Match , override 2 methods to get more details. like font, hint, color etc.
3.OnView().Perform().check(matches(withText("string")))    ==   view_match.view_action_view_assertion
4.OnDate(withText(constainString)("Espresso")))

Process:
@Rule  mainactivity
@Before
@After
@Test

Asynchronous work:
Thread.Sleep(2000)


