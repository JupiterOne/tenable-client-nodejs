# tenable-client-nodejs

## Installation

```
# Install with NPM
> npm install @jupiterone/tenable-client-nodejs

# Install with Yarn
> yarn install @jupiterone/tenable-client-nodejs
```

## Usage

```typescript
import { TenableClient } from '@jupiterone/tenable-client-nodejs';

const client = new TenableClient({
  // required for authentication
  accessKey: 'access-key',
  secretKey: 'access-key',
  // required for the `user-agent` header
  vendor: 'access-key',
  product: 'access-key',
  build: 'access-key',
});

client.fetchUsers()
  .then((r) => console.log(r))
  .catch((e) => console.error(e))
```


some readme change  