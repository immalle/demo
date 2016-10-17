# Linking to line numbers on Github

Sometimes you want to link to a certain line number or a range of lines.

## Link to a single line

Example link:

https://github.com/immalle/demo/blob/5c6ac6437718b5a9c2fd8b1fca157534f8148aa8/test.js#L1

Create a link like this by clicking on the number when viewing the file in Git:

![screenschot](https://cloud.githubusercontent.com/assets/2732197/11383747/a63762b8-930a-11e5-8c75-b819b9a9c60d.png)

This doesn't work the same for `.md`-files (like this `README.md`) because
markdown files are parsed by GitHub into HTML and shown in a different viewer.

To link to a markdown-file you can do 2 things :

- if you want a link like with regular files, you must view the **RAW** Markdown-file 
- if you want to link to a pretty HTML-marked-up version of the markdown-file, you
  have to use an id-parameter in the URL : `#`.

## Link to a range of lines 

Example link :

https://github.com/immalle/demo/blob/86f4c8f19ae680f1572357baa75e39706d38031c/test.js#L2-L6

```
https://github.com/immalle/demo/blob/86f4c8f19ae680f1572357baa75e39706d38031c/test.js#L2-L6
```

Creating a link like this by pressing `SHIFT` while selecting the line numbers.

## Exercise

- Go to the latest version of `test.js` : https://github.com/immalle/demo/blob/master/test.js 
- Select some line numbers (with or without `SHIFT`)
- Don't forget to press `Y` to generate a fixed link
- (Depening on your OS and browser) Press `ALT-D` and `CTRL-C` to copy the link
- Paste it somewhere! (for example in a chatroom or a GitHub issue)
