# Test Frameworks Playground

A centralized repository showcasing test projects for popular .NET testing frameworks. This repository serves as a testing ground for validating Test Explorer functionality and testing platform implementations.

## Purpose

This repository helps with:

- **Manual Testing**: Verify that Test Explorer correctly discovers, displays, and runs tests
- **Test Execution**: Validate tests can be executed individually or in batches
- **Platform Validation**: Test changes to Microsoft Testing Platform (MTP) and `dotnet test`
- **Framework Compatibility**: Ensure different test frameworks work correctly with various test runners

## Test Projects

The repository includes test projects for the following frameworks:

### [MSTest](https://github.com/microsoft/testfx)

- `MSTest.MTP` - MSTest with Microsoft Testing Platform
- `MSTest.VSTest` - MSTest with VSTest platform

### [NUnit](https://nunit.org/)

- `NUnit.MTP` - NUnit with Microsoft Testing Platform
- `NUnit.VSTest` - NUnit with VSTest platform

### [xUnit.net](https://xunit.net/)

- `XUnit.MTPv1` - XUnit with Microsoft Testing Platform v1
- `XUnit.MTPv2` - XUnit with Microsoft Testing Platform v2

### [TUnit](https://github.com/thomhurst/TUnit)

- `TUnit.MTP` - TUnit with Microsoft Testing Platform

## Building

To build all test projects:

```bash
dotnet build TestFrameworksPlayground.slnx
```

To build a specific project:

```bash
dotnet build src/<ProjectName>/<ProjectName>.csproj
```

## Running Tests

Run all tests:

```bash
dotnet test TestFrameworksPlayground.slnx
```

Run tests for a specific project:

```bash
dotnet test src/<ProjectName>/<ProjectName>.csproj
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for information on contributing to this project.

This project has adopted the code of conduct defined by the [Contributor Covenant](http://contributor-covenant.org/) to clarify expected behavior in our community. For more information, see the [.NET Foundation Code of Conduct](http://www.dotnetfoundation.org/code-of-conduct).

## License

This project is licensed with the [MIT license](LICENSE).
