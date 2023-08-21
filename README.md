![Freshli Logo](logo-banner.png)

# Freshli

Freshli is a tool for collecting historical metrics about a project's dependencies. View graphs about how your projects' dependency freshness has changed over time.

You can use Freshli in a number of ways:

| Type | Description |
|--------------------|-----------------------|
| [Homepage](https://freshli.app/) | Freshli marketing website |
| [Website UI](https://freshli.io/) | Website that displays analysis reports. Provides a publication API to the CLI application. This is a closed-source project, and access to reports will eventually be monetized. |
| [Freshli API](https://api.freshli.io) | Targeted for initial release with version 0.7.0, this will be the API that both Freshli UI and Freshli CLI use. This is a closed-source project, and access will be limited to users with Freshli UI accounts. |
| [Command Line (CLI)](https://github.com/corgibytes/freshli-cli) | Analyze a local project. Results are viewable via the [Website App](https://freshli.io). |
| [Command Line Java Language Agent](https://github.com/corgibytes/freshli-agent-java) | Language-specific agent program that knows how to process dependencies from the Java ecosystem |
| [Command Line DotNet Language Agent](https://github.com/corgibytes/freshli-agent-dotnet) (in progress) | Language-specific agent program that knows how to process dependencies from the .NET ecosystem |
| [Command Line Python Language Agent](https://github.com/corgibytes/freshli-agent-python) (in progress) | Language-specific agent program that knows how to process dependencies from the Python ecosystem |
| [Command Line Go Language Agent](https://github.com/corgibytes/freshli-agent-go) (in progress) | Language-specific agent program that knows how to process dependencies from the Go ecosystem |

## Roadmap

You can view the [GitHub project](https://github.com/orgs/corgibytes/projects/9) to see the work that we have planned. The ["Roadmap" tab](https://github.com/orgs/corgibytes/projects/9/views/6) shows the milestones we've assigned each Epic to. We've elected to use the same version numbers across all of the Freshli projects to help communicate which work will be completed simultaneously. We're currently working on releasing version 0.6.0.

## Related Projects

The following libraries support the functionality of either the CLI, a language agent, or the website.

| Name | Description |
|------|-------------|
| [Freshli Commons](https://github.com/corgibytes/freshli-commons) | A small Ruby Gem containing common code used by build scripts and Cucumber/Aruba tests in most Freshli repositories |
| [Dependency History Maven](https://github.com/corgibytes/dependency-history-maven) | A Java library that knows how to determine a package's release history using the information in Maven. Used by `freshli-agent-java` and the fork of the Versions Maven Plugin. |
| [Versions Maven Plugin (fork)](https://github.com/corgibytes/versions-maven-plugin) | A fork of the [Maven Versions Plugin](https://www.mojohaus.org/versions-maven-plugin/) that adds a Maven goal that can be run to resolve version ranges to a specific version number that was available on a particular date. This is required to collect historical data correctly. |

## Questions?  Spot a Bug?
If you have any general questions about Freshli or spot an issue with the Freshli [UI](https://freshli.io/), API, or marketing website, please open an [issue](https://github.com/corgibytes/freshli/issues).  

If you have questions about an Open Source Freshli project, please enter them in the appropriate repository. We are also accepting pull requests for these projects.

### Freshli CLI
- [Issues](https://github.com/corgibytes/freshli-cli/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-cli/pulls)

### Java Language Agent
- [Issues](https://github.com/corgibytes/freshli-agent-java/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-agent-java/pulls)

### DotNet Language Agent
- [Issues](https://github.com/corgibytes/freshli-agent-dotnet/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-agent-dotnet/pulls)

### Python Language Agent
- [Issues](https://github.com/corgibytes/freshli-agent-python/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-agent-python/pulls)

### Go Language Agent
- [Issues](https://github.com/corgibytes/freshli-agent-go/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-agent-go/pulls)

### `freshli-commons` Ruby Gem
- [Issues](https://github.com/corgibytes/freshli-commons/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-commons/pulls)
- [RubyGems](https://rubygems.org/gems/freshli-commons)

### Dependency History Maven
- [Issues](https://github.com/corgibytes/dependency-history-maven/issues)
- [Pull Requests](https://github.com/corgibytes/dependency-history-maven/pulls)
