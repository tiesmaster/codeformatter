# XUnitConverter

[![Build
Status](https://dev.azure.com/tiesmaster/xunit-converter/_apis/build/status/xunit-converter%20%5Bpull%20request%5D?branchName=master)](https://dev.azure.com/tiesmaster/xunit-converter/_build/latest?definitionId=2&branchName=master)

This is a tool for converting projects from using MSTest to XUnit.  This tool automates many of the repetitive tasks like changing to `[Fact]` attributes, using the correct methods on `Assert`, updating namespaces, etc ...

## Usage
The tool takes only the project to be converted as an argument.

```
xunitconverter <project path>
```

## Contributing
This is a fork of dotnet/codeformatter, and only focuses on XUnitConverter. I'd love to receive contributions ;)
