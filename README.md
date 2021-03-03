#  Notes on How this repo is created ...

### step 1: Base web site works fine
 - Step 1:
 -  first this REPO is crated with  Next js  examples/with-typescirpt 
 -  after $npm install -> $npm run dev ;  localhost:3000  on browser works fines shows pages
 
 ### step 2: We added files to  /pages folder 
 - /src/ added to /pages  form /page/src of the snadbox  https://codesandbox.io/s/rough-cherry-qntz3?file=/package.json:229-336
 -  below chaneges aded to package.json  
 ```
  "react-icons": "3.9.0",
   "uuid": "7.0.3"
 ``
 - getting problems after adding above src/* files 
 - PROBLEM :  it is giving 'fs' module not found error : 
 ```
 ./node_modules/babel-plugin-styled-components/lib/visitors/displayNameAndId.js:10:0
 Module not found: Can't resolve 'fs'

 ```
