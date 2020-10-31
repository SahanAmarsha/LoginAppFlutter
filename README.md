Want to add a simple login functionality into your application :question: You are in the right place. :relieved:

# LoginAppFlutter
A simple login app that I have created for one of my tutorials. I have used `Firebase Authentication` as the authentication provider for this app.

###  :rocket:  My Youtube Tutorial
- [Simple Login/Signup App Using Flutter & Firebase (Part 1)](https://youtu.be/JfskObsnPk4 "Simple Login/Signup App Using Flutter & Firebase (Part 1)")
- [Simple Login/Signup App Using Flutter & Firebase (Part 2)](https://youtu.be/xnENO8wqDU0 "Simple Login/Signup App Using Flutter & Firebase (Part 2)")

###  :round_pushpin: Tips
1. You may want to create a new firebase project.

2. Enter the `WEB KEY` assigned to your project in the `authentication.dart` file.

*Example :-*
<pre>
  Future<void> signUp(String email, String password) async
  {
    const url = 'https://identitytoolkit.googleapis.com/v1/accounts:signUp?key=[YourKEY]';

    try{
      final response = await http.post(url, body: json.encode(
</pre>

3. You ***need to install flutter*** to run this application. Just recheck your flutter installation using `flutter doctor` command in your terminal, and make sure everything is okay.

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
