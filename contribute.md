## How to contribute

  

Through this you will learn about contributing to open source projects by making your first contribution.

  

**Steps to be followed**

## 1. Fork this repository
 
You can fork this repository by clicking on fork button on top right corner. Once you fork this will have a copy of this repo in your account

## 2. Clone the repository

To clone the repository go to your account open this repo and either click on clone button or run the command below to get this repository on your local machine

  

> git clone "URL you just copied"

  

e.g. git clone https://github.com/WomeninTech-jamshoro/first-contribution.git

  

## 3. Create a branch

  

You can't make changes to master branch so it is necessary to make change on your branch so for that you have to go to your project folder

  

create a new branch using below command

  

> git checkout -b <add-your-github-name>

  

e.g. git checkout -b add-WomenInTech

  

## 4. Lets make some contributions

  

On your local machine open `Data` folder in repository and change `contribution.json` file and add your details in contributors array as follow

  

> {

"Name":"Name"

"imgURL":"URL to your image"

"Description": "Small Description about you"

}

  

## 5. Add Changes and Commit Changes

  

Adding your branch changes

  

> git add Data/contributors.json

  

Committing your changes

  

> git commit -m "Add my-name to the list"

  

## 6. Push changes to GitHub

  

Pushing your the changes

  

> git push origin your-branch-name

  

Make sure name of branch is same as you created in `step 3`

  

## Submit your changes for review

  

Once you push your code to GitHub, now it's time to create your `pull request`, you will go to the repository click on `compare and pull request` and submit the pull request.