
# node-github [![Build Status](https://secure.travis-ci.org/Looney-Dev/node-github.png)](http://travis-ci.org/Looney-Dev/node-github)

> Node.JS GitHub API (v3) Wrapper

### Installation

```bash
$ npm install github
```

### Example Code

```javascript

var github = require('github');

// get user information
github.getUser('Looney-Dev', function(error, user) {
  console.log(user);
});

// get users repos
github.getUserRepos('Looney-Dev', function(error, repos) {
  console.log(repos);
});

// get users watched repos
github.getUsersWatched('Looney-Dev', function(error, watched) {
  console.log(watched);
});

// get an organizations github users
github.getOrgMembers('github', function(error, members) {
  console.log(members);
});

```

### Running Tests

	* Tests are being reworked. Considering using process.env['github_username'] etc...?

### License (MIT)

Copyright (c) 2019, [Looney - Jimmy.](https://looney.gq)

**

Author: [Jimmy - Looney][0]

 
[0]: https://github.com/Looney-Dev/

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Looney-Dev/node-github/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
