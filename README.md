
## Folder Structure

> Assets - contains images, fonts, icons

```
    /assets
      /img
        bg.png
      /fonts
        Arial.woff
      /icons
        avatar.svg
```

> Component - contains components (with local constants, typings) that are shared over several scenes;

```
   /components
      /Spinner
        Spinner.tsx
        Spinner.test.tsx
        constants.ts
        index.ts
      /Modal
```

> Constants - contains constants that are shared over several scenes, components, services...

```
    /constants
      colors.ts
      routes.ts
```

> Scenes - contains all files according to screen - components, constants, typings, reducers, actions, etc.

```
    /scenes
      /Home
        /components
          /Header
          /Footer
        actions.ts
        Home.tsx
        reducer.ts
        constatns.ts
        index.ts
      /Auth
      /User
```

> Services - contains application services: api classes, helper functions, redux

```

    /services
      /api
        auth-api.ts
      /helpers
        time-slots.ts
      /redux
        middleware.ts
        store.ts
```

> Typings - containts shared typings

```
    /typings
      api.ts
      items.ts
```

> `index.ts` file serves as an export point. We should import files only from it.