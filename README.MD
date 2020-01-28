
> npm i -s https://github.com/arbncoltd/lint-typescript.git

Then in tslint.json

{
  "extends": ["./node_modules/arbntslint/tslint-config.json"],
  "rulesDirectory": [
    "codelyzer"
  ]
}
