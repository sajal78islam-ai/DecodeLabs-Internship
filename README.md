"# DecodeLabs-Internship" 
# EduFlow - Student LMS Portal
## Project 1: Frontend Development (HTML & CSS)
 
---
 
##  **Quick Overview**
 
- **Project**: Student Learning Management System Portal
- **Built With**: Semantic HTML5 + Professional CSS
- **Standards**: DecodeLabs Project 1 Requirements

---
 
##  **Files**
 
| File | Purpose |
|------|---------|
| `lms-portal.html` | Complete HTML structure |
| `lms.css` | All styling (CSS variables, Grid, Flexbox) |
 
---
 
##  **Key Features**
 
 **Sticky Header** - Top navigation with user profile  
**Sidebar Navigation** - 6 menu items with icons  
 **Dashboard** - Welcome message + stats cards  
 **Courses Grid** - Progress bars, instructor info  
 **Assignments List** - Due dates, status tracking  
 **Grades Table** - Semantic HTML table  
 **Resources** - 6 resource types with icons  
 **Weekly Schedule** - 7-day event view  
 **Responsive Design** - Works on all devices  
 
---
 
##  **Customization**
 
### **Change Colors**
Open `lms.css` → Find `:root` section → Edit color values:
```css
--color-primary: #0066cc;        /* Main blue */
--color-secondary: #00a86b;      /* Green accent */
--color-accent: #ff6600;         /* Orange accent */
```
 
### **Adjust Sidebar Width**
In `:root` section:
```css
--sidebar-width: 260px;  /* Change to 200px, 180px, etc. */
```
 
### **Change Spacing**
```css
--spacing-md: 16px;              /* Standard padding */
--spacing-lg: 24px;              /* Large padding */
--spacing-xl: 32px;              /* Extra large */
```
 
---
 
##  **Responsive Breakpoints**
 
| Device | Width | Layout |
|--------|-------|--------|
| Desktop | 1200px+ | Full sidebar + content |
| Tablet | 768px - 1199px | Adjusted layout |
| Mobile | 480px - 767px | Single column |
| Small | < 480px | Touch-friendly |
 
---
 
##  **Project 1 Compliance**
 
 **Semantic HTML** - Proper landmarks, one h1, heading hierarchy  
 **External CSS Only** - No inline styles  
 **DRY Principle** - CSS variables for all values  
 **BEM Methodology** - `.block__element--modifier` naming  
 **Grid + Flexbox** - Grid for layout, Flexbox for components  
 **Responsive Design** - Mobile-first approach  
**Accessibility** - WCAG AA, keyboard nav, aria labels  
 **W3C Valid** - Zero HTML/CSS errors  
 
---
 
##  **How to Use**
 
1. **Double-click** `lms-portal.html` → Opens in browser
2. **Or use Live Server** → Right-click → "Open with Live Server"
3. **Edit content** → Modify HTML text
4. **Change styles** → Edit CSS variables in `lms.css`
5. **Save & Refresh** → See changes instantly
---
 
##  **Design System**
 
**Colors:**
- Primary (Blue): `#0066cc`
- Secondary (Green): `#00a86b`
- Accent (Orange): `#ff6600`
- Text: `#1a1a1a`, `#666666`
- Background: `#ffffff`, `#f5f5f5`
**Typography:**
- Font: System fonts (no external downloads)
- Sizes: 12px → 48px scale
- Weights: 400, 500, 600, 700
**Spacing:**
- 8px baseline scale: 4px → 96px
- Uses CSS variables for consistency
---
 
##  **Common Fixes**
 
### **Sidebar hiding content?**
Change in `:root`:
```css
--sidebar-width: 200px;  /* Reduce width */
```
 
### **Footer behind sidebar?**
Add to `.footer`:
```css
margin-left: var(--sidebar-width);
```
 
### **Too much white space?**
Reduce padding in section styles:
```css
padding: var(--spacing-2xl) var(--spacing-lg);  /* Instead of 3xl */
```
 
---
 
##  **Browser Support**
 
 Chrome (Latest)  
 Firefox (Latest)  
 Safari (Latest)  
 Edge (Latest)  
 Mobile Browsers  
 
---
 
##  **Learning Resources**
 
- **Semantic HTML**: https://developer.mozilla.org/en-US/docs/Glossary/Semantics
- **CSS Grid**: https://css-tricks.com/snippets/css/complete-guide-grid/
- **Flexbox**: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- **Accessibility**: https://www.w3.org/WAI/WCAG21/quickref/
- **W3C Validator**: https://validator.w3.org/
---
 
---
 
##  **Features at a Glance**
 
| Section | Features |
|---------|----------|
| **Header** | Sticky nav, notifications, user profile |
| **Sidebar** | 6 menu items, active states |
| **Dashboard** | Personalized welcome, 3 stat cards |
| **Courses** | Grid layout, progress bars, badges |
| **Assignments** | List view, due dates, statuses |
| **Grades** | Semantic table, grade display |
| **Resources** | 6 resource types, icons, links |
| **Schedule** | 7-day weekly view |
| **Footer** | Links, copyright, company info |
 
---

---
