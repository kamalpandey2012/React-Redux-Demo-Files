# React-Redux-Express Demo Files

## Module 1 
1.1 Dependencies 
```
"dependencies": {
    "babel-polyfill": "6.8.0",
    "bootstrap": "3.3.6",
    "jquery": "2.2.3",
    "react": "15.0.2",
    "react-dom": "15.0.2",
    "react-redux": "4.4.5",
    "react-router": "2.4.0",
    "react-router-redux": "4.0.4",
    "redux": "3.5.2",
    "redux-thunk": "2.0.1",
    "toastr": "2.1.2"
  },
  "devDependencies": {
    "babel-cli": "6.8.0",
    "babel-core": "6.8.0",
    "babel-loader": "6.2.4",
    "babel-plugin-react-display-name": "2.0.0",
    "babel-preset-es2015": "6.6.0",
    "babel-preset-react": "6.5.0",
    "babel-preset-react-hmre": "1.1.1",
    "babel-register": "6.8.0",
    "cheerio": "0.22.0",
    "colors": "1.1.2",
    "compression": "1.6.1",
    "cross-env": "1.0.7",
    "css-loader": "0.23.1",
    "enzyme": "2.2.0",
    "eslint": "2.9.0",
    "eslint-plugin-import": "1.6.1",
    "eslint-plugin-react": "5.0.1",
    "eslint-watch": "2.1.11",
    "eventsource-polyfill": "0.9.6",
    "expect": "1.19.0",
    "express": "4.13.4",
    "extract-text-webpack-plugin": "1.0.1",
    "file-loader": "0.8.5",
    "jsdom": "8.5.0",
    "mocha": "2.4.5",
    "nock": "8.0.0",
    "npm-run-all": "1.8.0",
    "open": "0.0.5",
    "react-addons-test-utils": "15.0.2",
    "redux-immutable-state-invariant": "1.2.3",
    "redux-mock-store": "1.0.2",
    "rimraf": "2.5.2",
    "style-loader": "0.13.1",
    "url-loader": "0.5.7",
    "webpack": "1.13.0",
    "webpack-dev-middleware": "1.6.1",
    "webpack-hot-middleware": "2.10.0"
},
```

1.2 Loaders

```
    {test: /\.js$/, include: path.join(__dirname, 'src'), loaders: ['babel']},
    {test: /(\.css)$/, loaders: ['style', 'css']},
    {test: /\.eot(\?v=\d+\.\d+\.\d+)?$/, loader: 'file'},
    {test: /\.(woff|woff2)$/, loader: 'url?prefix=font/&limit=5000'},
    {test: /\.ttf(\?v=\d+\.\d+\.\d+)?$/, loader: 'url?limit=10000&mimetype=application/octet-stream'},
    {test: /\.svg(\?v=\d+\.\d+\.\d+)?$/, loader: 'url?limit=10000&mimetype=image/svg+xml'}
```

1.4 Editor config

```
# EditorConfig is awesome: http://EditorConfig.org

# top-most EditorConfig file
root = true

# Unix-style newlines with a newline ending every file
[*]
end_of_line = lf
insert_final_newline = true

# Matches multiple files with brace expansion notation
# Set default charset
[*.{js,py}]
charset = utf-8

# 4 space indentation
[*.py]
indent_style = space
indent_size = 4

# Tab indentation (no size specified)
[Makefile]
indent_style = tab

# Indentation override for all JS under lib directory
[lib/**.js]
indent_style = space
indent_size = 2

# Matches the exact files either package.json or .travis.yml
[{package.json,.travis.yml}]
indent_style = space
indent_size = 2
```