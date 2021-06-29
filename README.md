# Vue Testing Library Type Issue

See the github actions for the failure:

```
 14:25:57  /tmp/test-vtl  tsc index.ts
node_modules/@testing-library/vue/types/index.d.ts:50:11 - error TS1005: ',' expected.

50   localVue: typeof Vue,
             ~

node_modules/@testing-library/vue/types/index.d.ts:52:8 - error TS1005: ',' expected.

52   store: Store<any>,
          ~

node_modules/@testing-library/vue/types/index.d.ts:53:9 - error TS1005: ',' expected.

53   router: Router,
           ~

Found 3 errors.
```
