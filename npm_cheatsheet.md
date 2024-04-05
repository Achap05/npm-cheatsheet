# Packages

npm manages downloads of dependencies of your project.

Installing all dependencies

If a project has a package.json file, by running

```npm install```

Bash

it will install everything the project needs, in the node_modules folder, creating it if it's not existing already.

Installing a single package

You can also install a specific package by running

```npm install <package-name>```

Flags

```--save-dev``` 
    
    installs and adds the entry to the package.json file devDependencies

 ```--no-save installs``` 
 
 but does not add the entry to the package.json file dependencies

 ```--save-optional installs``` 
 
 and adds the entry to the package.json file optionalDependencies

 ```--no-optional will prevent optional dependencies from being installed```

Shorthands of the flags can also be used:

 ```-S: --save```
 ```-D: --save-dev```
 ```-O: --save-optional``

## Updating packages

Updating is also made easy, by running

```npm update```

Bash

npm will check all packages for a newer version that satisfies your versioning constraints.

You can specify a single package to update as well:

```npm update <package-name>```

Bash