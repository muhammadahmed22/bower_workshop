## Manage dependencies workshop

Workshop duration 10 minutes

#### Step 1

Fork this repository then `cd` to it

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

1- Add a bower.json file

```bash
# Fill the file with your name and follow the options
$> bower init
```

2- Open index.html in your editor Locate the dependencies files on the template then search for them using bower


```bash
# Example
$> bower search angular
```

3- install the dependencies locally

```bash
bower install --save-dev
```

4- Find where bower have located the dependencies and replace the current ones
5- Add bower modules to .gitignore

Add a .gitignore file on the root of the repo
```bash
touch .gitignore && vim .gitignore
```

then add this line `.bower_modules/`


6- Commit and push your changes to your forked repository

```bash
git add . && git commit -m 'Done' && git push

```