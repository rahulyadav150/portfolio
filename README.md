# Portfolio site 
 A beautiful, lightweight, responsive, customizable single-page personal portfolio website built using React and Gatsby.
 
 ## Portfolio Sections
✔️ Summary and About me\
✔️ Skills\
✔️ Education\
✔️ Work Experience\
✔️ Big Projects\
✔️ Contact me\
✔️ Github Profile

To view a live example, **[click here](https://rahulyadavportfolio.netlify.app/)**.

## Testing

```bash
npm test
```

## Local Run

Set up your development environment

```bash
npm install
cp .env.template .env.development
```

Provide correct values in `.env.development` and proceed with local run:
```bash
npm start
```

## Deployment

Similar to `.env.development`, create a `.env.production` file with necessary variables.

Sign up for Netlify and install Netlify CLI

```bash
netlify login
```

Proceed with deployment:
```bash
npm run-script build
netlify deploy --dir=public --prod
```
