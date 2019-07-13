# Visual Studio Code profiles

## Instructions

* Clone this repo
* Make sure you've already set up [VSCode to launch from the command line](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line)
* Open Visual Studio Code using a profile
  ``` bash
    # replace {PATH_TO_REPO} with the path to this repo {CODE_PROFILE_NAME} with the profile (home_profile)
    code --user-data-dir {PATH_TO_REPO}/profiles/home/{CODE_PROFILE_NAME}/data
  ```
* Create an alias for your profile (for example in you .bash_profile)
  ``` bash
  alias codeHome="code --user-data-dir {PATH_TO_REPO}/profiles/home/{CODE_PROFILE_NAME}/data"
  ```

## Acknowledgements
Inspired on: https://dev.to/jsjoeio/how-to-create-code-profiles-in-vscode-3ofo
