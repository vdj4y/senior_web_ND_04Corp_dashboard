# Project04 - Restaurant Finder

### Info:
1. the project is divided into 3 main folder: /client, /database, /server
2. Important file, in database are those with the word "_Final", (the rest are raw unformatted data):
    ```
        3letterCountryCode.txt
        customer_Final.csv
        Employee_Final.csv
        open_issue_Final.json
        closed_issues_Final.json
    ```


### How TO RUN:
1. `git clone`
2. To run client: 
   * `cd client/build`
   * `python -m SimpleHTTPServer *port*`
3. To run server:
   * `cd server`
   * `npm install`
   * `node server.js`



### Notes for client folder :
1. `cd client`
2. `npm install`
3. `npm start` to run development mode
4. `npm run build` to compile to build folder
5. directory: 
   * /client
     * /build    &nbsp;&nbsp; &nbsp;&nbsp;# build directory for production only, 
     * /public   &nbsp;&nbsp; # main html and static assets
     * package.json
     * /node_modules
     * /src
       * /components_pages  &nbsp;&nbsp; # each pages: home.html, showStations.html
       * /components_utils  &nbsp;&nbsp; # components that are common among pages
     * /helper   &nbsp;&nbsp; # helper functions
       * favicon.ico
       * index.css
       * index.js &nbsp;&nbsp;  # app main entry
       * logo.svc

### Notes for server folder:
1. server will only serve json file to client
2. to run:
   ```
       1. cd server
       2. npm install
       3. node server.js
   ```
3. `node data_wrangling.js` to re-produce the raw data to useable data, inside database folder
