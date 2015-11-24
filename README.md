# demo
Demo'ing git and github features...

## Linking to line numbers on Github

Example link:

https://github.com/immalle/demo/blob/5c6ac6437718b5a9c2fd8b1fca157534f8148aa8/test.js#L1

Create a link like this by clicking on the number when viewing the file in Git:

![screenschot](https://cloud.githubusercontent.com/assets/2732197/11383747/a63762b8-930a-11e5-8c75-b819b9a9c60d.png)

This doesn't work for `.md`-files (like this `README.md`) because they have a different viewer (which parses the Markdown-code).

## Linking to files on Github in general

[This](https://github.com/immalle/demo/blob/master/test.js) is a bad link, because `master` can change.

![screenshot-master-branch](https://cloud.githubusercontent.com/assets/2732197/11383906/c5bb7d30-930b-11e5-866c-c61fb00af369.png)

By pressing `Y` in GitHub (Yes, that's right, just on the website) it changes to current commit, **including the URL**:

![screenshot-specific-commit](https://cloud.githubusercontent.com/assets/2732197/11383906/c5bb7d30-930b-11e5-866c-c61fb00af369.png)

This is a much safer way to link, especially when using line numbers. The `master`-branch will always point to the latest version and can change enormously!
