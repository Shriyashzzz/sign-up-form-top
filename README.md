# A-Levels Tutor - Sign Up Form

A personal project built to practice CSS form styling and HTML5 client-side validation. The project is a sign-up page for a fictional A-Level tutoring service, featuring a two-column layout with a decorative aside panel and a structured registration form.

---

## Live Demo



---

## Features

- HTML5 built-in validation using `required`, `pattern`, `minlength`, and `type` attributes
- CSS-only validation feedback using `:user-valid` and `:user-invalid` pseudo-classes
- Custom focus and hover states on inputs with box-shadow transitions
- Two-column split layout using Flexbox (decorative aside + main form content)
- Custom web fonts loaded via `@font-face`
- Responsive viewport height using `100dvh`
- Password strength enforced via regex pattern (uppercase, lowercase, number, special character, 8-12 chars)

---

## Built With

- HTML5
- CSS3

No JavaScript, no libraries, no frameworks.



## Project Structure

```
/
├── index.html
├── style.css
├── images/
│   ├── logo.png
│   └── company-logo-icon.jpg
└── font-index/
    ├── IntroRustG-Base2Line.woff2
    ├── IntroRustG-Base2Line.woff
    ├── IntroHeadR-Base.woff2
    └── IntroHeadR-Base.woff
```

---

## What I Practiced

**HTML:**
- Semantic structure using `<form>`, `<fieldset>`, `<label>`, `<article>`, `<aside>`, and `<section>`
- Native validation attributes: `required`, `pattern`, `minlength`, `type="email"`, `type="tel"`
- Regex patterns for password rules and phone number format
- Correct `for`/`id` pairing between labels and inputs

**CSS:**
- `:user-valid` and `:user-invalid` for post-interaction validation feedback (no JavaScript needed)
- `:focus` and `:hover` states with `box-shadow` and `border-color` overrides
- `@font-face` for loading custom local fonts in `woff2`/`woff` formats
- Flexbox for both the page layout and the two-column form fieldset
- `object-fit: cover` on the aside image for full-height coverage
- `position: absolute` for the logo overlay on the aside panel
- CSS nesting for scoped component styles


## Known Limitations

- Confirm password match is not validated (requires JavaScript)
- No responsive/mobile breakpoints yet

---

## What's Next

- [ ] Add JavaScript to validate that both password fields match
- [ ] Add a login page to complement the sign-up page
- [ ] Add mobile breakpoints for smaller screens
- [ ] Animate error/success state transitions
