# [Vue js](https://vuejs.org/v2/guide/)
For two future student project I will need to learn vue js. So at the same time, I will take the time to document everthing I learned, as good as possible.

# Basic Directives [Go to Vue directives](https://vuejs.org/v2/guide/)
`v-text` = The same like bindig with double curly brackets `<h1>{{message}}</h1>` or `<h1 v-text='message'></h1>`

`v-html` = With v-html it is possbible to add some HTML-Tag with the message it self.

`v-show`= It´s pretty much the same like `v-if`, the only difference is that the code is loaded to the HTML but not displayed

`v-if` = If `false`the code is not displayed in the HTML-Code at all.

`v-else` = When `v-if='false'` then v-else.

`v-pre` = Will not render the message `<h1 v-pre>{{message}}</h1>` output in HTML will be `{{message}}`

`v-cloak` = This directive will remain on the element until the associated Vue instance finishes compilation. Combined with CSS rules such as `[v-cloak] { display: none }`, this directive can be used to hide un-compiled mustache bindings until the Vue instance is ready.


![bildschirmfoto 2017-04-07 um 23 03 14](https://cloud.githubusercontent.com/assets/22995847/24819834/92f33f0e-1be6-11e7-938b-46805b680d0b.png)
Picture of all directive I used so far.

