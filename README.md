# jsonresume-theme-onepage-mrseanryan

A tweaked version of `jsonresume-theme-onepage`.

A compact theme for JSON Resume, designed for printing.

Tries to fit as much information as possible onto a single page without making sections look cluttered.

MODIFIED by mrseanryan:

- resume.json extended to *extensibly* have more sections (under 'basics' so is still parseable by standard themes)
- allow highlights to have a hierarchy ('-' bullet points)
- slightly bigger font
- show only 'website' not the full list of networks/profiles
- allow a section to have preceding blank lines, for a page-break
- other minor tweaks

## Example

http://themes.jsonresume.org/theme/onepage

## Running

```
sudo npm install -g resume-cli
git clone https://github.com/ainsleyc/jsonresume-theme-onepage.git
cd jsonresume-theme-onepage
resume serve
```
You can print directly from the served html.

## Options

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See included resume.json for more details.

