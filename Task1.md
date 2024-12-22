# Git Task for Practice: Managing a Team Shopping List

## Task Description:
You and your team are working on a collaborative shopping list project. Each team member adds their assigned items to the list without disrupting others’ work. You'll use Git to manage the process.

---

## Steps to Complete the Task

### 1. Clone the Repository
- Clone an existing repository containing the initial setup for the project.

### 2. Set Up the Initial List
- Create a file named `shopping_list.txt` and add the initial structure with the categories "Fruits" and "Vegetables."
- Commit these changes to document the starting point.

### 3. Create a Branch for Adding Dairy Items
- Create a new branch named `feature/add-dairy-items` to work on adding dairy products without affecting the main branch.
- Add items like "Milk" and "Cheese" to the list.
- Commit the changes on this branch.

### 4. Switch to Main and Add Meat Items
- Return to the `main` branch to add another set of changes.
- Add items like "Chicken" and "Fish" under a "Meat" section.
- Commit the changes to the main branch.

### 5. Merge the Dairy Branch into Main
- Merge the `feature/add-dairy-items` branch into the `main` branch.
- If there are conflicts (e.g., changes to the same section of the file), resolve them by retaining both sets of changes.
- Finalize the merged file to include all updates.

### 6. Tag the Completed Shopping List
- Create a tag (`v1.0`) to mark the milestone of completing the initial version of the collaborative shopping list.

### 7. Push Changes to the Remote Repository
- Push the updated `main` branch and the new tag to the remote repository so the entire team can access the latest version.

---

## Objective
- Learn how to work with cloned repositories.
- Understand branch creation, merging, and conflict resolution.
- Practice tagging milestones and collaborating on a shared codebase.
