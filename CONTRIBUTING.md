# CONTRIBUTING
For new features or in case of bugs, please log an issue on the [tallchai/akshar-type](https://github.com/tallchai/akshar-type) repo.

## GlyphsApp
Akshar was built with GlyphsApp, a popular font development tool.
To contribute, you will need a Mac and a licensed copy of GlyphsApp.

## Building
To build the fonts from the source file, you will need to install [gftools](https://github.com/googlefonts/gftools).
Once you have installed it, run the following:
`gftools builder sources/builder.yaml` from the root of the project.

This should build the font files based on the configuration specified in sources/builder.yaml.

Update the version number for the font. Follow the [Semantic Versioning](https://semver.org/) guidelines when updating the version. In the [CHANGELOG](CHANGELOG.md) file, list the enhancements/updates/fixes made under the new version number.
