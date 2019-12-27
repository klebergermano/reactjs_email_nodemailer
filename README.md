# React Email Nodemailer

This is a basic project with React and Nodemailer configured to send emails

---

## About

The project has basicly two parts **Client** and **Server**
__Client__ folder contains the boilerplate React created with _"create-react-project"_. inside was added a folder component with the _form.js_ which has "_handles_" that store the data form in the "_state_" and send this info with the handleSubmit function that creates a post request with "_fetch_" to the location "_/form_"
__Server__ folder contains the node structure with express that uses a server.js as principal route which import routes.js wich was used to add and configured to use the function _sendNodemailer()_ to send emails.

## Dependecies

> Concurrently, Express, Nodemailer

## How to use

Install all the modules with

```bash
npm install
```

Then run de **Node Server** and the **React Client** with

```bash
npm run dev
```

\* Was necessary remove the "\_example" from the "_configNodemailer_example.js_" to conrrectly import it to sendNodemailer.js

\* Also don't forget to put your own config information in "server/nodemailer/configNodemailer.js"

Nodemaler was configured using the example configuration with some adjusts see the original example here [Nodemailer Example](https://nodemailer.com/about/)