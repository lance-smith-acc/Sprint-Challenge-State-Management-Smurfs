1. What problem does the context API help solve?
    It enables prop drilling and allows you to pass components down contextually.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Reducers can manage our state and make it immutable. Actions tell the reducer how to update the state and can include a payload. Store is where all the state changes and storage occurs.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
    Application state is syncing state across the entire application, where component state is strictly within the component. If we need data created by a component, but to not affect our state tree, we would put it in component state.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
    It modifies the redux flow and allows our action creators to invoke a function before passing to the reducer.

1. What is your favorite state management system you've learned and this sprint? Please explain why!
    useContext seems infinitely easier than redux.