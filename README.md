# Viewing the Presentation

I've created the presentation using **obsidian-advanced-slides** specific features.  
You can also view it using **marp**.  
Note that for **marp**, the notes need to be wrapped in HTML comments.  
Additionally, some obsidian-advanced-slides specific features won't work in Marp.

## VS-Code

Install the [marp-team.marp-vscode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) extension.  
Disable [shd101wyy.markdown-preview-enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) or similar extensions if you have it installed, because it blocks marps slide preview.  
There is also a reveal.js to .md slides extension: "[evilz.vscode-reveal](https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal)" but i prefer marp in vs-code because it is much simpler and i use vscode to code and not to write notes.

### MARP

#### Creating Slides

Just add this to the metadata of your markdown file (`markdown.marp.toggleMarpFeature`):

```md
--- 
marp: true
--- 
````

#### Exporting to PDF, HTML, PPTX, PNG or JPEG

1. `CTRL` + `SHIFT` + `P`
2. markdown.marp.export
3. ENTER

## Obsidian

I prefer writing markdown presentations in [obsidian](https://obsidian.md/download), because I have all my notes in obsidian already.

You can use [marp-slides](https://github.com/samuele-cozzi/obsidian-marp-slides) (`obsidian://show-plugin?id=marp-slides`).  
Or a reveal.js to .md slides plugin like [obsidian-advanced-slides](https://github.com/MSzturc/obsidian-advanced-slides) (`obsidian://show-plugin?id=obsidian-advanced-slides`).

### Obsidian Advanced Slides

Show Preview: `CTRL` + `SHIFT` + `E`.