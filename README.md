This is the home of the to-be-developed Fulcrum protocols.

Our stated goal is to have an established set of protocols for deploying a
web application to end-user-owned hardware. To begin with there will be at least
two parts, first a specification file for app developers that specify an applications
requirements and dependencies, and second a set of endpoints that hosting providers
can implement that allow for a user to add an application to her hardware.

We're aiming to turn the funcionality provided by Heroku's [`app.json`](https://devcenter.heroku.com/articles/app-json-schema)
file and their [Heroku Button](https://blog.heroku.com/heroku-button) into
targets for app developers that avoid any specific vendor lock in and encourage
implementations that cater to a wider, non-developer audience.


## Application Specification File

See #1 for more the discusion.

This will take the form already put into use by sites like Heroku. We're currently
investigating if our implementation can function as an extension to their
established schema in order to facilitate adoption. 

## Deployment Protocol

See #2 for the discusion.

Again we're shooting for similar functionality to that presented by the [Heroku Button](https://blog.heroku.com/heroku-button),
simply standardized in a way that discourages vendor lock-in. 

