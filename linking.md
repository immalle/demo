# Linking to files on Github in general

https://github.com/immalle/demo/blob/master/test.js is a bad link, because
`master` can change : the link will always point to the latest version of
`test.js`.

![screenshot-master-branch](https://cloud.githubusercontent.com/assets/2732197/11383906/c5bb7d30-930b-11e5-866c-c61fb00af369.png)

By pressing `Y` in GitHub (yes, that's right, just on the website) it changes
the URL to the commit **you are currently viewing** :

![screenshot-specific-commit](https://cloud.githubusercontent.com/assets/2732197/11383924/e0c88e06-930b-11e5-9f19-221a567126a7.png)

This is a much safer way to link since the `master`-branch will always point to
the latest version!

> This link points to the first version of `test.js` in this repository: https://github.com/immalle/demo/blob/5c6ac6437718b5a9c2fd8b1fca157534f8148aa8/test.js
