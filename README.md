# ared-sme-v2

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Run your unit tests

```
yarn test:unit
```

### Run your end-to-end tests

```
yarn test:e2e
```

### Lints and fixes files

```
yarn lint
```

### Author

- [Emmanuel Dushime](https://github.com/dushimeemma) - Full-stack Developer


# APIs INTEGRATED

## https://dev.api.shirikihub.com/api/v1/auth/jwt/create/
  
  This api is used to login the user 

## https://dev.api.shirikihub.com/api/v1/2fa/
  
  This api is used to send the OTP for login

## https://dev.api.shirikihub.com/api/v1/2fa/verify/
  
  This api is used to verify the OTP that is sent while login

## https://dev.api.shirikihub.com/api/v1/auth/users/reset_password/
  
  This api is used for forgot password 

## https://dev.api.shirikihub.com/api/v1/auth/users/set_password/
  
  This api is used for change old password 

## https://dev.api.shirikihub.com/api/v1/auth/users/me/
  
  This api is used to fetch  details of logged in user

## https://dev.api.shirikihub.com/api/v1/routers/?sme=1

 This api is used for listing of routers

## https://dev.api.shirikihub.com/api/v1/vouchers/?realm__sme=1

  This api is used for listing of vouchers

## https://dev.api.shirikihub.com/api/v1/files/?realm__sme=1&status=Enabled

  This api is used for listing of files

## https://dev.api.shirikihub.com/api/v1/tickets/?user__sme=1

  This api is used for listing of tickets 

## https://dev.api.shirikihub.com/api/v1/tickets/?user__sme=1&department=Router

  This api is used for listing of Router Department Tickets 

## https://dev.api.shirikihub.com/api/v1/tickets/?user__sme=1&department=Other

  This api is used for listing of Other Department Tickets 