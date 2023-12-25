# Indian Premier League
# React
**React** is a JavaScript library for building user interfaces.

**Declarative:** React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
**Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
Learn Once, Write Anywhere: We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using Node and power mobile apps using [React Native.](https://reactnative.dev/)

# Installation

React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:

- Use [Quick Start](https://react.dev/learn) to get a taste of React.
- [Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project) to use as little or as much React as you need.
- [Create a New React App](https://react.dev/learn/start-a-new-react-project) if you're looking for a powerful JavaScript toolchain.

# Documentation
You can find the React documentation on the website.

Check out the Getting Started page for a quick overview.

The documentation is divided into several sections:

- Quick Start
- Tutorial
- Thinking in React
- Installation
- Describing the UI
- Adding Interactivity
- Managing State
- Advanced Guides
- API Reference
- Where to Get Support
- Contributing Guide

You can improve it by sending pull requests to this repository.

# Examples
We have *several examples on the website.* Here is the first one to get you started:

```import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```

This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; we call it JSX. JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.
![Github](data:image/png;base64,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)