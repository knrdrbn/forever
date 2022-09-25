# endless
Jewelry forever.

A simple, elegant, multi-realm item that exists both in the physical world and the digital world. Currently on Mumbai testnet, release soon once designs are finalized.

Get in touch if you have any feedback or want to work with us! hugo [at] prophet.money / konrad [at] prophet.money


<br>
<br>

## Instructions
(Assuming linux terminal. If on windows consider using [WSL](https://docs.microsoft.com/en-us/windows/wsl/install))

1. create local python installation, activate it, and install libraries

```
        python -m venv venv
        source venv/bin/activate
        pip install -r requirements.txt
```

2. go to app/src/ and install npm packages

```
        cd app/src
        npm install
```

<br>

That's it! Now you can run the server, or push to github (autodeploys to render).

<br>

### Useful commands:

```
cd src
npm run build-css
```
⬆️ This will run a script that re-builds tailwind everytime you make a change to the html or css.

```
cd src
npm run local
```
⬆️ This builds the css once and will run the server locally.

```
python app.py
```
⬆️ Same thing as before, just without building the css first.

```
cd src
npm run yeet-it
```
⬆️ This says fuck it, builds the css, adds all files to a git commit, and pushes to github.