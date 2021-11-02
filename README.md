# testing--gitpod-url-params-with_colon

When opening URL of a repo where there's a colon in the URL params, it silently breaks Gitpod interface in VSCode:
* Gitpod menu items in main hamburger menu
* Ability to run `code` in terminal
* Ports panel
* etc...

Click on the link below to replicate the bug:
https://gitpod.io/#TESTING_URL_PARAMS_WITH_COLON=:/https://github.com/shaal/testing--gitpod-url-params-with_colon
