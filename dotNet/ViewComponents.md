## what are view components?
View components are comparable to partial views in functionality, but they are far more powerful. View components do not use model binding; instead, they rely on the data given when the view component is called. Although this post was designed with controllers and views in mind, view components are also compatible with Razor Pages.


## what view components can do?
- Produces a section of the response rather than the entire response.

- Provides the same benefits in terms of separation of concerns and testability as a controller and view.

- Parameters and business logic are possible.

- Is usually called from a layout page.


## where do we use view components?
View components are designed to be used anywhere there is reusable rendering code that is too sophisticated for a partial view, such as:

- Dynamic menu navigation

- Tag cloud, which searches the database

- Panel for signing in

- Purchase cart

- Recently released articles

- Blog sidebar content

- A sign in panel that would be shown on every page and show either sign out or sign in links, depending on the user's sign in state.



## what are the parts of view components?

A view component is made up of two parts:

- The class, which is usually inherited from ViewComponent.

- The result, which is usually a view.
