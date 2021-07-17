# `@blu3r4y/air-datepicker-types`

[![npm Version](https://img.shields.io/npm/v/@blu3r4y/air-datepicker-types?style=for-the-badge)](https://www.npmjs.com/package/@blu3r4y/air-datepicker-types)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/blu3r4y/air-datepicker-types/publish-npm-package?style=for-the-badge)](https://github.com/blu3r4y/air-datepicker-types/actions/workflows/publish-npm-package.yml)

TypeScript definitions for [air-datepicker](https://www.npmjs.com/package/air-datepicker)

## Installation

Install with alias `@types/air-datepicker` so that types are linked with your `air-datepicker` package.

```shell
# the npm way
npm install -D @types/air-datepicker@npm:@blu3r4y/air-datepicker-types

# the yarn way
yarn add -D @types/air-datepicker@npm:@blu3r4y/air-datepicker-types
```

## Usage

Don't forget to also import the `air-datepicker` package along with the types.

```typescript
import "air-datepicker";                                 // artifacts 
import { AirDatepickerInstance } from "air-datepicker";  // types
```

If you didn't install the package with an alias, you must import from `@blu3r4y/air-datepicker-types` instead.

### Exported Types

- `AirDatepickerStatic`
- `AirDatepickerInstance`
- `AirDatepickerLanguageInstance`
- `AirDatepickerEventObject`
- `AirDatepickerOptions`

As well as bindings to `jquery`

- `JQuery.datepicker`
- `JQuery.data("datepicker")`
