# Example links

This link points to the latest version of `test.js` in the `master`-branch:
https://github.com/immalle/demo/blob/master/test.js

This link points to the first version of `test.js` in this repository: https://github.com/immalle/demo/blob/5c6ac6437718b5a9c2fd8b1fca157534f8148aa8/test.js

# Linking to files on Github in general

## Default method

https://github.com/immalle/demo/blob/master/test.js is a bad link, because
`master` can change : the link will always point to the latest version of
`test.js`.

When viewing `test.js`, GitHub shows which version you are viewing:

![screenshot-master-branch](https://cloud.githubusercontent.com/assets/2732197/11383906/c5bb7d30-930b-11e5-866c-c61fb00af369.png)

## Smarter method

By pressing `Y` in GitHub (yes, that's right, just on the website) it changes
the URL to the commit **you are currently viewing** :

**The URL in the browser bar will change!**

GitHub will show the specific **tree-hash** of `test.js` :

![screenshot-specific-commit](https://cloud.githubusercontent.com/assets/2732197/11383924/e0c88e06-930b-11e5-9f19-221a567126a7.png)

This is a much safer way to link since the `master`-branch will always point to
the latest version!

# Further reading

- https://help.github.com/articles/using-keyboard-shortcuts/ : GitHub supports many shortcuts!
- https://git-scm.com/book/en/v2/Git-Internals-Git-Objects : Tree hashes represent tree-objects in git. A tree-object is very similar to a subdirectory in a filesystem.
