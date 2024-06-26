# What is this?

This is the text of Wicked Ones, a Forged in the Dark tabletop roleplaying game by Ben Nielson.

The markdown was created by Adam Kleizer based on the PDF rendition of the book.

# License

The book was released to the public domain under the CC0 1.0 license.

You can go to [https://creativecommons.org/publicdomain/zero/1.0/] to view the license.

# Markdown specifics

- Comments are added to the markdown with the following notation:
  
  `[comment]: # (free text)`

- Textboxes and styled paragraphs from the book are added using blockquotes, the purpose of the styling (as conceived by the markdown creator) is marked with the following notation:
  
  `[context]: # (purpose)`
  
  These contexts are directly preceding the blockquotes affected. The blockquotes that are in a single enclosure semantically (and visually in the book) and thus affected by the notation are following each other without empty lines in-between.
  
  Blockquotes without a context are indeed quotes in the book, without any further distinction in meaning.
  
  The following is a list of possible contexts to be found throughout the book:
  - `[context]: # (chances)`
  - `[context]: # (complete list)`
  - `[context]: # (example of play)`
  - `[context]: # (important rule)`
  - `[context]: # (list of examples)`
  - `[context]: # (roll summary)`
  - `[context]: # (summarizing subtitle)`
  - `[context]: # (table footnote)`
  - `[context]: # (tips)`

- Roll results are displayed with the following convention:

  `[rollresult]: "Result title{attribute1:value1,attribute2:value2}"`  
  `> (3d6) = 1, 2, 3`  
  `>`  
  `> **Outcome**`

  *Source:*

  `[rollresult]: # "Failure{dice-color:gray}"`  
  `> (3d6) = 1, 2, 3`  
  `>`  
  `> **Failure**`
  
  *Output:*

  [rollresult]: # "Failure{dice-color:gray}"
  > (3d6) = 1, 2, 3
  >
  > **Failure**

- Clocks are represented by circles in the book as is customary in Forged in the Dark games. We can't add circles here, so we use tables. We add a header to the table and mark it with the clock's name and attributes as metadata. We wrap the table in a blockquote so the metadata is correctly hidden on github.

  *Source:*

  `#### Fences & Dogs`  
  ` `  
  `[clock]: # "Fences & Dogs"`  
  `>|1|2|3|4|`  
  `>|-|-|-|-|`  
  `>|x|o|o|o|`
  
  *Output:*
  #### Fences & Dogs
  
  [clock]: # "Fences & Dogs"
  > |1|2|3|4|
  > |-|-|-|-|
  > |x|o|o|o|


