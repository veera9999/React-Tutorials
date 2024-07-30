![image](https://github.com/user-attachments/assets/69c92f34-15cd-478d-8ee4-6a750334eafe)

Hello Fellow Coders and Aspirants, This is a React JS Tutorials page and we will try to learn most of the react stuff that we are going to do in our everyday lives as a developer.

# What is React?

React apps are made out of components. A component is a piece of the UI (user interface) that has its own logic and appearance. A component can be as small as a button, or as large as an entire page.

React components are JavaScript functions that return markup:

```jsx
function MyButton() {
  return <button>I'm a button</button>;
}
```

Now that you’ve declared MyButton, you can nest it into another component:

```jsx
export default function MyApp() {
  return (
    <div>
      <h1>Welcome to my app</h1>
      <MyButton />
    </div>
  );
}
```

Notice that <MyButton /> starts with a capital letter. That’s how you know it’s a React component. React component names must always start with a capital letter, while HTML tags must be lowercase.
