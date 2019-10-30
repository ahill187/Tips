## Checkout a Pull Request

```
git fetch origin pull/{PULL_NUMBER}/head:pull_{PULL_NUMBER}
git checkout pull_{PULL_NUMBER}
```
e.g.

```
git fetch origin pull/42/head:pull_42
git checkout pull_42
```

## Checkout a Specific Commit

```
git checkout {ABBREV_COMMIT}
```

e.g.

```
git checkout 9ce920d
```

## Branches

New branch
```
git checkout -b {BRANCH_NAME}
```

Delete branch

```
git branch -D {BRANCH_NAME}
```

Switch branches

```
git checkout {BRANCH_NAME}
```
