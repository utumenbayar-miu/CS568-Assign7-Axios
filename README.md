# CS568 - Assignment 5 - Lifecycle methods
1. Implement and observe lifecycle methods, ```constructor, render, componentDidMount, componentDidUpdate, componentWillUnmount```.
2. Implement methods equivalent to ```componentDidMount, componentDidUpdate, componentWillUnmount``` in a functional component using the ```useEffect``` hook. ```componentWillUnmount``` is triggered when you hide/show the component using conditionals.
3. Trigger the ```componentDidUpdate``` only one of states has been changed by overwriting  ```shouldComponentUpdate```. Practice ```PureComponent``` in a class-based component.
4. [Research] Customize ```componentDidUpdate``` then it is invoked only one of the state has been changed, not every state. Similar to ```useEffect(() => {...}, [state])```. 
5. Practice ```React.memo```.
