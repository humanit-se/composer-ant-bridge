# Composer Ant Bridge
Composer script that runs Ant build-script for installed packages

## Use

Add script to projects composer.json
```
"scripts": {
    "antbuilder": [
        "ComposerAntBridge\\Packages::build"
    ]
}
```

Call:

```
composer run-script antbuilder
```
