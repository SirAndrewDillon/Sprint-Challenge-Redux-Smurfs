1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?

1A. .map .filter .concat We use map to create a new object!

2.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

2A. The store is the single source of truth because this is where te state lives, which is a javascript object. Actions are also objets that have a type and payload. Data is sent through the store as an action and Reducers assist the app in understanding how to react to the action.

3.  What is the difference between Application state and Component state? When would be a good time to use one over the other?

3A. Application state holds the data of the appplication and component state handles data that affects the UI. Application state has global information that many components can be concerned with while component state is something that only the immediate component is concerned with. A good time to use component state is a menu bar with an "open" or "closed" state.

4.  What is middleware?

4A. Redux extensions that create asynchronous behavior.

5.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

5A. Thunk lets action creators return a function instead of an action to be able to make async calls.

6.  Which `react-redux` method links up our `components` with our `redux store`?

6A. connect()
