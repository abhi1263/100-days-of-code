# 100 Days Of Code - Log

### Day 0: July 21, 2020 

**Today's Progress**: Environment setup, installed libraries and dependencies, subscribed to courses

**Thoughts:** I am really excited as well as nervous to take up this challenge. But I know, I have the willpower to complete it

**Link to work:** [None]

### Day 1: July 22, 2020 

**Today's Progress**: Started working on a Todo list. Done with 'add task' functionality

**Thoughts:** Since today being the first day, it took me a lot of time and errors to finally complete one functionality. Hopeful for the next days

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)(
[commitId](https://github.com/abhi1263/learningDjango/commit/88e5fc89528f1523be2149380a444c5f0899f14a))

### Day 2: July 23, 2020 

**Today's Progress**: Added the edit functionality

**Thoughts:** I am using simple HTML form. After completing CRUD functionalities, will try it with Django forms

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/2b932db1d2b67010bf4babda59eca5703549b3a9))

### Day 3: July 24, 2020 

**Today's Progress**: Added the delete functionality, thus completing the simple ToDo application with basic CRUD operation

**Future scope:** 
1. To learn about Django forms and integrate with Django forms. 
2. Learn basic testing and implement unit testing of the app

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/94f7880d518df85ad85b4450912ddffacd8784ea))


### Day 4: July 25, 2020 

**Today's Progress**: Created a new branch on the master repo. Added the task status update functionality. 

**Description:** 
When a task is done and checkbox is clicked, a ajax call is fired which changes the status of the task and refreshes the page.
Scope of improvement: This ajax call is redundant, as the page is getting refreshed anyway, to display the changes. Would work on simplying the code and reduce the number of calls to server.

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/e1e8b789ef9a6d5e99955adee3bb537e00657a2a))


### Day 5: July 26, 2020 

**Today's Progress**: Removed the ajax call for updating task status. Instead, made a form which autosubmits on checkbox click 

**Description:** 
When user clicks on the checkbox, form is autosubmitted and the status of the task is updated.

**Further scope**: Implement user authorization/authentication, unit testing


### Day 6: July 27, 2020 

**Today's Progress**: Removed the reduntant view 'edit_task_save' 

**Description:** 
That view was unnecessary because it could be combined in one single view. Now the 'edit_task' view firstly fetches task details and passes it to the form template and then saves the data from the form template to the database.

**Further scope**: Same as before

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/5a6dacec934c6d8b0372c1ed590330460e8526e2))


### Day 7: July 28, 2020 

**Today's Progress**: Added 'requirements.txt'

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/670a95a9a71a520cede8d6806222ef9005d051bb))


### Day 8: July 29, 2020 

**Today's Progress**: Created view for user-registration using Django's inbuilt user model

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/c671517f300cbe10ee592aa2bee191301183a513))


### Day 9: July 30, 2020 

**Today's Progress**: Finished with User-registraion functionality(Forms, Views, Templates)

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/4ea9b3681fad5f211d3edb7a7837b8c07473fab2))

