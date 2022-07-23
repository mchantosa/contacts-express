# contacts-express
## An introduction to Express

This project is a more complex intro to Express than [hello-world-express](https://github.com/mchantosa/hello-world-express).

**Examples:**
* **Use a form:** created `new-contact` view using form data with corresponding `get` and `post` handlers.
* **Validate user input data:** Added validation middleware to `/contact/new` handler
* **Persisted user data over validation failures**
* **Set up cookies and session persistance:** used `express-session` and `connect-loki` libraries to faciligtate this. The session secret is included in the source control (since this is a tiny application intended to run locally). IRL, the session secret should not be under source control.
* **Instroduces flash messaging:** flash messaging is introduced to persisted messages across views
