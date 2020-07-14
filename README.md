# Client Side Auth

## 1. First, initialize the project and install dependencies


## 2. Put all the route configuration to the index.js, which centralizes all our core setup logics for our application

Whenever the <App /> component is rendered, the <Route /> component will be passed to the <App /> as the prop, called children. And the <App /> component doesn't have to have the navigation logic




## 3. Wire up Redux for Redux Form

Add reducers 

## 4. Setup Redux Form and wire up to Sign-Up form



## 5. Handling form submission


What is Redux-Thunk?

A typical action creator is always to return an object that has properties of an type and a payload. And then this action get sent to the middleware and then reducers. Reducers then produce the new state and that flow back to our components.

So what is Redux-Thunk?

Rather than returning an object, we can return a function with the dispatch function parameter. It allow us to return an different value type from our action creators.

1. By having the ability to return a function with dispatch, we gain the ability to dispatch as many actions that we want from a single action creator.

2. In addition, we can handle asynchronous request.

## 6. Wire up Redux Thunk middleware

## 7. Make Signup component a container or a connected component


## 8. Display auth errors

