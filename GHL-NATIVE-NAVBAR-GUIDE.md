# SFG Navbar — Build It Natively in GoHighLevel (Website)

This recreates the Wealthspire-style navbar using GHL's own tools, so it
shows in Preview and applies to every page. No custom code needed.

**Brand values to use everywhere:**
- Navy: `#07304B`
- Gold: `#FFD166`
- Background: `#FFFFFF`
- Logo URL: `https://assets.cdn.filesafe.space/frh1FySyXd0r7cSut9EW/media/6a36fa546a6dd1b69a5c5745.png`

---

## STEP 1 — Open the page in the Website editor
Sites → Websites → your site → open a page (e.g. Home) in the builder.

## STEP 2 — Add a Section at the very top
1. Hover at the top of the page → click **Add Section** (or the **+**).
2. Choose a **blank / 1-column** section. This is your navbar bar.
3. Click the section → **Section Settings** (gear):
   - **Background color:** `#FFFFFF`
   - **Width:** Full width
   - **Padding:** Top `10`, Bottom `10`, Left `40`, Right `40`
   - **Bottom border:** 3px solid `#FFD166`  (under Border settings)

## STEP 3 — Make it a 2-column row (logo | menu)
1. Inside the section add a **Row** with **2 columns**.
2. Set the **left column width ~30%**, **right column ~70%**.
3. Row vertical align: **Center**.

## STEP 4 — Left column: the logo
1. Drag an **Image** element into the left column.
2. Upload / paste the logo URL above.
3. Set image **width ~200px** (height auto). Align **Left**.
4. Click the image → add a **Link** → `https://sfgtaxservice.com/home-5735`.

## STEP 5 — Right column: the menu
You have two options:

### Option A — "Custom Menu" element (recommended)
1. Drag a **Menu** / **Navigation** element into the right column.
2. Add these items with their links:
   | Label            | URL |
   |------------------|-----|
   | Home             | https://sfgtaxservice.com/home-5735 |
   | About Us         | https://sfgtaxservice.com/about-us |
   | Services         | https://sfgtaxservice.com/services |
   | Track My Refund  | https://www.irs.gov/wheres-my-refund  (open in new tab) |
3. Align the menu **Right**.
4. Style the menu:
   - **Text color:** `#07304B`
   - **Font:** a serif (Georgia / Playfair) to match the financial look
   - **Font size:** 15px, **weight** 600
   - **Hover color:** `#C99A2E` (darker gold)
   - **Spacing between items:** ~16–20px

### Option B — Individual Text/Button elements
Drop 4 **Text** elements side by side, each linked. More manual, but
full control if the Menu element is limited on your plan.

## STEP 6 — The "Become a Client" button
1. In the right column, after the menu, drag a **Button** element.
2. **Text:** `Become a Client`
3. **Link:** `https://sfgtaxservice.com/new-client`
4. Style:
   - **Background:** `#07304B`
   - **Text color:** `#FFD166`
   - **Border radius:** 4px
   - **Padding:** 12px top/bottom, 26px left/right
   - **Hover background:** `#FFD166`, **hover text:** `#07304B`

## STEP 7 — Make the bar stick to the top (optional)
1. Select the **Section** → Settings → **Advanced**.
2. Look for **"Sticky"** / **"Stick to top on scroll"** toggle → enable it.
   (Available on most GHL website themes. If absent, the bar still works,
   it just won't follow you as you scroll.)

## STEP 8 — Apply to every page
GHL Websites: build this section once, then either
- Use the theme's **Global Header** (Website Settings → Header) if your
  template supports it, **or**
- **Copy the section** (section menu → Copy) and **Paste** it at the top
  of each other page.

## STEP 9 — Save → Publish → check
Save, Publish, and view. With native elements it will also render in the
**Preview** button (unlike the tracking-code script).

---

### Mobile
GHL's Menu element auto-collapses into a hamburger on mobile. In the
**mobile view** of the editor, confirm the logo shrinks and the menu
becomes a hamburger; adjust the logo width to ~140px for mobile if needed.
</content>
