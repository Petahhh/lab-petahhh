# Editor Powers

Let's open up a sample markdown file:
```editor:open-file
file: ~/exercises/01-sample-content.md
```

"Turn to page 394"

"But we still haven't covered.."

"PAGE 394!" I mean, line 71!
```editor:open-file
file: ~/exercises/01-sample-content.md
line: 71
```

Highlight the word click

```editor:select-matching-text
file: ~/exercises/01-sample-content.md
text: "Click"
```

Highlight a word between the lines 12 and 15

```editor:select-matching-text
file: ~/exercises/01-sample-content.md
text: "Click"
before: 15
after: 12
```

Lets highlight a match for an entire line
```editor:select-matching-text
file: ~/exercises/01-sample-content.md
text: "#### Click text to copy"
before: 0
after: 0
```

