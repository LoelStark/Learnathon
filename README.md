# EES Cybersecurity Courses

A single-page website for students of the Electrical Engineering Society (EES), in partnership with BroConsulting. It lists five free Cisco Networking Academy (NetAcad) cybersecurity courses and links straight to each registration page.

## Courses

1. Introduction to Cybersecurity
2. Cybersecurity Essentials
3. Network Defense
4. Endpoint Security
5. Cyber Threat Management

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site. Styles and logos are embedded, so there is nothing else to upload. |
| `README.md` | This file. |

Rename `ees-cybersecurity-courses.html` to `index.html` before you commit it, so GitHub Pages serves it as the home page.

## Publish with GitHub Pages

1. Create a repository and add `index.html` and `README.md` to the main branch.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then save.
5. After a minute or two, the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Editing the page

- **Course links:** each course is a card in `index.html`. Change the `href` on its Register button to update the link.
- **Adding or removing a course:** copy or delete a whole `<li class="card">` block. Update the number in `<div class="num">` and pick a colour with `style="--c:..."`.
- **Logos:** they are embedded in the `<img>` tags at the top of the page as base64 data. To swap one, replace the `src` value with the path to a new image file (for example `logos/ees.png`) and upload that file to the repository.
- **Colours:** the brand colours are defined as variables at the top of the `<style>` block.

## Notes

- Registration is handled entirely by NetAcad. This site only links to it, and no student data is collected or stored here.
- Course links include NetAcad `instance_id` values. If NetAcad changes or retires a course instance, the link will need updating.
- Logos belong to EES and BroConsulting respectively.
