# Tutorial for Building React App with Webpack
### Starting with [ React For Beginners ad Codingbox ](blog.codingbox.io/react-for-beginners-part-1-setting-up-repository-babel-express-web-server-webpack-a3a90cc05d1e)
#### Notes
* to avoid absolute-path error, added 
  ```javascript
  const path = require('path');" and changed output.path to "path: path.resolve(__dirname, './public') 
  ```

* to correct empty extension error, changed 
  ```javascript 
  resolve.extensions to ['*', '.js', '.json'] 
  ```
  (adding the * to replace empty item)
  
