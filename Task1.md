Git Task for Practice: Managing a Team Shopping List
Task Description:
You and your team are working on a collaborative shopping list project. Each person is responsible for adding their assigned items to the list without disrupting others’ work. You'll use Git to manage the process.

Steps to Complete the Task
Initialize a Repository

Create a new folder named TeamShoppingList and navigate into it.
Run git init to initialize a Git repository.
bash
Copy code
mkdir TeamShoppingList
cd TeamShoppingList
git init
Set Up the Initial List

Create a file named shopping_list.txt and add the following content:

text
Copy code
Shopping List:
- Fruits
- Vegetables
Stage and commit the changes.

bash
Copy code
git add shopping_list.txt
git commit -m "Initial shopping list with Fruits and Vegetables"
Create a Branch for Adding Dairy Items

Create a branch called feature/add-dairy-items and switch to it.

bash
Copy code
git checkout -b feature/add-dairy-items
Add the following items to shopping_list.txt:

text
Copy code
- Milk
- Cheese
Stage and commit the changes.

bash
Copy code
git add shopping_list.txt
git commit -m "Added dairy items to the shopping list"
Switch to the Main Branch and Add Meat Items

Switch back to the main branch.

bash
Copy code
git checkout main
Add the following items to shopping_list.txt:

text
Copy code
- Chicken
- Fish
Stage and commit the changes.

bash
Copy code
git add shopping_list.txt
git commit -m "Added meat items to the shopping list"
Merge the Dairy Branch into Main

Attempt to merge the feature/add-dairy-items branch into main.

bash
Copy code
git merge feature/add-dairy-items
If there are merge conflicts, resolve them by keeping both sets of changes.
Example resolution in shopping_list.txt:

text
Copy code
Shopping List:
- Fruits
- Vegetables
- Milk
- Cheese
- Chicken
- Fish
Commit the merge.

bash
Copy code
git add shopping_list.txt
git commit -m "Resolved conflicts and merged dairy branch"
Tag the Completed List

Create a tag named v1.0 to mark the milestone of completing the shopping list.
bash
Copy code
git tag v1.0
Push Changes to Remote

Push the main branch and tags to a remote repository (e.g., GitHub).
bash
Copy code
git remote add origin <your-repository-URL>
git push origin main --tags
Objective
Understand branch creation and management.
Resolve merge conflicts.
Use tags to mark milestones.
Practice staging, committing, and pushing changes.
