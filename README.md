# Apache Annotator (incubating) Website

The site is currently in static HTML hosted out of the `content/` directory.

Any pre-generated/rendered content or documentation should be added to additional
folders in the root of this repo.

## Publishing

Currently, `master` and `asf-site` should be kept in sync. The `asf-site`
branch gets published to an Apache HTTPD static hosting environment run by
the Apache infrastructure team.

## Developing

Install dev dependencies with `npm install`.

Compile the ES6 code with `npm run build`.

Code for the demo lives inside of the `src/` directory.

# License

Apache License 2.0 (obviously...:wink:)
