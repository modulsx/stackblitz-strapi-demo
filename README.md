# 🚀 Stackblitz Strapi Demo (Sqlite)
Demo of strapi running in browser (Experimental)

### Navigate to below link

[Stackblitz Strapi Demo](https://stackblitz.com/~/github.com/suryamodulus/stackblitz-strapi-demo)

### `Build`

```
yarn build
```

### `Start`

```
yarn start
```

## Changes

- Added @webassembly/sqlite3 to package.json
- Added patch to sqlite dialect to disable ```returning```
- Added postinstall script
- Added Seed DB (There is still some issue with DB initalization)
- Removed develop command (It runs successfully, but doesn't work)

## Todos
- Fix DB initalization (Maybe prepared statements are the issue?)
- Fix develop command (Maybe cluster mode or chokidar is the issue?)

