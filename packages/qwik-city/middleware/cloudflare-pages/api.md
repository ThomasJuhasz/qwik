## API Report File for "@builder.io/qwik-city"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ServerRenderOptions } from '@builder.io/qwik-city/middleware/request-handler';

// @alpha (undocumented)
export function createQwikCity(opts: QwikCityCloudflarePagesOptions): ({ request, env, waitUntil, next }: EventPluginContext) => Promise<Response>;

// @alpha (undocumented)
export interface EventPluginContext {
    // (undocumented)
    env: Record<string, any>;
    // (undocumented)
    next: (input?: Request | string, init?: RequestInit) => Promise<Response>;
    // (undocumented)
    request: Request;
    // (undocumented)
    waitUntil: (promise: Promise<any>) => void;
}

// @alpha (undocumented)
export interface PlatformCloudflarePages {
    // (undocumented)
    env?: EventPluginContext['env'];
}

// @alpha (undocumented)
export interface QwikCityCloudflarePagesOptions extends ServerRenderOptions {
}

// (No @packageDocumentation comment for this package)

```
