# SKO-Assets
SKO Assets to be served static on website

# Digital Ocean build commands to move from assets to SKO site
npm run build

curl https://dev.stickknightsonline.com/assets/version.txt > build/version.txt

curl https://dev.stickknightsonline.com/assets/launcher-version.txt > build/launcher-version.txt

curl https://dev.stickknightsonline.com/assets/patch_windows.zip > build/patch_windows.zip

