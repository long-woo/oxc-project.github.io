<!-- This file is auto-generated by tasks/website/src/linter/rules/doc_page.rs. Do not edit it manually. -->

# import/no-self-import <Badge type="info" text="Suspicious" />

<div class="rule-meta">
</div>

### What it does

Forbid a module from importing itself. This can sometimes happen during refactoring.

### Example

```javascript
// foo.js
import foo from "./foo.js";
const foo = require("./foo");
```

## References

- [Rule Source](https://github.com/oxc-project/oxc/blob/main/crates/oxc_linter/src/rules/import/no_self_import.rs)
