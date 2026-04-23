# Inspect-Based Test Cases – Portfolio Website

## TC-01: Verify desktop layout renders correctly
**Type:** UI / Responsive  
**Tool:** Chrome DevTools  
**Viewport:** Desktop  

### Steps
1. Open the portfolio website in Chrome
2. Open DevTools
3. Keep default desktop viewport
4. Review navigation, hero section, and content cards

### Expected Result
Navigation is fully visible, hero content is aligned correctly, and sections render without overlap or clipping.

### Actual Result
Pass – Desktop layout rendered correctly with visible navigation and aligned content sections.

<img width="1726" height="993" alt="image" src="https://github.com/user-attachments/assets/6d7eb4cc-d232-41cc-973f-a92fa880f685" />


---

## TC-02: Verify tablet layout using Device Toolbar
**Type:** Responsive  
**Tool:** Chrome DevTools Device Toolbar  
**Viewport:** iPad Pro (1024 × 1366)

### Steps
1. Open the portfolio website
2. Open DevTools
3. Enable Device Toolbar
4. Select iPad Pro viewport
5. Inspect navigation, hero section, and section containers

### Expected Result
Content should remain inside the viewport, image and text should scale appropriately, and layout should adapt without breaking.

### Actual Result
Pass – Layout remained within viewport and content scaled appropriately in tablet view.

<img width="1726" height="993" alt="image" src="https://github.com/user-attachments/assets/85208058-2478-4226-9819-44b185809a44" />


---

## TC-03: Verify mobile layout using Device Toolbar
**Type:** Responsive  
**Tool:** Chrome DevTools Device Toolbar  
**Viewport:** iPhone 14 Pro Max (430 × 932)

### Steps
1. Open the portfolio website
2. Open DevTools
3. Enable Device Toolbar
4. Select iPhone 14 Pro Max viewport
5. Review navigation wrapping, text flow, image scaling, and content stacking

### Expected Result
Navigation should remain visible, content should stack vertically, and text should remain readable without horizontal overflow.

### Actual Result
Pass – Navigation wrapped visibly, hero content stacked correctly, and text remained readable on mobile view.

<img width="1726" height="993" alt="image" src="https://github.com/user-attachments/assets/e2767532-edad-4f0a-80f5-9c68b91eb1d2" />


---

## TC-04: Inspect CSS rules applied to page body
**Type:** UI Inspection  
**Tool:** Chrome DevTools Elements + Styles panels  

### Steps
1. Open the website
2. Open DevTools
3. Select the `body` element in the Elements panel
4. Review applied CSS rules in the Styles panel

### Expected Result
Applied styles should match intended page formatting such as font-family, background, color, and padding.

### Actual Result
Pass – Body styles were visible in the Styles panel and matched the expected visual presentation.

<img width="1726" height="993" alt="image" src="https://github.com/user-attachments/assets/77c02aae-dd4b-4632-9355-9b4c306fb49c" />

---

## TC-05: Verify responsive media query application
**Type:** CSS / Responsive Inspection  
**Tool:** Chrome DevTools Styles panel  
**Viewport:** Mobile  

### Steps
1. Open the website
2. Switch to mobile viewport in Device Toolbar
3. Select the `body` element
4. Review active responsive CSS rules in the Styles panel

### Expected Result
Media query styles for smaller screens should appear and override default styles where appropriate.

### Actual Result
Pass – Mobile-specific media query rules appeared in DevTools and were applied in the tested viewport.

<img width="1726" height="993" alt="image" src="https://github.com/user-attachments/assets/08c59df4-0b51-4ccb-8dca-42f6d2a3c5fe" />

---

## TC-06: Verify hero section reflow across viewports
**Type:** Responsive Layout  
**Tool:** Chrome DevTools Device Toolbar  
**Viewports:** Desktop, Tablet, Mobile  

### Steps
1. Open the website
2. Inspect the hero section in desktop view
3. Switch to tablet view
4. Switch to mobile view
5. Compare text and image positioning

### Expected Result
Hero section should adapt across screen sizes, preserving readability and visual balance.

### Actual Result
Pass – Hero section reflowed appropriately from larger to smaller viewports.

<img width="752" height="174" alt="image" src="https://github.com/user-attachments/assets/be676a0f-21fe-45f7-95b0-595532454da5" />


---

## TC-07: Verify content remains readable after responsive scaling
**Type:** UI / Readability  
**Tool:** Chrome DevTools Device Toolbar  
**Viewport:** Mobile  

### Steps
1. Open the website in mobile viewport
2. Review heading, paragraph text, and section titles
3. Check whether text remains readable without layout breakage

### Expected Result
Headings and body text should remain readable and properly spaced on smaller screens.

### Actual Result
Pass – Text remained readable and visually organized in tested mobile view.

<img width="752" height="931" alt="image" src="https://github.com/user-attachments/assets/d9987be3-4f74-43af-8657-68d310b95c6c" />


---

## TC-08: Verify section containers stay within visible viewport
**Type:** Layout Validation  
**Tool:** Chrome DevTools Device Toolbar  
**Viewports:** Tablet, Mobile  

### Steps
1. Open the website
2. Test tablet and mobile viewports
3. Review outer section cards and inner content blocks

### Expected Result
Containers should remain inside the screen width without visible clipping or horizontal overflow.

### Actual Result
Pass – Section containers remained within viewport in tested layouts.
