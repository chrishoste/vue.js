# [Vue js](https://vuejs.org/v2/guide/)
For two future student project I will need to learn vue js. So at the same time, I will take the time to document everthing I learned, as good as possible.

# Basic Directives [Go to Vue directives](https://vuejs.org/v2/api/#Directives)
`v-text` = The same like bindig with double curly brackets `<h1>{{message}}</h1>` or `<h1 v-text='message'></h1>`

`v-html` = With v-html it is possbible to add some HTML-Tag with the message it self.

`v-show`= It´s pretty much the same like `v-if`, the only difference is that the code is loaded to the HTML but not displayed

`v-if` = If `false`the code is not displayed in the HTML-Code at all.

`v-else` = When `v-if='false'` then v-else.

`v-pre` = Will not render the message `<h1 v-pre>{{message}}</h1>` output in HTML will be `{{message}}`

`v-cloak` = This directive will remain on the element until the associated Vue instance finishes compilation. Combined with CSS rules such as `[v-cloak] { display: none }`, this directive can be used to hide un-compiled mustache bindings until the Vue instance is ready.


<img width="400" alt="bildschirmfoto 2017-04-09 um 21 49 05" src="https://cloud.githubusercontent.com/assets/22995847/24840506/8044e928-1d6e-11e7-9d60-1a86832ca05b.png">


# v-bind
`v-bind` = This directive is used to bind attributes to the HTML-Tag. Like `v-bind:url=""` `v-bind:alt=""` `v-bind:title=""` an so on.

# v-for
`v-for` = This directive is used to loop through an array or a JSON-Object. It is pretty much the same like a foreach-loop. Here is an example syntax: `<li v-for="todo in todos">{{todo.text}}</li>` and in this case the JSON-Onject that is retunred from the data object ist called todos and has a field called text. For every todo in todos it will append a list item with the name of the todo.


# 2-way binding
`v-model` = `<h1>{{ message }}</h1>` `<input type="text" v-model="message"/>` What ever you type in this input it will be bind to the `<h1>`

<img width="350" alt="bildschirmfoto 2017-04-09 um 21 43 10" src="https://cloud.githubusercontent.com/assets/22995847/24840446/97e17098-1d6d-11e7-98c0-e922c8ce37cd.png">

