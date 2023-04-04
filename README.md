## CS 122B Project 2 Session example

This example shows how session works, including saving data to session and retrieve data from session.

### Brief Explanation
`SessionServlet.java` is a Java servlet that keeps tracking user information. It creates a new session for each new coming user, it also recognize the previous-visited user and count for visit times.
Try use different names in the url and see the difference.

`ItemsServlet.java` is a Java servlet that keeps tracking items. It maintains a session for all the previous items that logged on to it.
Try use different items names in the url and see the difference.
