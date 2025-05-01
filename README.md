# OpenAPI Rutter TypeScript Client Generation Issue

This project demonstrates an issue with TypeScript client code generation using `@hey-api/openapi-ts` when processing the Rutter API specification.

## Overview

This repository serves as a test case for generating TypeScript client code from the [Rutter API specification](https://docs.rutter.com/rest/2024-08-31/spec). The project specifically highlights a bug where TypeScript type generation appears to be truncated after reaching a certain length.

## Issue Description

When generating TypeScript types from the Rutter API specification using `@hey-api/openapi-ts`, we've encountered the following issue:

- The TypeScript type definitions are not completely generated
- Type generation appears to stop/truncate after reaching a certain length
- This affects the usability and completeness of the generated client code

## Project Setup

### Prerequisites

- Node.js
- pnpm

### Installation

```bash
pnpm install
```

## Reproduction Steps

1. Clone this repository
2. Install dependencies using `pnpm install`
3. Run the test using `pnpm test` which will generate the types and run a TypeScript compilation check

## Related Links

- [Rutter API Documentation](https://docs.rutter.com/)
- [Rutter API Specification](https://docs.rutter.com/rest/2024-08-31/spec)
- [@hey-api/openapi-ts](https://www.npmjs.com/package/@hey-api/openapi-ts)

## License

MIT
