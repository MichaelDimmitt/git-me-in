# git-me-in
A config switcher that lets you push repos, but changes you back to default config after push.

> fun fact, not that I am advocating for this but it is possible:
```
you "could" use your "default" config to add a bunch of commits to a project that requires a different config;
and then go to push and it will fail because you do not have right credentials required by the repo.
and then you could swap the credentials to push to the repo.
and then swap back to your "default" credentials
```

# Pain Point
1. Working on open source while working at a company, I have noticed my config was still set to the company config. 

# Features
1. push switching (always uses your default, on push, if fails will cycle configs, if succeeds changes back to default.
2. responsible easy switching (basically this will be a config manager..., primary, secondary, tertiary, etc.ranary)
3. accept flags that provide different experiences: responsible easy switching, push switching.

# About the name
repo name is "git-me-in"<br/>
it is like get me in but uses git 😅
