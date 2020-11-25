# webpack config | github pages deploy | netlify

- Download Zip
- Exclude dist folder from git ignore
- Create a deploy branch with
`$ git subtree push --prefix dist origin deploy`
- If branch exists for some reason use
`$ git push origin --delete deploy`
and try pushing the deploy branch again
