# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

       You do not need to pass props around the different files. This mitigates errors. You are also able to access data in components that are nested within one another.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

      The store is a state container that is immutable and holds the state tree. Actions are JS objects that are used to change state, these are housed within the reducer and are accessed by using dispatch.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

        Allows us to call the action creators that return a function that takes the stores dispatch method as an argument. Gives us access to the dispatch in our action creators, so that we can dispatch the synchronous actions after our side effects are done.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

  I really like using context API, It is confusing to keep track of all the props that I am passing down, so to remove that piece is really helpful for me. For larger apps, I do enjoy using Redux. Setting up actions and reducers may be extra work, but It's nice to have everything in one place that you can have access through when you mapstatetoprops and connect.