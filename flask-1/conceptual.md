### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?

Python is often used for data analysis and AI, while JavaScript is used for web development.
Python has cleaner syntax, while JavaScript has some quirks

- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.

Use the get() method with a default value.
Check if the key exists using the in operator.

- What is a unit test?

Tests individual code components in isolation.

- What is an integration test?

Tests how different components work together.

- What is the role of web application framework, like Flask?

Helps structure web apps.
Handles routing, middleware, templates, and more.

- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?

Use route parameters for core URL components.
Use query parameters for optional or filtering info.

- How do you collect data from a URL placeholder parameter using Flask?

Define the parameter in the route pattern, access it in the view function.

- How do you collect data from the query string using Flask?

Use request.args.get('param_name') to access query parameters.

- How do you collect data from the body of the request using Flask?

For POST requests, use request.json or request.form to access data.

- What is a cookie and what kinds of things are they commonly used for?

Stores data in a user's browser.
Common uses: session management, authentication, personalization, tracking, and more.

- What is the session object in Flask?

The session object in Flask allows you to store user-specific data that persists across multiple requests.
It's often used for features like user authentication and maintaining a user's login status.

- What does Flask's `jsonify()` do?
Flask's jsonify() is a function that converts Python dictionaries or objects into JSON format.
It's commonly used to send JSON responses from a Flask route to a client, making it easy to work with data in web applications.