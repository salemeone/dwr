DWR is a Java open source library which allows you to write Ajax web sites. It allows code in a browser to use Java functions running on a web server just as if it was in the browser.

DWR consists of two main parts:
**A Java Servlet running on the server that processes requests and sends responses back to the browser.** JavaScript running in the browser that sends requests and can dynamically update the webpage.

DWR works by dynamically generating Javascript based on Java classes. The code does some Ajax magic to make it feel like the execution is happening on the browser, but in reality the server is executing the code and DWR is marshalling the data back and forwards.