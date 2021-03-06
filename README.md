# CastleCSS generator (beta)
This generator is based on [Yeoman](http://yeoman.io). It can generate a boilerplate for a 
[CastleCSS](https://github.com/CastleCSS/) project. It gives more flexibility than the 
[castlecss-boilerplate](https://github.com/CastleCSS/castlecss-boilerplate/) because the generator
lets you pick which components of castlecss you want to use.

## Requirements
To use this generator, you must have NPM and Yeoman installed: ```npm install yo -g```

## How to use
- ```npm install generator-castlecss -g```
- ```yo castlecss```
- Follow the prompt

## Arguments
Any questions a user will be prompted for can be overridden with CLI options, for example:
```yo castlecss --projectname example```

## Contributing
To use  the generator locally, use ```npm install <local-path-to-repo>``` in the root of the repo, and then
 use the ```yo``` command to select the generator.