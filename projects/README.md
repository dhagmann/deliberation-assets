Each topic represents a single prompt or question/answer block.

Topics are defined with the following syntax:

```markdown
---
name: example/multipleChoice.md
type: multipleChoice
author: James Houghton
modified: Oct 19, 2022
---

# Markdown or HTML?

We need to decide whether to use Markdown or HTML for storing
[deliberation](https://www.annualreviews.org/doi/abs/10.1146/annurev.polisci.11.081306.070308) topics.

- **Markdown** files are a convenient way to include basic formatting in a human-readable plain text document that can be easily version controlled.
- **HTML** documents allow for more customization, but are more difficult to write and to read without a renderer.

_Which format is better for this task?_

---

- Markdown
- HTML
```

The first block is a metadata block using YAML syntax, encased in `---` dashes. It can contain anything you want to document about the prompt that will not be displayed, but should contain at least a `type` element. Currently supported types are `noResponse`, `multipleChoice`, and `openResponse`, but we'll work on `livePoll` and `checkboxes` and possibly some others.

The next block is markdown to render as the topic prompt.

The last block gives options for the responses, or default text for an open response box.
