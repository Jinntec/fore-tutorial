# Setting up

## Prerequisites

Fore itself does not need any specific toolchain.

However, for developing and testing Fore pages you'll need a webserver
to serve the pages. This repository comes with a webserver based on NodeJS and therefore
requires an NodeJS installation on your computer.

[Download and installation instructions for Node.js](https://nodejs.org/en/)

You will also need a version of [git](https://git-scm.com) installed.

Editing can be done with any code editor of your choosing.
[VSCode](https://code.visualstudio.com/) is one option available on all operating systems, but you can also use vim, for example.

In order to run the commands below, you will also need a terminal emulator .

**Mac:** you can use the built-in Terminal or any other replacement (iTerm2, kitty, ...)

**Windows:** [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701) or PuTTY

**Linux:** any Linux Terminal


## Setting up

- Open a terminal window
- Clone this repository with `git clone https://github.com/Jinntec/fore-tutorial.git`
- Change to the working directory `cd fore-tutorial`
- Run `npm install` to install WebDevServer dependencies

## Starting/Stopping WebDevServer

`npm start` will start the WebDevServer and watch for changed files.
It should also open the [index page](pages/index.html) in your default browser.

In the console you should see something similar to this:

```
Web Dev Server started...

  Root dir: /Users/joern/dev/fore-tutorial1
  Local:    http://localhost:8000/src/pages/
  Network:  http://192.168.178.168:8000/src/pages/
```

If your default browser does not open for some reason navigate to the `Local` address. 

Pressing `Ctrl+C` (or `Cmd+C` on mac) in your terminal window will stop the server.

## Editing Fore pages

While the development server is running it will watch all files
and reload them whenever the change on disk. You will see that
the browser will alos automatically reload the page that you are
editing.

You should add your pages to the 'src/pages' directory optionally creating directories.

## Template page

To quickly create a new page you can just copy the file 'template.html', save it 
under a new name and start edtiting. 

> The necessary CSS and JavaScript imports will work only directly in 'pages' directory
> and need to be adjusted if you are storing your page in a sub-directory.



