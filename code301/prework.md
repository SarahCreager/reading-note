# Introduction to React and Components

## Component Based Architecture

**What is a component?**

A `component` is a small piece of code that creates a piece of the user interface. Multiple components make up the application as a whole. 

**What are the characteristics of a component?**

**Reusability:** Though components can be designed for one task, they are typically created in a format that can be reused in different circumstances.

**Replaceable:** Components are designed so that they can be substituted with similar components.

**Not context specific:** Components can be used in different environments and circumstances.

**Extensible:** A new behavior can be created by extending a component from existing components.

**Encapsulated:** Data is nested within the component. You can use the functionality of the component without exposing the internal processes, variables, or state.

**Independent:** Components function independently. They are not designed to depend on other components.

**What are the advantages of using component based architecture?**

1). **Ease of deployment** 

You can more easily deploy new components to an application with little to no impact on the other components within the system.

2). **Reduced cost**

You can use third-party components help decrease the cost of development and maintenance.

3). **Ease of development**

Since components function independently, you can develop a component without impacting other pieces of the application.

4). **Reusable** 

Since the format of components can be transferable, you can use them across several different applications.

5). **Modification of technical complexity**

Because you can nest data within the components, this modifies the complexity of the application.

6). **Reliability**

As components are used more and more and prove to be reliable, this increases the overall reliability of the system as a whole.

7). **System maintenance and evolution**

Components are easy to modify without affecting the entire application.

8). **Independent**

Multiple people can develop components in parallel without causing issues in the code. This allows for more productive and efficient development. 

## What is Props and How to Use it in React

**What is props short for?**

*Props* is a keyword in React, which is short for *properties*.

**How are props used in React?**

Props are used to pass data between components. The data used in props is read-only and should not be changed by the component receiving it. 

**What is the flow of props?**

Data only flows one way in React, from the parent component to the child component.

[Back to Homepage](../README.md)