# SENDING FORM DATA
### Client/server architecture
 HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.
### The action attribute
attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form the current page.
### The method attribute
**how data is sent**<br />
 the most common being the GET method and the POST method
#### The GET method
  used by the browser to ask the server to send back a given resource.<br />
  The data is appended to the URL as a series of name/value pairs. After the URL web address has ended, we include a question mark (?) followed by the name/value pairs, each one separated by an ampersand (&).

#### The POST method
  uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.<br />  
**Advantages of POST method**
- If you need to send a password (or any other sensitive piece of data), never use the GET method or you risk displaying it in the URL bar, which would be very insecure.
- If you need to send a large amount of data, the POST method is preferred because some browsers limit the sizes of URLs. In addition, many servers limit the length of URLs they accept.