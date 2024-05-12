# Java Kits

## Introduce

VS Code Java Application Development Extension Pack.

## Recommended Configuration

- User Settings
```json
{
    "maven.settingsFile": "/path/maven/conf/settings.xml",
    "maven.executable.path": "/path/maven/bin/mvn",
}
```

- Workspace Settings
```json
{
    "java.jdt.ls.java.home": "/path/jdk",
    "java.configuration.updateBuildConfiguration": "automatic",
    "java.configuration.maven.globalSettings": "/path/maven/conf/settings.xml",
    "java.configuration.maven.userSettings": "/path/maven/conf/settings.xml",
    "java.compile.nullAnalysis.mode": "automatic",
    "java.format.enabled": true,
    "java.maven.downloadSources": false,
    "maven.excludedFolders": [
      "**/.*",
      "**/node_modules",
      "**/target",
      "**/bin",
      "**/archetype-resources"
    ],
    "xml.format.legacy": true,
    "xml.format.preservedNewlines": 1,
    "redhat.telemetry.enabled": false,
    "java.inlayHints.parameterNames.enabled": "none",
    "boot-java.validation.java.version-validation": "OFF"
    // detail: https://google.github.io/styleguide/javaguide.html
    // "java.format.settings.profile": "GoogleStyle",
    // "java.format.settings.url": "google-style.xml",
}
```
