Expandable-blocks spike probe record — every form, each under its own heading. Every block's summary starts `Probe <id>:` and every body ends with the line `End of probe <id>.`, so each block can be found again whether it renders collapsed or as literal text. Probes 01–06 vary the summary over a paragraph body; probes 07–13 vary the body under a plain summary.

## Form A: authored

the authored form: `<details>`, one-line `<summary>`, blank line, body, blank line, `</details>`.

**What you should see:** Collapsed on load, summary visible, every body variant rendered once expanded.

<details>
<summary>Probe A01: Plain summary text</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A01.

End of probe A01.

</details>

<details>
<summary>Probe A02: Entities &amp; &lt;tag&gt; in a summary</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A02.

End of probe A02.

</details>

<details>
<summary>Probe A03: Inline code `copy --dry-run` in backticks</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A03.

End of probe A03.

</details>

<details>
<summary>Probe A04: Inline code <code>copy --dry-run</code> as HTML</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A04.

End of probe A04.

</details>

<details>
<summary>Probe A05: **Bold** text in a summary</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A05.

End of probe A05.

</details>

<details>
<summary>Probe A06: <strong>Bold</strong> as HTML</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A06.

End of probe A06.

</details>

<details>
<summary>Probe A07: Body — paragraph</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe A07.

End of probe A07.

</details>

<details>
<summary>Probe A08: Body — lists</summary>

- First bullet
- Second bullet

1. First step
2. Second step

End of probe A08.

</details>

<details>
<summary>Probe A09: Body — headings</summary>

### A third-level heading in probe A09

Text under the third-level heading.

#### A fourth-level heading in probe A09

Text under the fourth-level heading.

End of probe A09.

</details>

<details>
<summary>Probe A10: Body — fenced code</summary>

```python
def probe():
    return "A10"
```

End of probe A10.

</details>

<details>
<summary>Probe A11: Body — image</summary>

![Probe image in A11](./probe-image.png)

End of probe A11.

</details>

<details>
<summary>Probe A12: Body — table</summary>

| Column | Value |
| --- | --- |
| form | authored |
| probe | A12 |

End of probe A12.

</details>

<details>
<summary>Probe A13: Body — nested</summary>

<details>
<summary>Probe A13i: nested inner summary</summary>

Nested body of probe A13.

</details>

End of probe A13.

</details>

## Form T: no-blank-after-summary

the authored form without the blank line after `</summary>`.

**What you should see:** Collapsed on load, but the body's first Markdown construct may show as literal text.

<details>
<summary>Probe T01: Plain summary text</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T01.

End of probe T01.

</details>

<details>
<summary>Probe T02: Entities &amp; &lt;tag&gt; in a summary</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T02.

End of probe T02.

</details>

<details>
<summary>Probe T03: Inline code `copy --dry-run` in backticks</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T03.

End of probe T03.

</details>

<details>
<summary>Probe T04: Inline code <code>copy --dry-run</code> as HTML</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T04.

End of probe T04.

</details>

<details>
<summary>Probe T05: **Bold** text in a summary</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T05.

End of probe T05.

</details>

<details>
<summary>Probe T06: <strong>Bold</strong> as HTML</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T06.

End of probe T06.

</details>

<details>
<summary>Probe T07: Body — paragraph</summary>
A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe T07.

End of probe T07.

</details>

<details>
<summary>Probe T08: Body — lists</summary>
- First bullet
- Second bullet

1. First step
2. Second step

End of probe T08.

</details>

<details>
<summary>Probe T09: Body — headings</summary>
### A third-level heading in probe T09

Text under the third-level heading.

#### A fourth-level heading in probe T09

Text under the fourth-level heading.

End of probe T09.

</details>

<details>
<summary>Probe T10: Body — fenced code</summary>
```python
def probe():
    return "T10"
```

End of probe T10.

</details>

<details>
<summary>Probe T11: Body — image</summary>
![Probe image in T11](./probe-image.png)

End of probe T11.

</details>

<details>
<summary>Probe T12: Body — table</summary>
| Column | Value |
| --- | --- |
| form | no-blank-after-summary |
| probe | T12 |

End of probe T12.

</details>

<details>
<summary>Probe T13: Body — nested</summary>
<details>
<summary>Probe T13i: nested inner summary</summary>
Nested body of probe T13.

</details>

End of probe T13.

</details>

## Form P: linear-plus

Linear's documented collapsible form: `+++ <summary>`, the body, `+++`.

**What you should see:** Literal `+++` lines on GitHub and in a local preview; a collapsible section in Linear.

+++ Probe P01: Plain summary text

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P01.

End of probe P01.

+++

+++ Probe P02: Entities &amp; &lt;tag&gt; in a summary

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P02.

End of probe P02.

+++

+++ Probe P03: Inline code `copy --dry-run` in backticks

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P03.

End of probe P03.

+++

+++ Probe P04: Inline code <code>copy --dry-run</code> as HTML

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P04.

End of probe P04.

+++

+++ Probe P05: **Bold** text in a summary

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P05.

End of probe P05.

+++

+++ Probe P06: <strong>Bold</strong> as HTML

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P06.

End of probe P06.

+++

+++ Probe P07: Body — paragraph

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe P07.

End of probe P07.

+++

+++ Probe P08: Body — lists

- First bullet
- Second bullet

1. First step
2. Second step

End of probe P08.

+++

+++ Probe P09: Body — headings

### A third-level heading in probe P09

Text under the third-level heading.

#### A fourth-level heading in probe P09

Text under the fourth-level heading.

End of probe P09.

+++

+++ Probe P10: Body — fenced code

```python
def probe():
    return "P10"
```

End of probe P10.

+++

+++ Probe P11: Body — image

![Probe image in P11](./probe-image.png)

End of probe P11.

+++

+++ Probe P12: Body — table

| Column | Value |
| --- | --- |
| form | linear-plus |
| probe | P12 |

End of probe P12.

+++

+++ Probe P13: Body — nested

+++ Probe P13i: nested inner summary

Nested body of probe P13.

+++

End of probe P13.

+++

## Form R: linear-arrow

Linear's editor shortcut `>>> <summary>`, the body, `>>>`.

**What you should see:** Literal `>>>` (a blockquote) on GitHub and in a local preview; Linear may read it as a collapsible section.

>>> Probe R01: Plain summary text

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R01.

End of probe R01.

>>>

>>> Probe R02: Entities &amp; &lt;tag&gt; in a summary

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R02.

End of probe R02.

>>>

>>> Probe R03: Inline code `copy --dry-run` in backticks

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R03.

End of probe R03.

>>>

>>> Probe R04: Inline code <code>copy --dry-run</code> as HTML

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R04.

End of probe R04.

>>>

>>> Probe R05: **Bold** text in a summary

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R05.

End of probe R05.

>>>

>>> Probe R06: <strong>Bold</strong> as HTML

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R06.

End of probe R06.

>>>

>>> Probe R07: Body — paragraph

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe R07.

End of probe R07.

>>>

>>> Probe R08: Body — lists

- First bullet
- Second bullet

1. First step
2. Second step

End of probe R08.

>>>

>>> Probe R09: Body — headings

### A third-level heading in probe R09

Text under the third-level heading.

#### A fourth-level heading in probe R09

Text under the fourth-level heading.

End of probe R09.

>>>

>>> Probe R10: Body — fenced code

```python
def probe():
    return "R10"
```

End of probe R10.

>>>

>>> Probe R11: Body — image

![Probe image in R11](./probe-image.png)

End of probe R11.

>>>

>>> Probe R12: Body — table

| Column | Value |
| --- | --- |
| form | linear-arrow |
| probe | R12 |

End of probe R12.

>>>

>>> Probe R13: Body — nested

>>> Probe R13i: nested inner summary

Nested body of probe R13.

>>>

End of probe R13.

>>>

## Form O: details-open

`<details open>`: the authored form with the `open` attribute.

**What you should see:** Expanded on load (not collapsed), summary visible, body rendered.

<details open>
<summary>Probe O01: Plain summary text</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O01.

End of probe O01.

</details>

<details open>
<summary>Probe O02: Entities &amp; &lt;tag&gt; in a summary</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O02.

End of probe O02.

</details>

<details open>
<summary>Probe O03: Inline code `copy --dry-run` in backticks</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O03.

End of probe O03.

</details>

<details open>
<summary>Probe O04: Inline code <code>copy --dry-run</code> as HTML</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O04.

End of probe O04.

</details>

<details open>
<summary>Probe O05: **Bold** text in a summary</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O05.

End of probe O05.

</details>

<details open>
<summary>Probe O06: <strong>Bold</strong> as HTML</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O06.

End of probe O06.

</details>

<details open>
<summary>Probe O07: Body — paragraph</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe O07.

End of probe O07.

</details>

<details open>
<summary>Probe O08: Body — lists</summary>

- First bullet
- Second bullet

1. First step
2. Second step

End of probe O08.

</details>

<details open>
<summary>Probe O09: Body — headings</summary>

### A third-level heading in probe O09

Text under the third-level heading.

#### A fourth-level heading in probe O09

Text under the fourth-level heading.

End of probe O09.

</details>

<details open>
<summary>Probe O10: Body — fenced code</summary>

```python
def probe():
    return "O10"
```

End of probe O10.

</details>

<details open>
<summary>Probe O11: Body — image</summary>

![Probe image in O11](./probe-image.png)

End of probe O11.

</details>

<details open>
<summary>Probe O12: Body — table</summary>

| Column | Value |
| --- | --- |
| form | details-open |
| probe | O12 |

End of probe O12.

</details>

<details open>
<summary>Probe O13: Body — nested</summary>

<details open>
<summary>Probe O13i: nested inner summary</summary>

Nested body of probe O13.

</details>

End of probe O13.

</details>

## Form L: in-list-item

the authored form indented under a bullet list item.

**What you should see:** Collapsed on load inside the list item, body rendered once expanded.

- A list item holding the block that follows

  <details>
  <summary>Probe L01: Plain summary text</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L01.
  
  End of probe L01.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L02: Entities &amp; &lt;tag&gt; in a summary</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L02.
  
  End of probe L02.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L03: Inline code `copy --dry-run` in backticks</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L03.
  
  End of probe L03.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L04: Inline code <code>copy --dry-run</code> as HTML</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L04.
  
  End of probe L04.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L05: **Bold** text in a summary</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L05.
  
  End of probe L05.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L06: <strong>Bold</strong> as HTML</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L06.
  
  End of probe L06.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L07: Body — paragraph</summary>
  
  A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe L07.
  
  End of probe L07.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L08: Body — lists</summary>
  
  - First bullet
  - Second bullet
  
  1. First step
  2. Second step
  
  End of probe L08.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L09: Body — headings</summary>
  
  ### A third-level heading in probe L09
  
  Text under the third-level heading.
  
  #### A fourth-level heading in probe L09
  
  Text under the fourth-level heading.
  
  End of probe L09.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L10: Body — fenced code</summary>
  
  ```python
  def probe():
      return "L10"
  ```
  
  End of probe L10.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L11: Body — image</summary>
  
  ![Probe image in L11](./probe-image.png)
  
  End of probe L11.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L12: Body — table</summary>
  
  | Column | Value |
  | --- | --- |
  | form | in-list-item |
  | probe | L12 |
  
  End of probe L12.
  
  </details>

- A list item holding the block that follows

  <details>
  <summary>Probe L13: Body — nested</summary>
  
  - A list item holding the block that follows
  
    <details>
    <summary>Probe L13i: nested inner summary</summary>
    
    Nested body of probe L13.
    
    </details>
  
  End of probe L13.
  
  </details>

## Form F: in-fenced-code

the authored form inside a fenced code block.

**What you should see:** Shown as code (literal text) everywhere: a fenced block is never parsed.

```markdown
<details>
<summary>Probe F01: Plain summary text</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F01.

End of probe F01.

</details>
```

```markdown
<details>
<summary>Probe F02: Entities &amp; &lt;tag&gt; in a summary</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F02.

End of probe F02.

</details>
```

```markdown
<details>
<summary>Probe F03: Inline code `copy --dry-run` in backticks</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F03.

End of probe F03.

</details>
```

```markdown
<details>
<summary>Probe F04: Inline code <code>copy --dry-run</code> as HTML</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F04.

End of probe F04.

</details>
```

```markdown
<details>
<summary>Probe F05: **Bold** text in a summary</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F05.

End of probe F05.

</details>
```

```markdown
<details>
<summary>Probe F06: <strong>Bold</strong> as HTML</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F06.

End of probe F06.

</details>
```

```markdown
<details>
<summary>Probe F07: Body — paragraph</summary>

A paragraph with *emphasis* and [a link](https://github.com/nickderobertis/onetaskgraph-live-scratch) in probe F07.

End of probe F07.

</details>
```

```markdown
<details>
<summary>Probe F08: Body — lists</summary>

- First bullet
- Second bullet

1. First step
2. Second step

End of probe F08.

</details>
```

```markdown
<details>
<summary>Probe F09: Body — headings</summary>

### A third-level heading in probe F09

Text under the third-level heading.

#### A fourth-level heading in probe F09

Text under the fourth-level heading.

End of probe F09.

</details>
```

````markdown
<details>
<summary>Probe F10: Body — fenced code</summary>

```python
def probe():
    return "F10"
```

End of probe F10.

</details>
````

```markdown
<details>
<summary>Probe F11: Body — image</summary>

![Probe image in F11](./probe-image.png)

End of probe F11.

</details>
```

```markdown
<details>
<summary>Probe F12: Body — table</summary>

| Column | Value |
| --- | --- |
| form | in-fenced-code |
| probe | F12 |

End of probe F12.

</details>
```

````markdown
<details>
<summary>Probe F13: Body — nested</summary>

```markdown
<details>
<summary>Probe F13i: nested inner summary</summary>

Nested body of probe F13.

</details>
```

End of probe F13.

</details>
````
