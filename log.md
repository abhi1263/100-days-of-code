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


### Day 10: July 31, 2020 

**Today's Progress**: Added user login/authentication functionality

**Description:** 
Registered user can log in and view the index page. Only login functionality has been added. Tasks doesn't have relationship with user

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/371630940de98e81686874fe5c2bcfcb71e89f46))

### Day 11: August 1, 2020 

**Today's Progress**: Fixed the issue: Login/Signup page was visible to authenticated user

**Description:** 
Already logged in user could still visit the signup/login page. Issue was fixed by checking if user is authenticated and redirecting them, if True

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/ea18605bdfadcd5678c69ca6f32c856318ff9c9e))

### Day 12: August 2, 2020 

**Today's Progress**: One-to-many relationship between user and tasks model added

**Description:** 
Previously, tasks created didn't have any author. Now each task has an author(user) associated. One-to-many relationship between User model and Task model

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/7a9ef8b318c60139bcdeb513bba5d9492a620fd6))

### Day 13: August 3, 2020 

**Today's Progress**: Working on registration form validations

**Description:** 
Display form validation errors to user during sign up

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](https://github.com/abhi1263/learningDjango/commit/cc585b802122570e2aac5f27e0035ad1d2176855))

### Day 14: August 4, 2020 

**Today's Progress**: Completed form validation error display, fixed issue, initialised unit-test configurations to project

**Description:** 
Completed with the form validation error display and fixed issue:Any user can edit any task. Also initialised unit-test configurations to project
This small project almost reaches finish line. Over the days, will add test-suite and then integrate with master branch

**Link to work:** [SimpleTodo](https://github.com/abhi1263/learningDjango)
([commitId](b620f40bc5bc234545dcfdb3106cb3dbbf789342, 60c372bc8518aec5659b8bbcad9e330d8e740ddf, c7149bbf3b115b64a48f17c37d724c9eb4f3a955))

### Day 15: August 5, 2020 

**Today's Progress**: Started contributing on Uday Khalsa's repo on Bitbucket

**Description:** 
Since, the project is hosted on private repository, created a mock repo to import all commit log(Containing mock code and mock commit).
Working on Django.

**Things learned:**
1. How to pull, merge, push and create pull request on git
2. How to write unit test cases, test suites in Django

**Link to work:** [Mock Repo](https://github.com/abhi1263/mock-commit-from_bitbucket)

