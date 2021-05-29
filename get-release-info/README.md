Submodule - gets info for current release (todo - is it needed?)

no

```pcode
if github.event_name == 'release' {
  return github.event.release.upload_url
}
```

you get upload\_url this way
