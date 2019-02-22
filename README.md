# api-caching
A simple service worker that will record api responses, and serve the latest response up from the cache when a service goes down.

In the case of developing against an unstable API, this SW will be enable local FE development to continue with the latest successful API response, until the backend services resolve successfully.
