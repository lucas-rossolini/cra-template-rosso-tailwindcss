<div id="top"></div>
<div align="center">
  
  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![Issues][issues-shield]][issues-url]
  [![MIT License][license-shield]][license-url]
  
  <br>

  <h1>ROSSO-TAILWIND</h1>

### A personnal `cra-template` based

#### Front-end Exclusively

#### Install ReactJS with some additionals packages

#### Eslint is configured on preset airbnb with 3 rules in "warn"

#### Default font-familly: Monserrat

#### Custom Readme

#### Work with NodeJs >= 14

</div>

<br>
<hr>
<br>

## Additionals Dependencies Packages:

🗸 「 AXIOS 」<br />
🗸 「 DOTENV 」<br />
🗸 「 REACT-ROUTER-DOM 」<br />
🗸 「 SASS 」<br />

<br>
<hr>
<br>

## Additionals Dev Dependency Package:

🗸 「 PRETTIER 」<br />
🗸 「 ESLINT 8 」 - And Co'<br />
🗸 「 TAILWINDCSS 」<br />

<br>
<hr>
<br>

## Preflight activated to work with ESLINT 8

Its allow the use of Eslint 8 with current ReactApp.<br>
You can find it in `.env`, this line :

```sh
SKIP_PREFLIGHT_CHECK=true
```

<br>
<hr>
<br>

## Eslint configuration:

🗸 Preset: `airbnb`<br />

3 rules in "warn":<br />

- react/function-component-definition
- no-console
- import/no-extraneous-dependencies

<br>
<hr>
<br>

## Jsconfig

🗸 I've created a configurated `jsconfig.json` for this project who work fine with Visual Studio Code.<br>    So, use it if you want !

<br>
<hr>
<br>

## Be sure to use the right command at installation:

- <b>NPX</b>

  ```sh
  npx create-react-app my-app --template rosso-tailwind
  ```

- <b>NPM</b>

  ```sh
  npm init react-app my-app --template rosso-tailwind
  ```

- <b>YARN</b>
  ```sh
  yarn create react-app my-app --template rosso-tailwind
  ```

<br>
<hr>
<br>

## After installing, launch this command to fix potential error with eslint (not required)

These command fix eslint to work with prettier. I don't know why its required but you can't use this template without doing this if you have the error: "prettier/prettier"

- <b>NPM</b>

  ```sh
  npm update -R eslint
  ```

- <b>YARN</b>
  ```sh
  yarn update -R eslint
  ```

<a href="#top">Back to Top</a>

<br>
<hr>
<br>

## For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.
- [Default Template](https://github.com/facebook/create-react-app/tree/main/packages/cra-template) – Template installed if no template option passed.
- [Cra-Template](https://github.com/facebook/create-react-app) – Used in the official Create React App

[contributors-shield]: https://img.shields.io/github/contributors/lucas-rossolini/cra-template-rosso-tailwindcss.svg?style=for-the-badge
[contributors-url]: https://github.com/lucas-rossolini/cra-template-rosso-tailwindcss/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lucas-rossolini/cra-template-rosso-tailwindcss.svg?style=for-the-badge
[forks-url]: https://github.com/lucas-rossolini/cra-template-rosso-tailwindcss/network/members
[stars-shield]: https://img.shields.io/github/stars/lucas-rossolini/cra-template-rosso-tailwindcss.svg?style=for-the-badge
[stars-url]: https://github.com/lucas-rossolini/cra-template-rosso-tailwindcss/stargazers
[issues-shield]: https://img.shields.io/github/issues/lucas-rossolini/cra-template-rosso-tailwindcss.svg?style=for-the-badge
[issues-url]: https://github.com/lucas-rossolini/cra-template-rosso-tailwindcss/issues
[license-shield]: https://img.shields.io/github/license/lucas-rossolini/cra-template-rosso-tailwindcss.svg?style=for-the-badge
[license-url]: https://github.com/lucas-rossolini/cra-template-rosso-tailwindcss/blob/main/LICENSE
