# larafonts
Font repo for lara

## make your own repo:
1. Fork this repo
2. Delete the old fonts
3. Patch your fonts using `fontpatch.py` (from this repo)
4. Add your own fonts into the fonts directory
5. Modify fonts.json and replace these values:
  ```json
  "repo_name": "YOUR REPO NAME",
  "repo_author": "YOUR NAME",
  "repo_icon": "LINK TO YOUR REPOS ICON",
  ```
6. Delete current font entries from fonts.json
7. For every custom font you added, create an entry like this in the fonts array:
```json
{
  "name": "FONT NAME",
  "url": "eg. https://linktoyourfont.com/fonts/yourfont.ttf",
  "format": "truetype" 
},
```
8. Profit!
