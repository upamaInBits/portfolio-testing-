# Portfolio Testing – QA Inspection

## Overview
This repository documents manual QA testing performed on a personal portfolio website using Chrome DevTools. The focus of this testing was on UI behavior, responsive layout validation, and inspection-based analysis across multiple screen sizes.

---

## Testing Type
- Exploratory Testing  
- UI Inspection  
- Responsive Testing  
- DevTools-based Validation  

---

## Scope
- Navigation bar  
- Hero section  
- Education section  
- Projects section  
- Responsive layout behavior  
- External links  
- CSS inspection using Chrome DevTools  

---

## Devices / Viewports Tested
- Desktop view  
- iPad Pro (1024 × 1366)  
- iPhone 14 Pro Max (430 × 932)  

---

## Tools Used
- Chrome DevTools  
- Elements Panel (DOM inspection)  
- Styles Panel (CSS inspection & overrides)  
- Device Toolbar (responsive testing)  
- Console (basic JavaScript validation)  
- Network Tab (resource loading & performance)  

---

## Test Observations

### Responsive Layout
- Navigation menu remained visible across all tested viewports  
- Navigation items wrapped appropriately on smaller screens  
- Hero section transitioned from side-by-side layout (desktop) to stacked layout (mobile)  
- Content containers remained within viewport boundaries  
- Images scaled proportionally without distortion  

---

### UI Inspection
- DOM structure validated using Elements panel  
- CSS rules reviewed and tested using Styles panel  
- Temporary style overrides applied to verify layout boundaries and behavior  
- Section spacing and alignment remained consistent across screen sizes  

---

### Functional Checks
- All primary content rendered correctly  
- Section text remained readable across devices  
- Visual hierarchy (headings, sections, spacing) was preserved  
- External links opened correctly in new tabs  

---

## Network & Performance Insights
- All primary resources loaded successfully (Status 200 / 304)  
- Browser caching observed through 304 (Not Modified) responses  
- Under throttled conditions (Slow 3G + Disable Cache):
  - Initial page load increased significantly (~2–3 seconds)
  - Image loading times increased substantially (up to ~1 minute)
  - Multiple requests entered a "Pending" state due to network constraints
- A 404 error was observed for `favicon.ico`, indicating a missing static asset  

---

## Console Observations
- No critical JavaScript errors detected  
- Successfully executed JavaScript commands (e.g., `document.title`)  
- Confirmed ability to interact with DOM via Console  

---

## Summary
Manual QA testing was conducted using Chrome DevTools to evaluate UI behavior, responsiveness, and performance characteristics of the portfolio website.

Across desktop, tablet, and mobile viewports, the application maintained:
- Stable layout structure  
- Readable content  
- Functional navigation  

Under simulated slow network conditions, the application demonstrated:
- Progressive loading behavior  
- Increased latency without layout breakage  

Overall, the system performed reliably across tested scenarios, with minor non-critical observations such as a missing favicon resource.

---

## Key QA Skills Demonstrated
- UI and responsive testing  
- DevTools-based inspection (Elements, Styles, Console, Network)  
- Network throttling and performance analysis  
- Debugging using Console and resource tracking  
- Understanding of HTTP status codes (200, 304, 404)  
