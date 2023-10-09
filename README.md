# SeniorThesis2023##

## Use Cases

#1. Use-Case [Login Page}

Actor: Users

Overview: user pulls up webpage and gets promtpeed to log in with a username and a password. 

Course of Events:
1. user pulls up webpage and gets greeted witha prompt to log in or to sign up.
2. user types in username and password.
3. system varifies username and password are correct.

  ALT: Step 3: veriy username and password
        1: display Error
        2: provide password recovery
        3: prompt to enter email.
        4: go back to step one.
  ****
#2. Use-Case [Sign-up Page] 

Actors: New Users

Overview: Users that dont have an account will be prompted to enter in a set of information to create their account it also includes a sepcial feature to be able to link an account to an existing (family) group or to create a new group.

Course of Events:
1. Uses [Login Page]
2. user gets prompted to enter a desired user name and password //think about specific password or username limitations.
3. user enters birth date and year // think about format.
4. user enters group name.
   ALT: create a new group and give it a name.
5. gets prompted to save and submit info.
   (either gets taken back to the homescreen to login in/ Gets logged in automattically after confirmation of signing up.
   
****
#3. Use-Case [HomePage Screen]

Actors: New and Old Users.

Overview: User will be taken to a main page where they will be presented with options to pick from: Profile page, Recipe Upload, Recipe Search.

Course of Events:
1. Uses Login page
2. displays selections for users unpon loading homepage
3. user selects chooses a selection.

****
#4. Profile Page

Actors: Users

Overview: User will br taken to the account interface being shown several other selections: View Uploaded, View group(Family) Recipies, Personal Information. 

Course of Events:

1. Select one of the selections or Edit Account
2. Prompt to edit Account or change group.
3. Enter in informtion.
4. prompt to save before exit.

****

UseCase: Recipe Search

Actor: User/Guest

OverVeiw: User enters page after selections and gets presented with a layout presenting a search for recupies by Region, or by Season, Food Genre, Cultural Food, then prompts options to search and then presents recipies in the file.

Course of Events
1. Uses Homepage.
2. User gets greeted with optons to customize search.
3. click sort by and get prompted options to select.
4. Pulls up (database) Recipies and displays the slections for users.

****

UseCase: Recipe Upload

Actor: Users/Members
Overview: After selecting this option from the homepage the user will be taken to an interface where they will be able to upload their own recipe which will be organized by various elements of the recipe. With the option of making the upload private or public.

Course Of Events:

  1. Uses Homepage
  2. User gets taken to recipe upload screen and gets promted to enter information
  3. User fill in family recipe.
  4. Before leaving the user gets prompted to make the recipe public or private. 
  5. promts user to save and complete.
  6. Recipe gets uploaded and can be viewed from the profile page.
****





