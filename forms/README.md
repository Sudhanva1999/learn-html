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
1. What is the purpose of the _action_ attribute in the _form_ tag?
  - The action attribute states the URL on which the get or post 
    request is to be sent on submitting the form.

2. What is the purpose of the _method_ attribute in the _form_ tag?
 - The method attribute specifies if the http request is GET (wants to fetch something from server)
   or POST (wants to send data to server)

3. What is the purpose of the _name_ attribute in the _input_ tag?
 - The name attriubtes allows us to refer to html input tags in 
   javascript or other scripts to fetch input data from them or 
   to refer to them.

4. What is the purpose of the _type_ attrbute in the _input_ tag?
 - Type specifies the type of input to be added in the form like
   radio, text, checkbox, file etc.

5. What is the purpose of the _label_ tag?
 - The label tag adds a reference for the user that lets them know 
   what the input field is expecting them to enter.

6. What is the purpose of the _required_ attribute?
 - The required attribute states that the input is mandatory and that 
   the form cannot be submitted before entering that input.

