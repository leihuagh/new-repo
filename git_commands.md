# Git Commands

## git status

```
git status
```

## Example

- Create a file called `exmaple.md`
- Check the status
- It is will be in red, which means the file `example.md` is not added to the stage yet
- Add to the stage

```
git add .\example.md
git status
```

- The file `example.md` will become green, which means it is on the state

## Finding the Different Between the Commits

- The command is `git diff`

```
git diff
```

## Check Stagged Difference

```
git add .
git diff --cached
```

## git log

```
git log
git log --grap
```

