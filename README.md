# Bash Cheatsheet

## Use Shellchek

See https://github.com/koalaman/shellcheck/

## Remove prefix/suffix from string

```bash
echo "{$var#*/}" # remove prefix starting with '/'
echo "{$var%/*}" # remove suffix ending with '/'
```

## No-op

```bash
# Use ':' for no-op
echo "$var" | grep "some-value" || :
```
