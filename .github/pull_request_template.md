
## Describe your changes

Added a row click feature to the Maintenance table, following the same pattern used in the Uptime Monitoring page. This lets the user navigate to the maintenance edit page of that specific maintenance window.
<video controls src="screen-recording.mp4" title="Title"></video>
## Write your issue number after "Fixes "

Fixes #2512 

## Please ensure all items are checked off before requesting a review. "Checked off" means you need to add an "x" character between brackets so they turn into checkmarks.

- [x] (Do not skip this or your PR will be closed) I deployed the application locally.
- [x] (Do not skip this or your PR will be closed) I have performed a self-review and testing of my code.
- [x] I have included the issue # in the PR.
- [ ] I have added i18n support to visible strings (instead of `<div>Add</div>`, use): 
```Javascript
const { t } = useTranslation();
<div>{t('add')}</div>
```
- [x] I have **not** included any files that are not related to my pull request, including package-lock and package-json if dependencies have not changed
- [x] I didn't use any hardcoded values (otherwise it will not scale, and will make it difficult to maintain consistency across the application).
- [x] I made sure font sizes, color choices etc are all referenced from the theme. I don't have any hardcoded dimensions.
- [x] My PR is granular and targeted to one specific feature.
- [x] I ran `npm run format` in server and client directories, which automatically formats your code.
- [x] I took a screenshot or a video and attached to this PR if there is a UI change.

