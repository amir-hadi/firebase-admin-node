## API Report File for "firebase-admin.instance-id"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { Agent } from 'http';

// Warning: (ae-forgotten-export) The symbol "App" needs to be exported by the entry point index.d.ts
//
// @public
export function getInstanceId(app?: App): InstanceId;

// @public
export class InstanceId {
    get app(): App;
    deleteInstanceId(instanceId: string): Promise<void>;
    }

// @public
export function instanceId(app?: App): instanceId.InstanceId;

// @public (undocumented)
export namespace instanceId {
    // (undocumented)
    export type InstanceId = InstanceId;
}


// (No @packageDocumentation comment for this package)

```