# content-server

Demo content server


# Setup
  - `npm install`
  - `bower install`


# Starting the server
```
npm start
```


# Notes
  - The index.html page has code to conenct to the data-server


# Approach 1
  - Use iframes to construct the entire page from components.
  - interframe communication through a proxy in the parent.


# Approach 2
  - Angular1 has support for components using directives.
  - No need for iframe as the components can be directly included in the page.
