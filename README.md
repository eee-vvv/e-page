# personal-site

Plain HTML + one CSS file, with no build step. Open `index.html` in a browser to preview.

## Where things live

| To change…                        | Edit                                          |
| --------------------------------- | --------------------------------------------- |
| Bio text, links on the home page  | `index.html`                                  |
| Work / projects list              | `work.html`                                   |
| Colors, fonts, text sizes         | `style.css` → **1. Settings** (top of file)   |
| Home page layout                  | `style.css` → **3. Home page**                |
| How things look on phones         | `style.css` → **5. Mobile**                   |
| Photo / handwritten name / icon   | `images/`                                     |
| Resume                            | replace `resume.pdf` (keep the filename)      |

## Adding a page

Copy `work.html` and change the content inside `<main>`. If the new page
is in a subfolder (like `summer25/`), prefix shared files with `../`,
for example `href="../style.css"`.

## Checking the mobile layout

In Firefox or Chrome, open dev tools and toggle the device toolbar
(Ctrl+Shift+M). Anything narrower than 800px uses the mobile styles.
