# Generate React CLI Setup Guide

## Introduction

This guide will help you set up and customize the Generate React CLI for your project. The Generate React CLI is a powerful tool that streamlines the creation of React components, ensuring consistency and efficiency in your development process.

## Installation

To begin, you need to initialize the Generate React CLI in your project. Run the following command in your project directory:

```sh
npx generate-react-cli init
You will be prompted to answer a series of questions to customize the Generate React CLI according to your project's requirements. Below are the questions you will be asked, along with the preferred responses:

plaintext
Code kopieren
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
It looks like this is the first time that you're running generate-react-cli within this project.

Answer a few questions to customize generate-react-cli for your project needs (this will create a "generate-react-cli.json" config file on the root level of this project).
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

? Does this project use TypeScript? Yes
? Does this project use styled-components? No
? Does this project use CSS modules? Yes
? Does this project use a CSS Preprocessor? scss
? What testing library does your project use? Testing Library
? Set the default path directory to where your components will be generated in? src/components
? Would you like to create a corresponding stylesheet file with each component you generate? Yes
? Would you like to create a corresponding test file with each component you generate? Yes
? Would you like to create a corresponding story with each component you generate? Yes
? Would you like to create a corresponding lazy file (a file that lazy-loads your component out of the box and enables code splitting: https://reactjs.org/docs/code-splitting.html#code-splitting) with each component you generate? Yes
After completing these prompts, a generate-react-cli.json configuration file will be created at the root level of your project.

Generating Components
With the Generate React CLI initialized and configured, you can now generate components with ease. Use the following command to create a new TypeScript component:

sh
Code kopieren
npx generate-react-cli component MyComponent --type=typescript
This command will generate a new component named MyComponent with the following structure:

src/
└── components/
    └── MyComponent/
        ├── MyComponent.tsx
        ├── MyComponent.module.scss
        ├── MyComponent.test.tsx
        ├── MyComponent.stories.tsx
        └── MyComponent.lazy.tsx
Customization and Further Reading
The generate-react-cli.json file allows for further customization of the Generate React CLI. You can modify this file to change default settings, paths, and other options as needed.

For more detailed information and advanced usage, please refer to the Generate React CLI documentation.

Happy coding!