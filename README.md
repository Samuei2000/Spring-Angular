# How to prepare the database

In the Mysql database, run the script `refresh-database-with-100-products.sql`

# How to prepare the backend/Spring

  1. Run `./mvnw clean install`
  2. Run `./mvnw spring-boot:run`, which will start the backend. After the application is started, click http://localhost:8080/api/ on the browser to see all APIs

# How to prepare the front end

What needs to be installed:
- nvm [Node Version Manager](https://github.com/nvm-sh/nvm).


Check nvm version: `nvm --version`
- npm and node: After installing nvm, run `nvm install node`

Check npm and node versions: `node --version` and `npm --version`
- tsc: Run `npm install -D typescript`
Check tsc version: `tsc --version`
- Angular: Run `npm install -g @angular/cli`
Check Angular CLI version: `ng version`

## Installation Notes

  1. Run `source ~/.bashrc` to add nvm to the system path
  2. If it is displayed

> The current version of Node (20.4.0) is not supported by Angular.

Then run `nvm list` to check the currently used nvm version, run `nvm use 16.16.0` to select the nvm version, run `nvm install v16.10.0` to install the nvm version, run `npm uninstall -g @angular/cli` Uninstall Angular
## Run the front end
After running `node -v`, `npm -v`, `npm install -g @angular/cli` without any problem, in the front-end directory, run `npm install`, `ng build` and `ng serve`
