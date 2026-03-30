# Bug Reports – Nirvana Japanese Spa Website

---

## Bug 1: [RU Services Page] Typo in word “люой” instead of “любой” in ROYAL spa package description

### Environment
Browser: Chrome
Device: Desktop
Language: Russian

### Preconditions
User opens the website in Russian Language

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch language to Russian
3. Navigate to the “Каталог услуг” 
4. Scroll to “SPA-пакеты ROYAL”
5. Check line 9 in the description

### Actual Result
The word “люой” is displayed (missing letter “б”)

### Expected Result
The word “любой” should be displayed correctly

### Severity
low

### Status
Open

---

## Bug 2: External link opens in the same tab instead of a new tab

### Preconditions
The user opens the website and navigates to the "Company Policy" page in Russian language.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch language to Russian
3. Navigate to the "Политика компании" page: https://nirvanajapanesespa.com/ru/policyru/ 
4. Scroll down the page
5. Click "Политика и правила акций"

### Actual Result
The external link opens in the same browser tab.

### Expected Result
The external link should open in a new browser tab without replacing the current page.

### Severity
Medium

### Status
Open

---

## Bug 3: Incorrect language displayed in "Company Policy" page title

### Preconditions
The user opens the website and selects Russian or English language

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch the language to Russian or English
3. Navigate to the "Company Policy" page:
   - Russian: https://nirvanajapanesespa.com/ru/policyru/
   - English: https://nirvanajapanesespa.com/en/policyen/

### Actual Result
The page title is displayed in Hebrew ("מדיניות ונהלים") instead of the selected language.

### Expected Result
The page title should match the selected language:
- Russian: "Политика компании"
- English: "Company Policy"

### Severity
Medium

### Status
Open

---

## Bug 4: Service item is expanded by default in the catalog page

### Preconditions
The user opens the website in Russian language.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch the language to Russian
3. Navigate to the "Services Catalog" page: https://nirvanajapanesespa.com/ru/catalogru/

### Actual Result
The service "Спа головы 30 минут" is expanded by default when the page loads.

### Expected Result
All service items should be collapsed by default when the catalog page is opened.

### Severity
Low

### Status
Open
### Notes
This behavior contradicts the requirement that all services shall be collapsed by default (see SRS section 3.3.2.5)

---

## Bug 5: Missing English language option on "Promotions and Discounts" page

### Environment
Browser: Chrome, Safari  
Device: Desktop, Mobile  
Languages: Russian, Hebrew

### Preconditions
The user opens the website and selects either Russian or Hebrew language.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch language to Russian or Hebrew
3. Navigate to the "Акции и скидки" / "מבצעים והנחות" page

### Actual Result
The language switcher does not include an option to switch to English.

### Expected Result
The language switcher should provide all available language options (Russian, English, Hebrew).

### Severity
Medium

### Status
Open

### Notes
Issue occurs on both desktop and mobile but only on this specific page.

---

## Bug 6: Website layout breaks after navigation (CSS/Responsive issue)

### Environment
Browser: Safari, Chrome  
Device: Mobile (iPhone)  
Mode: Private browsing  
Language: Any  

### Preconditions
The user opens the website and navigates between pages.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Navigate between several pages (e.g., Home → Catalog → Policy)
3. Observe the layout

### Actual Result
- Two logos are displayed at the top
- Navigation menu is broken (links displayed as a vertical list instead of a menu)
- Page layout exceeds screen width
- Images are oversized and not responsive
- Fonts appear inconsistent
- Layout appears “unstyled” or broken

### Expected Result
- The layout should remain consistent and responsive after navigation
- Only one logo should be displayed
- Navigation menu should function correctly
- Images should scale properly within screen boundaries
- Fonts and styles should remain consistent

### Severity
High

### Status
Open

### Notes
The issue appears intermittently after navigating between pages and is reproducible across multiple browsers (Safari, Chrome).

---

## Bug 7: Inconsistent language switcher in English version

### Environment
Browser: Chrome, Safari  
Device: Desktop, Mobile  
Language: English

### Preconditions
User opens the website in English.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch to English language
3. Observe the language switcher in the header/menu on any page

### Actual Result
Two separate buttons are displayed for Hebrew and Russian languages instead of a unified language switcher.  
This occurs on **all pages** in the English version.

### Expected Result
The English version should have the same unified language switcher style as in the Russian and Hebrew versions (single dropdown or consistent control) according to SRS.

### Severity
Medium

### Status
Open


