# Bug Reports – Nirvana Japanese Spa Website

---

## Bug 1: 
[RU Services Page] Typo in word “люой” instead of “любой” in ROYAL spa package description

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

## Bug 5: Missing English language option in mobile menu (Safari, Russian version)

### Environment
Browser: Safari  
Device: iPhone 12(Mobile)  
Language: Russian  

### Preconditions
The user opens the website on a mobile device using Safari browser.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch the language to Russian
3. Open the mobile menu "Акции скидки и распродажи"
4. Open the mobile menu
5. Locate the language switcher

### Actual Result
Only Hebrew language option is available. English language option is missing.

### Expected Result
The language switcher should provide all available language options (Russian, English, Hebrew).

### Severity
Medium

### Status
Open

### Notes
The issue occurs in the mobile version (Safari) and may not be reproducible on desktop browsers.

---

## Bug 6: Missing English language option in mobile menu (Safari, Hebrew version)

### Environment
Browser: Safari  
Device: iPhone 12 (Mobile)  
Language: Hebrew  

### Preconditions
The user opens the website on a mobile device using Safari browser.

### Steps to Reproduce
1. Open the website: https://nirvanajapanesespa.com
2. Switch the language to Hebrew
3. Open the mobile menu "מבצעים החודש"
4. Open the mobile menu  
5. Locate the language switcher

### Actual Result
Only Russian language option is available. English language option is missing.

### Expected Result
The language switcher should provide all available language options (Russian, English, Hebrew).

### Severity
Medium

### Status
Open
