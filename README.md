# lsw-depender

Dependency manager abstraction for LSW.

## Installation

```sh
npm install -s @allnulled/lsw-depender
```

## Importation

```html
<script src="node_modules/@allnulled/lsw-depender/lsw-depender.js"></script>
```

## API

The signatures of the two classes are:

```js
class LswDepender {
    hasDefined(name)
    define(...args)
    resolve(idsInput = this, defs = this.$definitions)
    addDefinition(name, definition, shouldFailOnRedundancy = 1, shouldOverrideOnRedundancy = 1)
    addUniqueDefinitions(moreDefinitions = {})
    addMissingDefinitions(moreDefinitions = {})
    resetDefinitions(moreDefinitions = {})
    deleteDefinitions(definitionsInput = [])
}
```

# Conclusion

For now, this is not a virtuous package in the domain. Just to pack on the same place the utilities needed for the way.