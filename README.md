# How to create file .exe from url

**Library require**  
1`.` dotenv (https://www.npmjs.com/package/dotenv)  
2`.` electron (https://www.npmjs.com/package/electron)

**How to run and build project**  
1`.` npm install  
2`.` npm start  
3`.` run npm install electron-packager --save-dev  
4`.` add "start": "electron ." in "scripts" package.json  
4`.` run npx electron-packager . name_project --platform=win32 --arch=x64 --out=release-builds
