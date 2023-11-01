# CS569 Homework 03
## In a new markdown file `hw3-question1.md`:
Summarize when each Angular lifecycle hook is triggered.
  
## Coding Exercise
1. Create a new Angular application from CLI.
2. Create a component `Counter` that has one property `count=0`, and bind (display) the property to the template.
3. Add two buttons `"-"` and `"+"`, when clicked, the `counterLocalValue` should decrease/increase.
4. Display the `Counter` component as a direct child to `AppComponent`.
5. Make the necessary updates to the `Counter` component, so it receives the initial `count` value from the parent component as an `input`, and emits the `count` value as an `output` every time it changes.
  
The expected use of the `Counter` component is as follows:
```html
<Counter [count]="counterValue" (countChange)="handleChange($event)"></Counter>
```
![Counter](./counter.png)
