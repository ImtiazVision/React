We use a React utility function named `useState` to manage state. The `useState` function is referred to as a **hook**. There are multiple React hooks, each of which is related to state management but also to other aspects of React. 

```
const App = () => {
  const stories = [ ... ];

  const [searchTerm, setSearchTerm] = React.useState('');

  ...
};
```
