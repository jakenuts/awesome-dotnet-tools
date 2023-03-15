# awesome-dotnet-tools
A list of awesome dotnet tools

## Source Generators 

[ThisAssembly](https://github.com/devlooped/ThisAssembly) : A set of source generators that create constants from things like the paths of local files, assemblyinfo properties, git branch & commit and more!

## Actual 'dotnet tools' in the formal sense

## Dependencies & Versioning

- [Snitch](https://github.com/spectresystems/snitch) : A tool that help you find transitive package references that can be removed. 

- [dotnet-outdated](https://github.com/dotnet-outdated/dotnet-outdated) : A tool that allows you to quickly report on any outdated NuGet packages in your .NET Core and .NET Standard projects.

- [dotnet-please](https://github.com/morganstanley/dotnet-please/blob/main/README.md) : A swiss army knife for Visual Studio projects and solutions.This CLI tool aims to streamline some repetitive tasks around Visual Studio projects and solutions, including renaming multiple projects, extracting NuGet package versions into properties, and many more.  
    - Consolidate nuget packages across a solution, or only a subset of them
    - Keep package versions in a central props file and maintain that file
    - Move and rename projects
    - Clean up in case you manually moved and renamed
    - Clean up <Compile Remove="..." /> items, with or without globbing
    - To find stray projects
    - To remove ‘junk’ from solution directory
    - To change the PATH variable (useful when working with dotnet tools)
 
## Build & Deploy

- [dotnet-releaser](https://github.com/xoofx/dotnet-releaser) : An all-in-one command line tool that fully automates the release cycle of your .NET libraries and applications to NuGet and GitHub by building, testing, running coverage, cross-compiling, packaging, creating release notes from PR/commits and publishing.
  
  - dotnet build/test/pack/publish locally or from GitHub Action using the same command  
  - dotnet nuget push to publish your package to a NuGet registry
  - Pretty changelog creation from pull-requests and commits.
  - More..
  
