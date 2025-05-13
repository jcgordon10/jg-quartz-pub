# Quartz v4

helper function to [sync](https://quartz.jzhao.xyz/setting-up-your-GitHub-repository) the repo to Github
```bash
npx quartz sync --help
```

I would use this one to sync the content since I have the vault somewhere other than `content`. though it doesn't copy the content, so I'm not sure what the use of the `--directory` flag is.
```bash
npx quartz sync --directory ../jg-obsidian-pub
```


npx quartz build --serve --directory ../jg-obsidian-pub