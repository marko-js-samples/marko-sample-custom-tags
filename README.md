Sample App: Marko Sample Custom Tags
======================================

This sample app illustrates how to create a set of custom tags that can be shared across multiple projects. This project includes a `marko-taglib.json` file in the root of the project that is used to export custom tags.

# Installation

Install this package into the project that wants to utilize these sample custom tags:

```bash
npm install marko-sample-custom-tags --save
```

After this package has been installed, the custom tags exported by this package can then be used within Marko templates found in the parent project:

```xml
<sample-custom-tags-say-hello name="Jane"/>
<sample-custom-tags-foo/>
```

_NOTE: The names of the custom tags can be whatever you want. However, it is recommended to prefix the custom tag name with the name of the package that it came from to avoid confusion (hence the long names for these custom tags)._