# Relative links in Github

You can link to other files or directories in your **current repository** using relative links.

You have to use the markdown syntax for links :

```
[Description](Link)
```


## Linking to a file

Markdown code:

```
[A link to test.js](test.js)
```

Try it out:

[A link to test.js](test.js)


## Linking to a directory

Markdown code:

```
[A link to Subdir](Subdir)
```

Try it out:

[A link to Subdir](Subdir)

When visiting a subdirectory in GitHub, by default it will :

- show the files in that directory
- show the parsed `README.md` of that directory


## Linking to a file in a (sub)directory

Links to a file can also be in a sub-directory.

Markdown code:

```
[A link to test.js in Subdir](Subdir/test.js)
```

Try it out:

[A link to test.js in Subdir](Subdir/test.js)


## Linking to a parent directory

You can use `..` as is common in **relative paths** to link to files in a parent
directory.

Try it out by visiting [This file in a subdirectory](Subdir/link_to_parent.md).

## Further reading

https://help.github.com/articles/relative-links-in-readmes/
