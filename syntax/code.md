# Les blocs de code
# Code Blocks

Les blocs de codes pré-formatés sont utlisés pour écrire sur la programmation ou surligner un code source. Plus que de simple pragraphe, les lignes de code d'un bloc de code sont litterallement interprétées.
Pre-formatted code blocks are used for writing about programming or markup source code. Rather than forming normal paragraphs, the lines of a code block are interpreted literally.

Voici un exemple :
Here is an example:

```
Ceci est un bloc de code 
This is a code block
```

Afin de créer un bloc de code en Markdown, il suffit d'identer chaque ligne du bloc avec au moins 4 espaces ou une tabulation.
To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

Par exemple :
For example:

```
Ceci est un paragraphe normal:
This is a normal paragraph:

    This is a code block.
    Ceci est un bloc de code. 
```

You can also create code block separated by:
Vous pouvez également créer un bloc de code separé avec:

    ```

### Inline code blocks
### Bloc de code en ligne

Inline code blocks can be written using: `
Les blocs de code en ligne peuvent être écrit en utilisant: `

For example:
Par exemple:
    This is a `inline code block`
    Ceci est `un bloc de code en ligne`

### Syntax highlighting
### La syntaxe de mise en avant 

You can define the language to be used for syntax highlighting by adding the name on the opening tag. Example:
Vous pouvez definir le langage utlisé pour mettre en évidence la syntaxe en ajoutant un nom sur un mot clé ouvrant. Exemple : 

    ```js
    var a = {};
    ```