# rajachakraborti.github.io

Source Code-
https://github.com/rajachakraborti/my-products-app

There is no email and password associated. I have just created the page as the JWT needs to be passed to API.
Alternatively, we can expose some of the routes without authenctication.

Improvements-
The test cases and e2e cases could be developed. I have skipped creation of specs just to save time.

The error messages are all, logged to console now going forwaard we can create a toast component, module and service. 
To display error or notifications to user.

We can as well create a modal to warn user about loss of data, if form is dirty and user clicks on cancel.

The project is built with prod flag true, so it is minified. We can still go with server side rendering to increase performance.

I have added 2 secs delay at certain api requests just to see if element jumps or not after the page is rendered.
A more better approach would have been to show a progress bar till the resolver resolves api data.

Validations could be imporved sufficiently. Added some basic validations, and one genric text on page for create/edit.
Individual element can still be focussed.

favico is default angular.

There is a redundant api call which is happening, on click of edit. The data could have been passed to edit component
by a service. But, I wanted to implement the forkJoin to call multiple api at once and show the next route only when 
both are resolved.

Some components can be moved to shared from core.
