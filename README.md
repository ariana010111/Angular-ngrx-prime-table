angular-ngrx-table
Angular NGRX table using the Prime NG framework Get the user data from this URL https://dummyjson.com/users. Create a simple table with the following fields:

     firstName, lastName, age, gender, email, phone, eyeColor, and birthdate.
At the top of the table add a search input to search on both user firstName and lastName At the top of the table add a filter button that opens a sidebar that includes the following part as a filter:

     Gender
· for the gender filter put three check boxes "female, male, and others and I prefer not to say”. · Note that the conditions between these checkboxes are "or" and the user can filter one or more genders at the same time.

     Age
· for the age filter put a dropdown with "equal, greater, and smaller" options along with input so that the user can filter users by entering a number and choosing one of the age options.

     Eye color
· to display the eye color filter, display all the eye colors in the information obtained by the API (non-repetitive) in the checkbox, and like the gender field, the user can select and filter one or more options at the same time.

     Birth date
· Use a calendar so that the user can filter the date of birth, note that the user must be able to use a range of dates in the calendar. When the user sets the filter, store the data in the store and fetch and apply the data in the list module.


