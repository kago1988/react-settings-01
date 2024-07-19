Install create-react-app
```sh
npm install -g create-react-app
```

Initialize a project with TS 
```sh
npx create-react-app my-app --template typescript
```

Install `generate-react-cli`
```sh
npm install -g generate-react-cli 
```

Initialize generate-react-cli in in the root of your project. Same folder as `package.json`
```sh
npx generate-react-cli init 
```

Questions from `create-react-cli`
```
? Does this project use TypeScript? Yes

? Does this project use styled-components? No

? Does this project use CSS modules? Yes

? Does this project use a CSS Preprocessor? scss

? What testing library does your project use? Testing Library

? Set the default path directory to where your components will be generated in? src/components

? Would you like to create a corresponding stylesheet file with each component you generate? Yes

? Would you like to create a corresponding test file with each component you generate? Yes

? Would you like to create a corresponding story with each component you generate? Yes

? Would you like to create a corresponding lazy file (a file that lazy-loads your component out of the box and enables code splitting: 
https://reactjs.org/docs/code-splitting.html#code-splitting) with each component you generate? Yes
```

Create a component inside src/components 
```sh
npx generate-react-cli component MyComponent
```

Create a component inside src/components/MyComponent2 
```sh
npx generate-react-cli component MyComponent2/MyComponent
```
