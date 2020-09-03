This assignment consists of two levels that are given below, please go through it.

Level 1

Note : Emphasis is only on the functionality , assignment will not be judged for UI or additional css , a basic input form and a skeleton table is sufficient. 

Create a CRUD application using the apis from json placeholder where you can manage employees in your company . 

Using the Application, a user should be able to :
View list of employees
Create an employee
Delete an employee

Hint : Use the users endpoint and consider them as employees.
Endpoint : https://jsonplaceholder.typicode.com/users

Use the Observable Store approach to cache the results
(Use a BehaviorSubject to store the results and expose it as an observable)

Optional : Try to implement the container/presenter or smart/dumb components technique.

Use all the optimizations available such as trackBy, async pipe, etc

Use rxjs operators for api manipulations , unsubscription and error handling , etc


Level 2

Expand the CRUD application using the apis from json placeholder
Using the Application, a user should now be able to :

Edit an employee details


Try to implement the container/presenter or smart/dumb components technique.

Use all the optimizations available such as OnPush ChangeDetection strategy, async pipe, etc

Use Material components , setup an app theme

Create an app level overlay service using the cdk and use that to show a dialog before deleting an employee asking for confirmation.

