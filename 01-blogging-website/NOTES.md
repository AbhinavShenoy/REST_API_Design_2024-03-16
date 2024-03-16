## Notes

- In case of high number of query parameters: 
    - Put the parameters in Request Body (Might get stripped away by CDN)
    - Put it in a POST request
    - Ideally refactor the architecture such that it doesn't happen

- PUT vs PATCH (Idempotency)

- Server side validation is the real validation. Client side validation is only to make UX better

- Using accurate Response codes is important

- Base url should have versions (/v1). So that in case of breaking changes it can be migrated from v1 to v2 easily.

