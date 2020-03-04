# Library files

Most suggested gitignore files entirely exclude unity's /Library/ folder, since it gets re-created as needed. However, I've discovered the Build Settings and scene settings to be stored within several files in the Library/.

By preserving the following files, we can set build target and other settings into a project from the start, allowing the developer to "Fork, build and deploy"

1. BuildSettings.asset
2. EditorOnlyScriptingUserSettings.json
3. EditorUserBuildSettings.asset
4. EditorUserSettings.asset
5. LastSceneManagerSetup.txt
6. ProjectSettings.asset


## ProjectSettings.asset
This file is stored in repo WITHOUT a value for ProductName. This allows a forked version of this project to "auto-fill" with the forked repo name
