Problem statement
Learn to secure views by implementing user authentication with express-session, enhancing middleware for user validation, and seamlessly integrating authentication within route handling for protected web pages. This provides practical insights into creating secure user experiences in a Node.js application.

Objectives:

i) Given a view, "secure-page.ejs," accessible through the GET route ('/'), access to this view should be restricted to logged-in users only. Users who are not logged in must be prevented from accessing the secure page. Implement this functionality using express-session.
ii) Implement secure access to the "secure-page.ejs" view.
iii) Restrict access to the page for non-logged-in users.
iv) Implement the "auth" middleware to authenticate users and apply it to the GET Route ('/').
v) Modify the "loginUser" controller to support the authentication process.

Notes:
Users can log in using the POST Route ('/login'). Analyze all provided routes and their controllers to gain a clear understanding of the data flow for user authentication.
The "auth" function should check if the user is logged in and return an appropriate response.
Consider using middleware to apply the authentication logic before accessing the secure page.
If an unauthorized user tries to access the secure page, render the 'msgPage' view with the error message 'Login first to access secure page', for example: 'res.render("msgPage", { message: "login first to access secure page" });'.

Expected Output:

The "secure-page.ejs" view should only be accessible to users who have logged in. Non-logged-in users should be redirected or denied access to the page.
