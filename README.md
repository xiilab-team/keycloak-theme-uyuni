<h1 align="center">Uyuni keycloak Theme π</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
</p>

## Install

```sh
npm install
```

## Usage


1. dev μλ² μμνκΈ°

    ```sh
    npm run start
    ```

2. `src/utils/keycloakManager.ts` νμΌμμ 27λ²μ§Έ μ£Όμ ν€μ¬
    ```typescript
      ({
      // @cindy.choi
      // μλμ λλ²κΉμ μνλ νμ΄μ§ μ£Όμμ ν΄μ νλ©΄ νλ¨μ mockDataλ₯Ό μ μ©νμ¬ λ‘μ»¬μ νμ΄μ§λ₯Ό λμΈ μ μμ΅λλ€.
       "mockPageId": "login.ftl",
      // "mockPageId": "register.ftl",
      // "mockPageId": "login-update-profile.ftl",
      // // @ts-ignore
      // "mockPageId": "login-update-password.ftl",
      // "mockPageId": "info.ftl",
      // "mockPageId": "error.ftl",
    ```

## Build and deploy

1. λ€μ λͺλ Ήμ΄ μ€ν

    ```sh
    npm run keycloak
    ```

2. `build_keycloak/src/main/resources/theme` ν΄λμμ μλ ν΄λλ€μ keycloak μ€μΉ μλ²μ `/opt/jboss/keycloak/themes` μΌλ‘ λ³΅μ¬

## Show your support

Give a β­οΈ if this project helped you!

***
_This README was generated with β€οΈ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_