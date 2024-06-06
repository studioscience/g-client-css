# g-client-css
TEMPORARY repository to facilitate the buildout of the project.

This repository houses a stylesheet file. Once edited, the stylesheet is published to a public link. This link can then be inclueded in the head section of an experience cloud site.

Public Link to stylesheet: https://studioscience.github.io/g-client-css/style.css

## Adding to Experience Cloud
In the HEAD of the experience cloud, incude this line

```
<link rel="stylesheet" href="https://studioscience.github.io/g-client-css/style.css"/>
```

## Content Security Policy
CSP will need to ALLOW list the published URL. Must be done in the Trusted URL section of setup, using the style-src.

## Temporary Solution
Once development is complete, and the stylesheet is stable, it will be included in the Salesforce Experience Builder site either as a static resource or directly into the HEAD of the site.

This will ensure as many sources as possible are housed in Salesforce servers.

