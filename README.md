<br/>
<h1 align="center">
  PNPM and Github Packages Workflow
</h1>
<p align="middle">
  An example Github Action using PNPM and Github Packages. 
  </p>
<br/>
<p align="center">
  <a href="https://github.com/tbusillo/pnpm-vite-react-github-action-example/actions/workflows"><img src="https://github.com/tbusillo/pnpm-vite-react-github-action-example/actions/workflows/test.yml/badge.svg" alt="CI status"></a>
</p>
<br/>

## Features

- PNPM
- Caching of dependencies
- Authorization to Github packages and downloading of a private dependency
- Test/lint steps

## Installation

- Copy and paste the workflow in `dist/workflow.yml` and replace the commands/sections where commented. 
- Add the file to your repository's `.github/workflows` directory
- That's it! 

## Usage

- Use to automate retrieval/caching of dependencies using PNPM and Github actions. 
- Run your project's tests/linting rules to reduce regressions in an automated way. 

## License

MIT License

Copyright (c) 2022 Tom