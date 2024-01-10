## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag? The action attribute holds the address of the server we wish to communicate with.
2. What is the purpose of the _method_ attribute in the _form_ tag? The method attribute declares what type of request we are sending to the server.
3. What is the purpose of the _name_ attribute in the _input_ tag? The name attribute is an identifier for the website user. It indicates what the form is for eg. Username or Password
4. What is the purpose of the _type_ attrbute in the _input_ tag? The type Attribute indicates what the input is. If the attribute is "password" for example, the entered text will be hidden from view. If the type attribute is "submit" then the input will be a button which triggers the form action.
5. What is the purpose of the _label_ tag? The label tag gives a label to a form input. It requires the specification of the inuts "name" attribute.
6. What is the purpose of the _required_ attribute? The required Attribute indicates that the form must be completed to submit.

