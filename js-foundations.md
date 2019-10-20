# ASSESSMENT 2: FOUNDATIONS OF JAVASCRIPT
## Interview Practice Questions

### Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.

Consider the function:

var text = 'outside'
function logIt(){
  console.log(text)
  var text = 'inside'
}
logIt()


1a. Look at this Javascript function and try to predict what the console show.
it will log undefined


1b. Test the function. Explain why the function returned what it did.

  Your answer: text in the logIt() function is not defined because of scoping

  Researched answer: if var text wasn't declared inside the function then it would just log 'outside'; b/c it is defined inside the function
  it will log undefined; if text in logIt() was a let then it would throw an error instead


2. What is JSON?

  Your answer: javascript object notation

  Researched answer: javascript object notation


3. What does CRUD stand for?

  Your answer: create/read/update/delete

  Researched answer: create/read/update/delete



4. What does are the 5 HTTP verbs?

  Your answer: pull/get/push/put/delete

  Researched answer: pull->analogous to create; get-> analogous to read; push/put->analogous to update; delete->analogous to delete


5. What is a higher-order function?

  Your answer: a function that can take a function as an argument

  Researched answer: a function that can take a function as an argument or returns a function as a result


6. STRETCH: What is a closure, what is it good for and how do you recognize one?

  Your answer: curly braces

  Researched answer: global variables (variables defined with var) can be made local by using closures


7. STRETCH: What is an API?

  Your answer: Application programming interface

  Researched answer: Application programming interface; it connects a server to a client and its goal is to simplify the building of client-side software


### Additional Feedback Questions.

1. Do you have a suggestion for a Check In question?
If you could live in 1 era in history what would it be and why? 


2. What was your favorite topic this week?
learning about making React classes


3. What was your "A-ha!" moment this week?
I guess learning about react classes and just thinking about what we can do with them.  It's going to be a lot of fun