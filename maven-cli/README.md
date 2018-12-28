# GitHub Action for Maven

The GitHub Action for [Maven](https://maven.apache.org/) wraps the Maven CLI to enable Maven commands to be run. This can be used to run every Maven Command.

## Usage

```
action "package" {
  uses = "systelab/github-actions/maven-cli@master"
  args = "clean install"
}
```

## License

The Dockerfile and associated scripts and documentation in this project are released under the [MIT License](LICENSE.md).
