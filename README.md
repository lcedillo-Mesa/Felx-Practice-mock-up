# CSS Flexbox — Part 2: Style the Mock-Up

You have already discovered what flexbox does by uncommenting the CSS.

Now it is your turn to **write it yourself.**

You have been given:
- The same `index.html` file from Part 1 — do not change it
- A new `style.css` with some properties **missing**
- A mock-up showing what your page should look like when you are done

> **Your goal:** Fill in the missing CSS values so your page matches the mock-up.

---

## Before You Start

Open these three things side by side:

1. `style.css` in Codespaces
2. The live preview (right-click `index.html` → Open with Live Server)
3. The mock-up reference sheet

Look at the mock-up carefully before you write anything.

**Ask yourself:**
- What colour is the header?
- Where are the nav links sitting?
- Which direction do the two sections go?
- Where is the footer text?

---

## What Is Different From Part 1?

The colours and spacing have changed. Some flex property **values** have also changed.

Here is what is new:

| Section | What changed |
|---------|--------------|
| Header | Darker teal background. Text is now on the **left** — not centred |
| Nav | Green background. Links start from the **left** — not centred |
| Main | Warmer off-white background. Gap is smaller (16px not 24px) |
| Footer | Text is pushed to the **right** — not centred |

---

## The Missing Properties

Your `style.css` has **5 blanks** to fill in. They are marked with `/* ??? */`.

Find each one and replace it with the correct value.

### Blank 1 — `.header` → `align-items`

Look at the mock-up. The heading and tagline are on the **left side** of the header.

Which value lines items up on the left?

```css
.header {
  align-items: /* ??? */;
}
```

**Hint:** It is not `center`. Look at the flex cheat sheet for other options.

---

### Blank 2 — `.nav` → `flex-direction`

The nav links are sitting **side by side** in a row.

Which flex-direction value makes items go left to right?

```css
.nav {
  flex-direction: /* ??? */;
}
```

**Hint:** You used this value in Part 1. Check your notes.

---

### Blank 3 — `.nav` → `justify-content`

The links start from the **left edge** of the nav bar.

Which value pushes items to the start?

```css
.nav {
  justify-content: /* ??? */;
}
```

**Hint:** The opposite of `flex-end`. Items go to the beginning.

---

### Blank 4 — `.main` → `display`

The two sections are sitting **next to each other**.

What do you need to add to the parent to make children go side by side?

```css
.main {
  display: /* ??? */;
}
```

**Hint:** This is the one property that turns flexbox on. You have written it many times today.

---

### Blank 5 — `.footer` → `justify-content`

The footer text is on the **right side**.

Which value pushes content to the end?

```css
.footer {
  justify-content: /* ??? */;
}
```

**Hint:** The opposite of `flex-start`. Think about where the end of a row is.

---

## Check Your Work

When all 5 blanks are filled in, your page should match the mock-up exactly.

Go through this list:

- [ ] Header background is dark teal `#1a3a4a`
- [ ] Header text is on the left
- [ ] Nav background is green `#0F6E56`
- [ ] Nav links start from the left with space between them
- [ ] Main background is warm off-white `#F1EFE8`
- [ ] Two sections sit side by side with a gap
- [ ] Footer text is on the right

---

## Stuck?

Try these before asking for help:

1. Look at your **cheat sheet** — find the property name and read the values listed
2. Look at your **Part 1 code** — you have already used all of these values before
3. Check the **mock-up annotations** — each section has a label showing which property changed

---

## Early Finisher Challenge

Your page matches the mock-up — great work. Now try these:

**Challenge 1:** Change the nav links so they are spaced evenly across the full width of the nav bar. Which value do you need?

**Challenge 2:** Make the two sections stack on top of each other instead of sitting side by side. What do you change and where?

**Challenge 3:** Move the header text to the right side. What property and value does that?

Write your prediction first, then try it. If it breaks, undo with **Ctrl + Z**.

---

## Exit Ticket

Before you close your laptop, make sure you can answer these:

1. What does `display: flex` do?
2. Which property controls left and right spacing?
3. Which property controls up and down alignment?
4. Does `display: flex` go on the parent or the child?
