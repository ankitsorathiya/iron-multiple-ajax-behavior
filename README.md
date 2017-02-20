# iron-multiple-ajax-behavior
It is useful to send multiple XHR requests asynchronously and have one final handler to be invoked after all the requests are executed.
It is a polymer behvaior and can be easily used with the api based applicaton.

#installation
bower install iron-multiple-ajax-behavior

#usage
Let's take a situation where user has to call multiple api call and when all the api calls are executed certain action should be taken.
This is where iron-multiple-ajax-behavior can be useful.

eg. getting data from multiple sources and when all of them are recieved it should show data has been loades successfully.
please refere https://github.com/ankitsorathiya/iron-multiple-ajax-behavior/blob/master/demo/index.html
Example:
```
<custom-element-demo>
  <template>
     <link rel="import" href="iron-multiple-ajax-demo.html">
     <iron-multiple-ajax-demo></iron-multiple-ajax-demo>
  </template>
</custom-element-demo>
```