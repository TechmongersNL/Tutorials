# Mock Assessment: Task Management App 📝

For this assessment, we want you to build a task management app. You are required the add at least 3 of the features and style it as you wish.

## Required Stack

- React

## Tips

- Redux is not required, up to you
- No need for a backend/saving the data, keep it frontend only
- Here is some example data:

```js
//example code
//not working code

  const maxTasks = 20
  const showCompletedTasks = false
  const tasks = [
    { id: 1, task: "Pick up new glasses", completed: true }
    { id: 2, task: "Buy airco", completed: false }
    { id: 3, task: "Take packages to return", completed: false }
    { id: 4, task: "Order dog food", completed: true }
  ]
```

## Feature 1 - Add new task

- The added task should be an object in the same format as the existing ones
- If the `maxTasks` is reached, you shouldn't be able to add more tasks

## Feature 2 - Mark task as completed

- Marking a task as completed removes it from the list if `showCompletedTasks: false`

## Feature 3 - Delete task

- Add a button to delete a task from the list

## Feature 4 - Toggle show completed tasks

- If `showCompletedTasks: false`, we should only see pending tasks
- If `showCompletedTasks: true`, we should all tasks

## Feature 5 - Modify the maximum amount of tasks

- If `maxTasks: 20`, you should be able to have more tasks than 20
- Add the possibility to change the amount of tasks, this number can vary from 1 to 99
