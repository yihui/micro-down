# micro-down

JavaScript based Markdown parser with no dependencies.

**<1kB** markdown parser *(gzipped + minified)*

## support:
- Headlines: `### Headline`
- Inline:
    - `*italic*, **bold**, ***bold italic***`
    - \``_code_="- something";`\`
    - `~underline~,~~strike through~~, ~~~deleted~~~`
- Blocks:
    - pre format blocks: surroundent by  \`\`\`
    - div blocks: `""" just a div block """`
    - blockquotes: `> something`
    - class support
- Links: `[Label](destination Title)`
- Images: `![label](source altText))`
- Lists:
    - Unorderd lists using: `+` and `-`
    - Ordered lists using: `1.`
    - Nested Lists
- Tables: `| some | text |`
    - Headerrow: `|- header -|- row -|`
