# QWED JavaScript SDK

Official JavaScript/TypeScript client for the QWED Verification Engine.

## Installation

```bash
npm install qwed-sdk
```

## Quick Start

```typescript
import { QwedClient } from 'qwed-sdk';

const client = new QwedClient("YOUR_API_KEY", "http://13.71.22.94:8000");
const result = await client.verifyNaturalLanguage("What is 10 + 10?");
console.log(result.finalAnswer); // 20.0
```

## Documentation

Full documentation at: https://github.com/rahuldass19/qwed-open
