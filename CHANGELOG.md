# Change Log

## 0.3.0

Pre-release

- Fixed multi-line comments in class fields obtained from VU-Docs [Issue 8](https://github.com/Imposter/vscode-lua-vu/issues/8)
- Ability to disable intermediate file generation [Issue 9](https://github.com/Imposter/vscode-lua-vu/issues/10)
- Add json library [Issue 11](https://github.com/Imposter/vscode-lua-vu/issues/11)
- Fix vector types and allow them to be indexed [Issue 12](https://github.com/Imposter/vscode-lua-vu/issues/12)
- Differentiate between integer and number (floating point values) [Issue 13](https://github.com/Imposter/vscode-lua-vu/issues/13)
- Support for tuple (many) return types [Issue 14](https://github.com/Imposter/vscode-lua-vu/issues/14)
- Fix static fields not appearing in meta data [Issue 17](https://github.com/Imposter/vscode-lua-vu/issues/17)
- Allow editing of mod.json through the Vua commands [Issue 19](https://github.com/Imposter/vscode-lua-vu/issues/19)
- Allow aborting of create project [Issue 20](https://github.com/Imposter/vscode-lua-vu/issues/20)
- Reorganize project layout [Issue 15](https://github.com/Imposter/vscode-lua-vu/issues/15)

## 0.2.10

Pre-release

- Fix definition downloads [Issue 9](https://github.com/Imposter/vscode-lua-vu/issues/9)

## 0.2.9

Pre-release

- Fixed grammar issues

## 0.2.8

Pre-release

- Added better error messages for intermediate file errors

## 0.2.7

Pre-release

- Open new project correctly
- Implemented code generation configuration, allowing users to force class definitions to the global scope for intellisense
- Added support for updating project types/support libraries with latest ones from their respective git repositories

## 0.2.6

Pre-release

- Update extension name and version

## 0.2.5

Pre-release

- Update package dependencies to include `@microsoft/vscode-file-downloader-api` as a dependency rather than a dev dependency
- Removed unused package dependencies

## 0.2.4

Pre-release

- Update VSCode builds

## 0.2.3

Pre-release

- Correctly handle documentation comments
- Generate multiline doc comments correctly
- Correctly generate variadic arguments for functions in stub generator

## 0.2.2

Initial public pre-release of the extension.

- User type generation
- VU doc stub generation
- Project support
- Type caching
- Documentation support
