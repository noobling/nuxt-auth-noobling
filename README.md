# Azure Active Directory Authentication with Nuxt
This library extends up nuxt auth to add AAD support to Nuxt

## Getting started

1. 
```bash
$ yarn add nuxt-auth-noobling
```

2. Then add the required details to `nuxt.config.js`
Look at the demo for an example https://github.com/noobling/auth-module/blob/dev/examples/demo/nuxt.config.js

3. Create a page to display the callback which will fetch the access token 

4. login with `$auth.loginWith('aad')`


## Development

Running demo for development:

```bash
$ yarn install
$ yarn dev
```

## License

[MIT License](./LICENSE) - Copyright (c) Nuxt Community
