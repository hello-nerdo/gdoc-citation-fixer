# gdoc-citation-fixer

Transform Google Docs citations into proper Markdown footnotes and references

![UI Screenshot](/ui.jpg)

## Features

- Converts inline citations (e.g., "text1." → "text[^1].")
- Transforms numbered reference lists into Markdown footnotes
- Handles quoted text with trailing citations
- Browser-based with no dependencies

## Usage

1. Download `index.html`
2. Open in any web browser
3. Paste your Google Docs-exported Markdown
4. Click "Transform"
5. Copy the result

## Example

Before:
```markdown
According to research1, the data shows promising results2.

#### **Works cited**
1\. Smith, J. (2023). Research Paper
2\. Jones, M. (2024). Data Analysis
```

After:
```markdown
According to research[^1], the data shows promising results[^2].

[^1]: Smith, J. (2023). Research Paper
[^2]: Jones, M. (2024). Data Analysis
```
