# everybookitsreader.org

Website for the #EveryBookItsReader / #CadaLivroSeuPúblico Wikimedia campaign.

- Hosted free on **GitHub Pages** (built with Jekyll); domain registered at Porkbun.
- Edited with **Pages CMS** at https://app.pagescms.org — no coding needed. See [EDITING.md](EDITING.md).

## Where things are

| What | File |
| --- | --- |
| English pages | `pages/en/*.md` |
| Portuguese pages | `pages/pt/*.md` |
| Menu, footer, logos (both languages) | `_data/site.yml` |
| Images and documents | `assets/uploads/` |
| Page design | `_layouts/default.html`, `assets/css/style.css` |
| Editor setup | `.pages.yml` |

Each page has a `ref` in its front matter. The English and Portuguese versions of the same page share the same `ref`, which is how the language switcher links them.

Every change is saved in the repository history, so any edit can be undone.
