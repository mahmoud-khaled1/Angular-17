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

### What is a decorator in Angular?
In Angular, a decorator is a special kind of declaration that can be attached to classes, methods, properties, or parameters. Decorators add metadata to these elements, which Angular uses to understand how to process them.

They are defined using the @ symbol followed by a function. Angular uses decorators extensively to define and configure components, services, modules, directives, and more.</br>
Common Angular Decorators</br>
Here are some of the most commonly used decorators in Angular:</br>
![image](https://github.com/user-attachments/assets/86e81915-9a5e-4fed-b784-3def628276ab)
</br>

![image](https://github.com/user-attachments/assets/3ca9202e-2bca-44c9-84d1-f9b1ac2d722e)


### What is Interpolation in Angular?
Interpolation in Angular is a way to bind data from your component class to your HTML template. </br>
It allows you to display dynamic values in the view.

It uses double curly braces syntax: {{ value }}

### What is Property Binding in Angular?
Property binding in Angular is a way to bind a value from the component class to an element’s property or attribute in the DOM.

It uses square brackets ([]) around the HTML property: [property]="value"</br>
✅ Example:</br>
export class AppComponent {
  imageUrl = 'https://example.com/logo.png';
}</br>
<img [src]="imageUrl"></br>
![image](https://github.com/user-attachments/assets/25f2d8e9-b98e-4886-b168-56f644272863)
</br>
### What is Two-Way Data Binding in Angular?
Two-way data binding is a mechanism in Angular that synchronizes data between the component (TypeScript) and the template (HTML), both ways:</br>
When the user updates the input field, the value in the component is updated.</br>
When the component variable changes, the view is also updated automatically.</br>
How to Use Two-Way Data Binding ? Angular uses [(ngModel)] syntax for two-way data binding.
![image](https://github.com/user-attachments/assets/db7baf40-4a3b-47c7-9817-9e088c6a460e)
![image](https://github.com/user-attachments/assets/7f4e4cc2-36ff-4621-8654-d2da1c8e7e74)

### What are Angular Directives?</br>
In Angular, Directives are special instructions you can apply to elements in the DOM (HTML) to change their behavior or appearance.</br>
They tell Angular to do something with the element — like hide it, repeat it, or apply logic to it.</br>
#### 🔄 3 Main Types of Directives in Angular</br>
1. Component Directives</br>
Technically, Components are directives with a template.</br>
They’re the most common kind — when you create a component, you're actually creating a directive.</br>
✅ Example:</br>
![image](https://github.com/user-attachments/assets/06badaa9-e428-4e03-827c-73d017dc4b61)

2. Structural Directives</br>
These change the structure of the DOM — like adding/removing elements.</br>
✅ Common examples:</br>
*ngIf – conditionally show elements</br>
*ngFor – loop through a list</br>
*ngSwitch – switch-case logic</br>
✅ Example:
![image](https://github.com/user-attachments/assets/7c2ba1bc-24e3-4cbb-b256-223188321eb0)

3. Attribute Directives</br>
These change the appearance or behavior of an element — without adding or removing it.</br>
✅ Common examples:</br>
ngClass – dynamically add classes</br>
ngStyle – dynamically apply styles</br>
✅ Example:</br>
![image](https://github.com/user-attachments/assets/533b959a-556c-47ec-b330-5938cf18bd97)

