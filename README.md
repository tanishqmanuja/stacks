# Infra

This is my infrastructure as code :)

#### Loading ENV

Must be done to use scripts.

```fish
source env.fish
```

### Using Command

#### Creating a new stack

```fish
compose-stack my-stack
```

#### Updating partial compose files in a stack

1. Calling from inside a stack root directory

```fish
compose-update
```

OR

```fish
compose-update .
```

2. Providing stack dir in first argument

```fish
compose-update docker/core
```
