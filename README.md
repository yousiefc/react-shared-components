# React Shared Components

Shared reusable react BCGov themed components.

## Getting started

In order for projects to consume a new version, create a new release on this repository with the updated semantic version. Once the release is created, edit the release and upload the generated _shared-components-X.X.X.tgz_ file to the release. Once this is complete, update your project's package.json file to the following (current latest release):

```
"dependencies": {
    ...
    "shared-components": "https://github.com/bcgov/react-shared-components/releases/download/0.5.2/shared-components-0.5.2.tgz",
    ...
},
```

## Creating a release

Run the following commands locally when ready to release:

```bash
yarn install
```

```bash
npm pack
```

Running the pack command will create a _shared-components-X.X.X.tgz_ file in the root level of the project that contains the components ready for consumption by any project.
