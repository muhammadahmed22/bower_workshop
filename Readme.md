## Manage dependencies workshop

Workshop duration 10 minutes

#### Step 1

Fork this repository

#### Step 2

1- Insatll node.js in your system

[Install node](http://howtonode.org/how-to-install-nodejs)

or 

Run the installer.sh located on the root of the repo 

```bash
./install.sh
```

2- Install bower globally in your system

```bash
$> npm install -g bower
```

#### Action begins

1- Open index.html in your editor
2- Locate the files on the template and search for them using bower

example

```bash
$> bower search angular
```

3- install the dependencies locally

```bash
bower install --save-dev
```

4- Find where bower have located the dependencies and replace the current ones
5- Add bower modules to .gitignore
6- Commit and push your changes to the repository


