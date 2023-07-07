# todo-react
 
![image](https://github.com/eemrekoca/vite-project/assets/53919965/b5a2d9b9-bfcd-42db-b6f1-efc9880b1352)



This project is a Todo List application built using React. The main goal of the application is to allow users to create, manage, and track their tasks or todos.

Technologies Used:
- React: The project is built using the React library, which is a popular JavaScript library for building user interfaces.
- useState Hook: The useState hook is used to manage the state of the todos. It allows the application to keep track of the current todos and update them when needed.
- useEffect Hook: The useEffect hook is used to handle side effects in the application. In this case, it is used to save the todos to the browser's localStorage whenever they change.
- localStorage: The localStorage API is used to store the todos locally in the user's browser. It allows the todos to persist even if the user refreshes the page or closes the browser.
- NewTodoForm Component: This component is responsible for rendering a form where users can input the title of a new todo. It receives the `addTodo` function as a prop to handle the submission of the form.
- TodoList Component: This component is responsible for rendering the list of todos. It receives the todos array as a prop and renders each todo item. It also receives the `toggleTodo` and `deleteTodo` functions as props to handle toggling the completion status of a todo and deleting a todo, respectively.

Overall, this project provides a simple and interactive user interface for managing a list of todos. Users can add new todos, mark them as completed or incomplete, and delete them from the list. The use of React and the useState and useEffect hooks allows for efficient state management and updates in the application.

# App
App component manages the state of todos using the useState hook and persists the todos to the localStorage using the useEffect hook. It provides functions for adding, toggling, and deleting todos. The rendered UI consists of a form for adding new todos, a header, and the list of todos.

# TodoList Component 
the TodoList component iterates over the todos array, creating a TodoItem component for each todo item. This forms the visual representation of the Todo List, and allows for operations such as editing or deleting each todo item.

#TodoItem
The TodoItem component provides the visual representation and interactions for each individual todo item. Users can modify the completion status by checking or unchecking the checkbox, and they can delete the item by clicking the "Delete" button.

# NewTodoForm Component
the NewTodoForm component provides a form for users to enter new todo items. When the form is submitted, it calls the onSubmit function provided via props with the value of the new item. The component uses the useState hook to manage the state of the newItem input field, allowing for real-time updates as the user types.

# TodoItem Component
TodoItem component represents an individual todo item in the Todo List. It renders a checkbox for toggling the completion status, displays the title, and provides a delete button for removing the todo item. The component utilizes the provided props to handle the interaction and modification of the todo item.

