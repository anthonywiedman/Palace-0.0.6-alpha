# Palace-0.0.6-alpha
Visual chat app built with electron

## Building

First you will want to install [Node](https://nodejs.org/en/)

You will then want to download or `git clone` Palace's source

Navigate to the Palace folder in your terminal and type the following command to install all of the projects dependancies
```
npm install
```
If you're on Windows installing spellchecker may require that windows-build-tools is installed.

Installing this requires a PowerShell with administrative rights. (right-click on Powershell and run "as Administrator").
```
npm install --global windows-build-tools
```

### Finally
```
npm start
```
or
```
npm run build
```

For windows before running npm start, run :
```
npm run rebuild-win32
```
