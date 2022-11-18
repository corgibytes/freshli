# Freshli

Freshli is a tool for collecting historical metrics about a project's dependencies. View graphs about how your projects' dependency freshness has changed over time.

You can use Freshli in a number of ways:

| Type | Description |
|--------------------|-----------------------|
| [Homepage](https://freshli.app/) | Freshli marketing website |
| [Website App](https://freshli.io/) | Website that displays analysis reports. Provides a publication API to the CLI application. This is a closed source project, and access to reports will eventually be monetized. |
| [Command Line (CLI)](https://github.com/corgibytes/freshli-cli) | Analyze a local project. Results are viewable via the [Website App](https://freshli.io). |
| [Command Line Java Language Agent](https://github.com/corgibytes/freshli-agent-java) | Language-specific agent program that knows how to process dependencies from the Java ecosystem |


## Related Projects

The following libraries support the functionality of either the CLI, a language agent, or the website.

| Name | Description |
|------|-------------|
| [Dependency History Maven](https://github.com/corgibytes/dependency-history-maven) | A Java library that knows how to determine a package's release history using information in Maven. Used by `freshli-agent-java` and the fork of the Versions Maven Plugin. |
| [Versions Maven Plugin (fork)](https://github.com/corgibytes/versions-maven-plugin) | A fork of the [Maven Versions Plugin](https://www.mojohaus.org/versions-maven-plugin/) that adds a Maven goal that can be run to resolve version ranges to a specific version number that was available on a particular date. This is required to correctly collect historical data. |

## Questions?  Spot a Bug?
If you have any general questions about Freshli or spot an issue with the Freshli [website](https://freshli.io/), please open an [issue](https://github.com/corgibytes/freshli/issues).  

If you have questions about Freshli Command Line or Library please enter them in the appropriate repository. We are also accepting pull requests for these open source projects.

### Freshli CLI
- [Issues](https://github.com/corgibytes/freshli-cli/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-cli/pulls)

### Java Language Agent
- [Issues](https://github.com/corgibytes/freshli-agent-java/issues)
- [Pull Requests](https://github.com/corgibytes/freshli-agent-java/pulls)

### Dependency History Maven
- [Issues](https://github.com/corgibytes/dependency-history-maven/issues)
- [Pull Requests](https://github.com/corgibytes/dependency-history-maven/pulls)
