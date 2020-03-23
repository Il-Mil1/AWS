<h1>How to use AWS in an Android application</h1>

<h2>First of all create an AWS account</h2>
Here: https://aws.amazon.com 
<h2>Setting up the server</h2>
Source: <a href="https://aws-amplify.github.io/docs/cli-toolchain/quickstart?sdk=js">Installation and configuration of the server</a><br>
Install Node.js and NPM if you don't have them. 
Open the terminal and use this command: 
<li> npm install -g @aws-amplify/cli
<li> amplify configure 
<li> It will open a web page where is require the login.
<li> Press enter after you have signed in
<li> Select the region of the server
<li> Select the user name (if you press enter it will take the one in brackets)
<li> It will open a new web page with the user, next: permissions, next: tags, create a tag, create user.
<li> Go back to the terminal (do not close the web page) and press enter
<li> Give the access key id that you have in the web page, press enter
<li> Same thing with the secret access key
<li> Decide if you want to update or create the AWS Profile in your local machine (press enter for "default" has the name)
<h2> Initialization of Amplify </h2>
<li> amplify init
<li> Enter a name for the project (enter and it will take the previous one
<li> Enter a name for the environment 
<ul> Choose your default editor: (Select one)
<li> Visual Studio Code
<li> Atom editor
<li> Sublime Text
<li> Intellij IDEA
<li> Vim (Mac OS only)
<li> Emacs (Mac OS only
<li> None
</ul>
<ul> Choose the type of app that you're building (Select one)
<li> Android
<li> IOS
<li> Javascript
</ul>
<li> Where is your Res directory? (The defual one is app/src/main/res)
<li> Do you want to use an AWS profile? (The one from early).
<h2> Add the API for authentication</h2>
<li> amplify add auth
<li> Do you want to use the default authentication and security configuration? I selected the default one
<ul> Select how user will be able to sign in
<li> Username
<li> Email
<li> Phone number
<li> Email and Phone Number
</ul> 
<li> Amplify push for pushing the changes and the creation of the server and reply Y
<h3>Look at the android application from now on</h3>

<h3>If you want to see the console of the user pool type in the terminal amplify auth console</h3>
