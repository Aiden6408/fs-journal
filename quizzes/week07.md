# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```

In a data binding process, whenever data is changed, it is reflected automatically by the elements bound to the data. 
Two-way data binding refers to sharing data between a component class and its template. If you change data in one place, it will automatically reflate at the other end. For example, if you change the value of the input box, then it will also update the value of the attached property in a component class.
 One way dat binding takes data in and pushes it one direction. 


```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Spa stands for Single page application. This is how vue structures its components and pages. CSS,java script and html are all located in one file for that particular item. 
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Advantes of a SPA application include ,faster speeds as logic and loading is handled differently, better UX experience,often times more mobile friendly,decreased server calls etc.  
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The onmounted method in vue Loads whats inside the function when the page is mounted or in other words loaded. 
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model attribute is for two way data binding within vue. This is where data can be passed two directions through the application. This usually occurs in the form of a template or component injection. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
 v:on can be described as an event listener. It essentially says run or do that thing when ever it notices a change in that data or method. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
 v-if's and v-elses are a good way to conditionally render elements to the page. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute tells Vue how your data relates to the HTML elements it's rendering to the screen. When your data changes, Vue uses these keys to know which HTML elements to remove or update, and if it needs to create any new ones.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
 The slot element represents a placeholder inside a component created using the shadow DOM specification. This element becomes powerful in the development of compound widgets, favoring the reuse of code.
```