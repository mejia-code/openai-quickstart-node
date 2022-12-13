# Questions:

1. meaning of "Important note: When using Javascript, all API calls should be made on the server-side only, since making calls in client-side browser code will expose your API key. See here for more details."?

The meaning of "When using Javascript, all API calls should be made on the server-side only, since making calls in client-side browser code will expose your API key" is that when making API calls with Javascript, the calls should be made on the server-side instead of the client-side browser code. This is because if the API calls are made in client-side browser code, the API key can be easily exposed.

An example of how the API key can get exposed is if the client-side code is viewable by other users. For example, if the client-side code is part of a website and the website is publicly available, anyone who views the website's source code can see the API key and potentially use it for their own purposes.

Another example of how the API key can get exposed is if the client-side code is vulnerable to hacks or other security breaches. For example, if the client-side code is part of a web application and the application is not properly secured, a hacker could potentially access the API key and use it for their own purposes.

The server-side refers to the server or servers that host the website or web application, and handle the processing of requests and responses between the client-side and the API. The server-side code is typically not accessible to users and is therefore more secure.

An example of the server-side is the back-end of a website or web application, where the server-side code is responsible for handling requests from the client-side, making API calls, and sending responses back to the client-side.

Another example of the server-side is a server-side language or framework, such as Node.js or PHP, which is used to write and execute server-side code.

When using Javascript, API calls should only be made on the server-side because making calls in client-side browser code can expose the API key.
Examples of how the API key can get exposed in client-side code include:
Viewing the source code of the page where the API call is made
Using browser tools to inspect network requests
Accessing the browser's local storage where the API key may be stored
The server-side refers to the code that runs on the server, as opposed to the client-side code that runs in the user's web browser.
Examples of server-side languages include PHP, Python, and Node.js.
Making API calls on the server side allows for better security and control over the API key.

The server-side code can be protected from unauthorized access and the API key can be securely stored in a database or configuration file. This ensures that the API key is not exposed to potential security risks.
Additionally, server-side code can be used to implement authentication and authorization mechanisms to ensure that only authorized users and applications have access to the API and its data. This can help prevent unauthorized access to the API and protect against potential security threats.
Overall, using server-side code for making API calls is a best practice for ensuring the security and integrity of the API and its data.

Viewing the source code of the page where the API call is made
Using browser tools to inspect network requests
Accessing the browser's local storage where the API key may be stored
Sharing the API key with unauthorized users or applications
Storing the API key in unsecured or publicly accessible locations
Using weak or easily guessable API key names or passwords
Not implementing adequate authentication and authorization mechanisms to protect the API key
Not regularly rotating or updating the API key to prevent potential security threats
Not properly securing the server-side code or server environment where the API key is stored
Not regularly monitoring and auditing access to the API key and its usage.

---

Viewing the source code of the page where the API call is made
Using browser tools to inspect network requests
Accessing the browser's local storage where the API key may be stored
Inadequate security measures on the website or web application hosting the API call
Insecure or unencrypted transmission of the API key
Sharing the API key with unauthorized users or applications
Storing the API key in a publicly accessible location, such as a public GitHub repository
Inadequate security controls on the server hosting the API
Lack of authentication and authorization mechanisms for access to the API
Insufficient monitoring and logging of API usage and access
Vulnerabilities in the API or the server-side code
Compromised credentials of a user or application with access to the API key
Social engineering attacks targeting individuals with access to the API key.

---

Viewing the source code of the page where the API call is made
Using browser tools to inspect network requests
Accessing the browser's local storage where the API key may be stored
Inadequate security measures on the website or web application hosting the API call
Insecure or unencrypted transmission of the API key
Sharing the API key with unauthorized users or applications
Storing the API key in a publicly accessible location, such as a public GitHub repository
Inadequate security controls on the server hosting the API
Lack of authentication and authorization mechanisms for access to the API
Insufficient monitoring and logging of API usage and access
Vulnerabilities in the API or the server-side code
Compromised credentials of a user or application with access to the API key
Social engineering attacks targeting individuals with access to the API key.

---

1. Viewing the source code of the page where the API call is made
2. Using browser tools to inspect network requests
3. Accessing the browser's local storage where the API key may be stored
4. Inadequate security measures on the website or web application hosting the API call
5. Insecure or unencrypted transmission of the API key
6. Sharing the API key with unauthorized users or applications
7. Storing the API key in a publicly accessible location, such as a public GitHub repository
8. Inadequate security controls on the server hosting the API
9. Lack of authentication and authorization mechanisms for access to the API
10. Insufficient monitoring and logging of API usage and access
11. Vulnerabilities in the API or the server-side code
12. Compromised credentials of a user or application with access to the API key
13. Social engineering attacks targeting individuals with access to the API key.

---

# API key exposure

## Top 5 ways API keys can get exposed in client-side code

1. Hardcoding the API key into client-side code
2. Storing the API key in a publicly accessible file or database
3. Sharing the API key with unauthorized users or applications
4. Failing to properly encrypt the API key in storage or transmission
5. Using the same API key for multiple applications or services.

## Top 5 ways API keys can get exposed in server-side code

1. Not securing the server-side code that makes API calls
2. Not protecting the API key in server storage or configuration files
3. Not properly validating user input or handling user-supplied data
4. Using an insecure communication protocol for API calls
5. Not securing network connections or firewalls.
