# Releasing


## Performing Release
- Start release using the current date as the release version:
```bash
RELEASE_VERSION=YYYY-MM-DD
git flow release start $RELEASE_VERSION
```
- Commit the changes:
```bash
git commit -m "Prepare release $RELEASE_VERSION" .
```
- Finish the release:
```bash
git flow release finish $RELEASE_VERSION
```
- Push changes, develop, master branches and tags to remote repository:
```bash
git push origin develop master --tags
```
