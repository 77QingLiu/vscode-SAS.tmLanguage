# SAS Language Definition for VSCode

 Syntax highlighting for the SAS files in VsCode, with precise syntax match, SAS like theme and code snippets. 
 The syntax highlighting uses tmLanguage files sourced from https://raw.githubusercontent.com/martinring/tmlanguage/master/tmlanguage.json. 


## Features
#### Data Step
![](feature1.jpg)
#### Proc SQL
![](feature2.jpg)
#### Inside Macro
![](feature3.jpg)
#### Statistical Procedure
![](feature4.png)


## Install instructions
* **Install the extension**
  * Search **sas-syntax** in the extension market
  * ![](install.png)
* **Extension settings**

  Firstly, change syntax engine to SAS
  * toggle `CTRL+SHIFT+P` to open the command panel
  * enter `change language mode`
  * select SAS
  ![](setup1.png)

  Secondly, change theme to SAS
  * toggle `CTRL+SHIFT+P` to open the command panel
  * enter `color theme`
  * select SAS
  ![](setup2.png)

## Known Issues
Syntax parse error if there are unmatched `'` or `"` even if being marked by macro mask
![](issue1.jpg)

## For more information

**Enjoy!**
