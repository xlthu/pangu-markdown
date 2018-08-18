# Pangu-Markdown 

## Function

1. Add whitespace between Chinese and English
2. Add whitespace between Chinese and `[ ] \` `
3. `, \ . : ; ? !` after Chinese characters to `，、。：；？！`
4. `()` around Chinese characters to `（）`
	- `[] <>` remains untouched
5. Continuous `。`(at least 3) to `......`, e.g. `。。。` to `......`
6. Truncate more than three continuous `？ ！` to only three ones.
7. Truncate continuous `。，；：、“”『』〖〗《》` to only one.

## Usage

```
Ctrl+Shift+P -> Pangu Format
```

Or

Right Click -> Pangu Format

## Setting

| Name                     | Description                                        |
|:-------------------------|:---------------------------------------------------|
| pangu.auto_space_on_save | Auto add whitespace for the whole document on save |

## Thanks

Thanks to [pangu.vim](https://github.com/hotoo/pangu.vim), [writing4cn](https://marketplace.visualstudio.com/items?itemName=twocucao.writing4cn) and [pangu](https://marketplace.visualstudio.com/items?itemName=halfcrazy.pangu).