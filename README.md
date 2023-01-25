# Heroku Review App GitHub Action

GitHub Action that creates a Heroku review app and deploys to it

This repository was forked from https://github.com/pmbanugo/heroku-review-app-actions and full documentation for its use can be found there.  Please consider [sponsoring](https://github.com/sponsors/pmbanugo) the original author.

## Example usage

```yaml
uses: ynab/heroku-review-app-action@v1
id: deploy
with:
 api-key: ${{ secrets.HEROKU_API_KEY }}
 pipeline-id: ${{ secrets.PIPELINE_ID }}
 app-name-prefix: my-app-name-prefix
 region: us
 team: my-team-name
```