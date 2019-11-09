- [x] Why would you use class component over function components (removing hooks from the question)?
    For practice incase I need to refactor legacy code or if the company I work for in the future works only in class components. It also allows some methods the React Dev Team developed for the react life cycle.

- [x] Name three lifecycle methods and their purposes.
     componentDidMount(){
        fetching data, and setting to state with setState()
    }

    render(){
        renders what's inside the function to the browser
    }

    constructor(){
        sets the initial state values, and allows to pass on that to child components with super();
    }

- [x] What is the purpose of a custom hook?
    To make logic very reusable (defining stateful logic), it's like how we make components to reuse and fill with the same shaped data so we dont have to rewrite it everytime.

- [x] Why is it important to test our apps?
    Surfaces bugs faster.
    Reduces the risk of regressions.
    Allows us to trust the code.
    Makes us think about the edge cases.
    Acts as a safety net when making changes or refactoring.
    Acts as documentation for the code.
    Encourages us to write more testable (better!) code.