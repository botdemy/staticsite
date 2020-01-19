# staticsite
### How to download:
##### First Time
```
git clone https://github.com/botdemy/staticsite.git
```
##### Weekly Refresh
```
cd staticsite
git fetch origin
git reset --hard origin/master
```
### How to upload/commit: (admin only)
```
git add -A
git commit -m "weekly update"
git push
```
### How to setup a static site on pythonanywhere
1. In main menu, select Web
2. Add a new web app
3. Select Manual configuration. Select Python 3.7. Next. 
4. Then, on the Web tab configuration screen, scroll down to the Static Files section, and add one new entry:
  * URL: /
  * Path: /home/girlswhocodetv#/staticsite
5. Hit Reload on the web tab
6. Test your site: yourusername.pythonanywhere.com
