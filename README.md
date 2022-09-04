#my-app

From `my_lib`

```
npm link
npm run dev
```

From `my_app`

```
npm link @geometryzen/my-lib
npm run start
```

When done

```
npm unlink @geometryzen/my-lib
```

