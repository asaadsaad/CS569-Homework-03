# CS569 Homework 03
## In a new markdown file `hw3-question1.md`:
* What is the first lifecycle hook that reads an `Input` property value?
* What causes the `ngOnChanges` lifecycle hook to trigger?
* What decorator is used to access a template variable?
* What is the first lifecycle hook that reads a template variable value?
  
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
