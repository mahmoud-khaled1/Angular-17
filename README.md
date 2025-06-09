# Angular-17

### What is Angular? 
Angular is a development platform, built on TypeScript </br>
As a platform, Angular includes:

- A component-based framework for building scalable web applications
- A collection of well-integrated libraries that cover a wide variety of features, including routing, forms management, client-server communication, and more
- A suite of developer tools to help you develop, build, test, and update your code
 ### Understanding Component-Based Architecture in Angular :- 
Component-Based Architecture in Angular is a software design approach where an application is built as a collection of independent, reusable, and encapsulated components.

Each component in Angular:

- Represents a specific part of the UI (like a button, form, or dashboard).

- Contains its own HTML (template), CSS (styles), and TypeScript (logic).

- Can communicate with other components using inputs and outputs.</br>
Component Hierarchy</br>
Angular apps typically follow a tree-like structure:</br>
AppComponent</br>
├── NavbarComponent</br>
├── SidebarComponent</br>
├── DashboardComponent</br>
│   ├── ChartComponent</br>
│   └── TableComponent</br>
└── FooterComponent</br>
Each child component focuses on a specific responsibility, and data can be passed between parent and child components using @Input() and @Output() decorators.</br>
Summary
Component-Based Architecture in Angular helps you build clean, scalable, and maintainable web applications by breaking the UI into independent and reusable components. It's central to Angular’s design philosophy.

