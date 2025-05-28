# renovate-config

renovate config file

## validate

https://docs.renovatebot.com/config-validation/

```sh
npm run validate
```

```sh
export LOG_LEVEL=debug
export RENOVATE_CONFIG_FILE="./default.json"
export RENOVATE_TOKEN=<GITHUB_PAT_TOKEN>
npx renovate \
  --dry-run \
  --schedule= \
  --require-config=ignored \
  tak458/todo-app
```

## modify config

https://docs.renovatebot.com/config-validation/#validation-of-renovate-config-change-prs

```sh
git switch -c renovate/reconfigure
# なにかしら編集
git push origin
```
