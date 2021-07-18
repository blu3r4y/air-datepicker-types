# TypeScript definitions for [air-datepicker](https://www.npmjs.com/package/air-datepicker)

[![npm Version](https://img.shields.io/npm/v/@blu3r4y/air-datepicker-types?style=for-the-badge)](https://www.npmjs.com/package/@blu3r4y/air-datepicker-types)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/blu3r4y/air-datepicker-types/publish-npm-package?style=for-the-badge)](https://github.com/blu3r4y/air-datepicker-types/actions/workflows/publish-npm-package.yml)

```bash
# the npm way
npm install -D @blu3r4y/air-datepicker-types

# the yarn way
yarn add -D @blu3r4y/air-datepicker-types
```

## Usage

Explicitly import the types from this package.

```typescript
import "air-datepicker";
import { AirDatepickerInstance } from "@blu3r4y/air-datepicker-types";
```

If you want to import everything directly from `air-datepicker`, you could [alias](https://docs.npmjs.com/cli/v7/commands/npm-install) the package under `@types/air-datepicker` instead.
However, I would **not** recommend it because the versions aren't tracked properly anymore then.

```bash
# install with alias
npm install -D @types/air-datepicker@npm:@blu3r4y/air-datepicker-types
```

### Exported Types

- `AirDatepickerStatic`
- `AirDatepickerInstance`
- `AirDatepickerLanguageInstance`
- `AirDatepickerEventObject`
- `AirDatepickerOptions`

As well as bindings to `jquery`

- `JQuery.datepicker`
- `JQuery.data("datepicker")`
