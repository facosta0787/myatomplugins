# My Atom Plugins
Simple document with plugins used by me

__Installation__
```
apm install autoclose-html emmet file-icons highlight-selected language-babel platformio-ide-terminal react-snippets
```

__Font__

+ [Fira Code Font](https://github.com/tonsky/FiraCode)

### tips
Change Invisibles Characters, open config.cson file and edit invisibles
```
invisibles:
  cr: ""
  eol: ""
  space: "·"
  tab: "»"
```
Change Invisibles Characters Color, open stylesheet.less file and paste
```
atom-text-editor::shadow {
  .leading-whitespace, .invisible-character {
    color: #999999;
  }
}
```
