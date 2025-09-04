This is a reproduction to show `defineEmits` isn't typed properly when using auto imports.

The only difference between `AutoImported.vue` and `ImportedFromComponents.vue` is that `AutoImported.vue` relies on auto imports. Running the app with `pnpm dev` shows that `AutoImported.vue` works just fine.

To see the issue run:

```bash
pnpm i && pnpm type-check
```
