# Quick markdown guide

Forgot some markdown snippet? checkout.

## Titles

```
# Heading level 1
## Heading level 2          
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```

## Snippets

| Type | Syntax | Output |
|  --- | ------ | ------ |
| Email | `<Your-email>`| <address@example.com> |
| Strikethrough text | `~~Your-strikethrough-text~~` | ~~Some wrong text~~ |
| Italic text | `*Your-italic-text*` | *Italic text* |
| Bold text | `~~your-bold-text~~` | **Bold Text**  |
| Emoji | `:your-emoji:` | :sunglasses: |
| Checkbox | ` - [] checkbox` | <li>[ ] Checkbox</li> |
| Line breaker | ` Hello <br /> world` | Hello <br/> World |
| embedded link| `[Link-title](some-link)` | [Google](https://www.google.com) |
| Image| `![image-name](image-link)` | ![ss](https://github.githubassets.com/images/mona-loading-dark.gif) |
| Image with embedded link| `[![image-title](image-link)](some-link)` | [![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)](https://adobe.com) |

## Styles for descriptions

To highlight some text as below, you have to insert triple backticks and insert diff as identifier.
<br />
eg: ` ```diff  your-text-here``` `

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
Default text
```

###### Dropdown

<details>
  <summary>Dropdown Title</summary>
 
  <blockquote>Dropdown Content</blockquote>
</details>

## Table 

|  First title  |  Second title  |
| ------------- | -------------- |
|  Some content | Some content   |
|  Some content | Some content   |

## Lists

- #### Numerical list

1. One
2. Two
3. Three

- #### Default list

* One
* Two
* Three

- #### Nested list

> This the first paragraph. 
>> This is the nested paragraph. 
>>> And this is other nested paragraph.

##  Highlighting code blocks 

To highlight some code block, you have to insert triple backticks and the language you want as identifier.
<br />
eg: ` ```js  your-code-here``` `

```js
function test() {
  console.log("Hello world :)");
}
```

## Useful shares

[Emoji list](https://github.com/ikatyang/emoji-cheat-sheet)
<br />
[Badges list](https://github.com/Maark007/markdown-badges)
