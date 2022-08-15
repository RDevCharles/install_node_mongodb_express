# install_node_mongodb_express
Installation instructions for node, mongodb, and express.

# Node for Mac
Open your terminal.

```sh
brew install node@16
brew link --force --overwrite node@16
```

- Close your terminal and open a new one.
- Check to see if if Node was installed correctly.

```sh
node -v
npm -v
```
Our output for those commands should show us what versions of node and npm we have. If not lets assess.



# Node for PC

Download node directly from this link and follow the install instructions.
https://nodejs.org/en/download/

======================================
## Mongodb for Mac

```sh
brew tap mongodb/brew
brew update
brew install mongodb-community@6.0
```

## Mongodb for PC

##### Download the MongoDB Community .msi installer from the following link:
https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/#download-the-installer

- In the Version dropdown, select the version of MongoDB to download.
- In the Platform dropdown, select Windows.
- In the Package dropdown, select msi.
- Click Download.

##### Run the MongoDB installer.
###### From the Windows Explorer/File Explorer:

- Go to the directory where you downloaded the MongoDB installer (.msi file). By default, this is your Downloads directory.
- Double-click the .msi file.
- Follow the MongoDB Community Edition installation wizard
####

Here's a link with more info 
https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/q

======================================
## Express
We won't get into the inner workings of express just yet. But we will be installing it for every project we work on that requires a custom backend server.

```sh
mkdir myapp
cd myapp
npm init
npm install express
ls
```
======================================

## License

MIT
