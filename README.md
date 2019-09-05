# bash-web-scripts

## I'm a big fan of automation! Aren't you?

After working for a while in web development, I realized that we end up doing the same things over and over. Creating databases, installing Wordpress, moving the App.js to it's own folder in a React application... the list goes on and on. And while there are a lot of (official) generators that do the job (like for example **create-react-app**), sometimes you need something more specific (like for example creating an electron app, that has already react build into it).

So I spent quite a while browsing the web for tutorials and creating my apps. And after a while I realized, that I keep coming back to these tutorials. Because let's face it, you're not going to remember all of that! So I started putting a lot of the tutorials into scripts, that run automatically and now I would like to share them with you script by script.

I try to mention the tutorial the script is based on in every file, so if you want to have a look at it itself (or improve the script, because I messed up), go ahead. I hope the scripts are as helpfull to you as they are to me.

### React

#### create-react-electron-app

A script to create an electron app with react built-in.

| Options  | Description                                                                         |
|----------|-------------------------------------------------------------------------------------|
| [FOLDER] | Provide last after all arguments. (like ./create-react-electron-app -n -y [FOLDER]) |
| -y       | Accept everything by default                                                        |
| -n       | Use npm instead of yarn (also in the config files)                                  |
| -h       | Show this help                                                                      |
