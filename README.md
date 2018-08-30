# Auth Notes

### Pre-Configuration

+ install superagent as project dependency
  ```sh
  npm install --save superagent
  ```

### Relevant files/folders

+ `src/client/js/ListingsMulti.js`
  - import superagent
  - set default state for component as empty array
  - use superagent to make request to `/api/products` route
  - set state with returned data

+ `src/client/js/ShopsMulti.js`
  - import superagent
  - set default state for component as empty array
  - use superagent to make request to `/api/vendors` route
  - set state with returned data
