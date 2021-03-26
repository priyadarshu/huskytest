```
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is up to date with 'origin/86-final-react-setup'.

Changes not staged for commit:
        modified:   .husky/pre-commit
        modified:   client/.eslintrc.js
        deleted:    lint-staged.config.js

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Changes have been made"
[86-final-react-setup b1e2b35] Changes have been made
 4 files changed, 19 insertions(+), 12 deletions(-)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> husky --version
5.2.0
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> cd client 

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> eslint --init
Cannot find local ESLint!
Please install ESLint by `npm install eslint --save-dev`.


added 2044 packages, and audited 2045 packages in 13m

found 0 vulnerabilities
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> git add .
[86-final-react-setup 4370fda] Added eslint and prettier
 1 file changed, 20677 insertions(+), 24 deletions(-)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> git add .
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> git commit -m "Added nodemodules in root folder"   
On branch 86-final-react-setup

nothing to commit, working tree clean
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 2 commits.

On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> git commit -m "Checking husky#1"
[86-final-react-setup 1b228de] Checking husky#1
 1 file changed, 1 insertion(+)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> npm install husky
^CTerminate batch job (Y/N)? y
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> cd ..
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
nothing to commit, working tree clean
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> cd client 
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> eslint --init

ESLint: 7.22.0


PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> eslint --version
v7.22.0
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> prettier --version
2.2.1
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client> cd ..
husky - updated package.json
husky - Git hooks installed
husky - created .husky\pre-commit
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> husky install
husky - Git hooks installed
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git add .    
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   package.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


added 29 packages, removed 1888 packages, changed 19 packages, and audited 186 packages in 3m

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit

ℹ No staged files match any configured task.
ℹ No staged files match any configured task.

> client@0.1.0 precommit
> eslint src/**/*.js


Oops! Something went wrong! :(

ESLint: 7.22.0

Error: ESLint configuration in .eslintrc.js is invalid:
        - Unexpected top-level property "main".

    at ConfigValidator.validateConfigSchema (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\@eslint\eslintrc\lib\shared\config-validator.js:271:19)
    at ConfigArrayFactory._normalizeConfigData (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\@eslint\eslintrc\lib\config-array-factory.js:644:19)
    at ConfigArrayFactory.loadInDirectory (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\@eslint\eslintrc\lib\config-array-factory.js:512:33)
    at CascadingConfigArrayFactory._loadConfigInAncestors (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\@eslint\eslintrc\lib\cascading-config-array-factory.js:379:46)
    at CascadingConfigArrayFactory._loadConfigInAncestors (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\@eslint\eslintrc\lib\cascading-config-array-factory.js:398:20)
    at CascadingConfigArrayFactory.getConfigArrayForFile (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\@eslint\eslintrc\lib\cascading-config-array-factory.js:300:18)
    at FileEnumerator._iterateFilesRecursive (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\eslint\lib\cli-engine\file-enumerator.js:481:49)
    at _iterateFilesRecursive.next (<anonymous>)
    at FileEnumerator.iterateFiles (C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\node_modules\eslint\lib\cli-engine\file-enumerator.js:296:49)
npm ERR! code 2
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c eslint src/**/*.js

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_24_37_226Z-debug.log
npm ERR! code 2
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c lint-staged && cd client && lint-staged && npm run precommit

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_24_37_411Z-debug.log
husky - pre-commit hook exited with code 2 (error)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


up to date, audited 186 packages in 4s

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit

ℹ No staged files match any configured task.
ℹ No staged files match any configured task.

> client@0.1.0 precommit
> eslint src/**/*.js


Oops! Something went wrong! :(

ESLint: 7.22.0

ESLint couldn't find the plugin "eslint-plugin-react".

(The package "eslint-plugin-react" was not found when loaded as a Node module from the directory "C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client".)

It's likely that the plugin isn't installed correctly. Try reinstalling by running the following:

    npm install eslint-plugin-react@latest --save-dev

The plugin "eslint-plugin-react" was referenced from the config file in ".eslintrc.js".

If you still can't figure out the problem, please stop by https://eslint.org/chat/help to chat with the team.
npm ERR! code 2
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c eslint src/**/*.js

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_26_59_892Z-debug.log
npm ERR! code 2
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c lint-staged && cd client && lint-staged && npm run precommit

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_27_00_024Z-debug.log
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   client/.eslintrc.js
        modified:   package-lock.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> npm install eslint-plugin-react@latest --save-dev

added 44 packages, and audited 230 packages in 26s

30 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   package.json

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   package-lock.json
        modified:   package.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git add .
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   client/.eslintrc.js
        modified:   package-lock.json
        modified:   package.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky#1"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


up to date, audited 230 packages in 3s

30 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit

[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...
[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...

> client@0.1.0 precommit
> eslint src/**/*.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configuration .

C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client\src\components\Bootstrap\Header.js
  4:10  error  Redundant double negation  no-extra-boolean-cast

C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client\src\reportWebVitals.js
  3:12  error  Strings must use doublequote  quotes

C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client\src\setupTests.js
  5:8  error  Strings must use doublequote  quotes

✖ 3 problems (3 errors, 0 warnings)
  3 errors and 0 warnings potentially fixable with the `--fix` option.
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c eslint src/**/*.js

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_29_29_651Z-debug.log
npm ERR! code 1
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c lint-staged && cd client && lint-staged && npm run precommit

npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_29_29_891Z-debug.log
husky - pre-commit hook exited with code 1 (error)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git add .
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   client/.eslintrc.js
        modified:   client/src/components/Bootstrap/Header.js
        modified:   package-lock.json
        modified:   package.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky#2"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


up to date, audited 230 packages in 5s

30 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit

[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...
[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...

> client@0.1.0 precommit
> eslint src/**/*.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configuration .

C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client\src\reportWebVitals.js
  3:12  error  Strings must use doublequote  quotes

C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client\src\setupTests.js
  5:8  error  Strings must use doublequote  quotes

✖ 2 problems (2 errors, 0 warnings)
  2 errors and 0 warnings potentially fixable with the `--fix` option.
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c eslint src/**/*.js

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_33_32_078Z-debug.log
npm ERR! code 1
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c lint-staged && cd client && lint-staged && npm run precommit

npm ERR! A complete log of this run can be found in:
husky - pre-commit hook exited with code 1 (error)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git add .
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   client/.eslintrc.js
        modified:   client/src/components/Bootstrap/Header.js
        modified:   client/src/reportWebVitals.js
        modified:   package-lock.json
        modified:   package.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky#3"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


up to date, audited 230 packages in 5s

30 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit && npm run lint:fix

[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...
[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...

> client@0.1.0 precommit
> eslint src/**/*.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configuration .

C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd\client\src\setupTests.js
  5:8  error  Strings must use doublequote  quotes

✖ 1 problem (1 error, 0 warnings)
  1 error and 0 warnings potentially fixable with the `--fix` option.

npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c eslint src/**/*.js

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_37_45_318Z-debug.log
npm ERR! code 1
npm ERR! path C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c lint-staged && cd client && lint-staged && npm run precommit && npm run lint:fix

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Priyadarshini\AppData\Local\npm-cache\_logs\2021-03-26T16_37_45_457Z-debug.log
husky - pre-commit hook exited with code 1 (error)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git add .
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky#4"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


up to date, audited 230 packages in 6s

30 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit && npm run lint:fix

[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...
[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...
> client@0.1.0 precommit
> eslint --fix src/**/**.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configuration .

> client@0.1.0 lint:fix
> eslint --fix src/**/*.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configurat[86-final-react-setup 6b720ca] Checking husky#4
 6 files changed, 3001 insertions(+), 44 deletions(-)
 rewrite client/.eslintrc.js (95%)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 4 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git restore <file>..." to discard changes in working directory)
        modified:   client/src/setupTests.js

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git add .
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 4 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   client/src/setupTests.js
        modified:   package.json

PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git commit -m "Checking husky#5"
Running Husky --

> internship-lms-frontend@1.0.0 prepare
> husky install

husky - Git hooks installed
HUSKY INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 lintstaged_install
> npm i -D lint-staged


up to date, audited 230 packages in 3s

30 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
LINT STAGED INSTALLED SUCCESSFULLY

> internship-lms-frontend@1.0.0 precommit
> lint-staged && cd client && lint-staged && npm run precommit && npm run lint:fix && git add .

[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...
[SUCCESS] Cleaning up...
[STARTED] Preparing...
[SUCCESS] Preparing...
[STARTED] Running tasks...
[STARTED] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[STARTED] prettier --write
[SUCCESS] prettier --write
[SUCCESS] Running tasks for **/*.+(js|css|sass|less|scss|jsx)
[SUCCESS] Running tasks...
[STARTED] Applying modifications...
[SUCCESS] Applying modifications...
[STARTED] Cleaning up...

> client@0.1.0 precommit
> eslint --fix src/**/**.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configuration .

> client@0.1.0 lint:fix
> eslint --fix src/**/*.js

Warning: React version not specified in eslint-plugin-react settings. See https://github.com/yannickcr/eslint-plugin-react#configuration .
PRECOMMIT HOOK RAN SUCCESSFULLY
[86-final-react-setup fcf75a9] Checking husky#5
 2 files changed, 2 insertions(+), 2 deletions(-)
PS C:\Users\Priyadarshini\Desktop\MyApps\finalOSP\Internship-LMS-FrontEnd> git status
On branch 86-final-react-setup
Your branch is ahead of 'origin/86-final-react-setup' by 5 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

```
