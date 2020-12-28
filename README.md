# pizzaApp

----------------------------------------------------How to run.
# have used django framework for this project.

1. get a pull request of the project from the github.
2. download python and django framework according to your OS. 
3. open the directory where you placed the project.
4. run the command- python manage.py runserver
6. update your DB related information in settings.py file.
5. make the dbMigration - python manage.py makemigrations (make sure you have postgresql up and running)
6. do the migration - python manage.py migrate.
7. you can open the link in the web browser to start using the project.



----------------------------------------------------How to use.

Home page is divided into three section.
1. pizza Information --> here you will be selecting the information and input all the required fields which is needed for the storage.
		-- toppings input box has given limitation to 64 characters only.

2. Data section --> this section contains all the data related to pizza stored in database. 
	-- from here you can edit the data and also you can delete it.
	-- two buttons are available for each data which handle edit and delete functionality.
	-- incase of edit, when this button is clicked the pizza information section fields will automatically gets filled with those data from
	- - the table, user can change whatever information it needed and then click on update.

3. Filter Section --> in this section user can apply filters related to pizza type and size, according to the applied filter it will update the 
	-- data section (table which shows the list of pizza's data)


# technologies used.
--> Frontend- for UI and events hadling HTML and JAVASCRIPT is being used. 
	--library for UI is SEMANTIC UI
	-- Event handling - JQUERY

--> Backend -> core python

--> database -> postgresql
