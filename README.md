# cyclondx-dev-dependency-reproduction

## steps to reproduce

- run `yarn install` in root directory
- run `cd package1`
- run `yarn exec cyclonedx-yarn --prod --spec-version 1.6 > sbom.json`
- see `eslint` in sbom.json which is a devDependency in package2
