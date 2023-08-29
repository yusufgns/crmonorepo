# Starter

```sh
git clone https://github.com/yusufgns/crmonorepo.git
```

```sh
yarn install
```

```sh
yarn dev:web
```

# Install a package in a workspace

../crmonorepo
```sh
yarn workspace <workspace> add <package>
```

- Example
```sh
yarn workspace @crmonorepo/nextjs add react-hooks
```

../crmonorepo/**/*
```sh
yarn install <package>
```

-Example
```sh
yarn install tailwindcss
```

# Add Shadcn UI Component
../crmonorepo/packages/ui
```sh
npx shadcn-ui@latest add <component>
```
