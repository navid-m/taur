## Typography

-  `h1` to `h6` – Styles for headings from largest (`h1`) to smallest (`h6`).
-  `p` – Paragraph text styling.
-  `li` – Styles list items with padding or marker tweaks.

## Layout Systems

### Grid System

-  `.grid` – Enables CSS grid layout.
-  `.grid.dense` – Collapses grid gaps for a denser layout.
-  `.grid.wide` – Expands grid container width.
-  `.grid.cols-2` – Defines two equal-width grid columns.
-  `.grid.cols-3` – Defines three equal-width grid columns.
-  `.grid.cols-4` – Defines four equal-width grid columns.

### Flexbox System

-  `.flex` – Applies flexbox layout.
-  `.flex.column` – Changes flex direction to column.
-  `.flex.center` – Centers items horizontally and vertically.
-  `.flex.between` – Justifies content with space between items.
-  `.flex.around` – Justifies content with space around items.
-  `.flex.end` – Aligns items to the end of the container.
-  `.flex.mobile-row` – On mobile, forces flex direction to row.

## Boxes and Containers

-  `.box` – Basic box container styling.
-  `.r-box` – Rounded box with border-radius.
-  `.danger-box` – Box styled to indicate danger or error.
-  `.success-box` – Box styled to indicate success.
-  `.info-box` – Box styled to show informational messages.
-  `.page` – Wrapper for page-level container.
-  `.container` – Central layout container.
-  `.container.narrow` – Restricts container width to a narrow layout.
-  `.container.wide` – Expands container to a wider layout.

## Sections

-  `.section` – Content section wrapper.
-  `.section.compact` – Section with reduced padding.
-  `.section.spacious` – Section with increased padding.
-  `.part-section` – Section block for page parts.
-  `.part-section h2` – Heading inside part section.
-  `.color-part-section` – Themed color section.

## Spacing Utilities

### Padding Top (`pt-`)

-  `.pt-1` to `.pt-10` – Adds increasing top padding.

### Padding Bottom (`pb-`)

-  `.pb-1` to `.pb-10` – Adds increasing bottom padding.

### Padding Left (`pl-`)

-  `.pl-1` to `.pl-10` – Adds increasing left padding.

### Padding Right (`pr-`)

-  `.pr-1` to `.pr-10` – Adds increasing right padding.

### Padding Horizontal (`px-`)

-  `.px-1` to `.px-10` – Adds increasing left & right padding.

### Padding Vertical (`py-`)

-  `.py-1` to `.py-10` – Adds increasing top & bottom padding.

## Hero Components

-  `.hero` – Main hero section container.
-  `.hero::before` – Pseudo-element for background or overlays.
-  `.hero-content` – Container for hero content.
-  `.hero-title` – Main heading style in hero.
-  `.hero-subtitle` – Subtitle text in hero.
-  `.hero-cta` – Container for hero call-to-action elements.
-  `.hero-btn` – Base button style in hero.
-  `.hero-btn--primary` – Primary hero button.
-  `.hero-btn--primary:hover` – Hover effect for primary button.
-  `.hero-btn--secondary` – Secondary hero button.
-  `.hero-btn--secondary:hover` – Hover effect for secondary button.
-  `.hero[data-colors]` – Applies theme-based color variants.

### Hero Color Variants

-  `.hero-red`
-  `.hero-green`
-  `.hero-purple`
-  `.hero-orange`
-  `.hero-pink`
-  `.hero-teal`
-  `.hero-dark`

## Quotes

-  `.quote` – Styles quote elements.
-  `.quote:hover` – Hover effect on quote.
-  `.quote::before` – Decorative quote symbol or icon.

## Spacing Between Elements

-  `.space > * + *` – Adds spacing between direct children.
-  `.space.tight > * + *` – Reduced spacing.
-  `.space.loose > * + *` – Looser spacing.
-  `.space.huge > * + *` – Very large spacing.

## Buttons

-  `.btn` – Base button.
-  `.btn:hover` – Hover effect.
-  `.btn.secondary` – Secondary style.
-  `.btn.secondary:hover` – Hover for secondary button.
-  `.btn.success` – Success style button.
-  `.btn.danger` – Danger style button.
-  `.btn.large` – Large size button.
-  `.btn.small` – Small size button.

## Cards

-  `.card` – Base card style.
-  `.card:hover` – Hover effect.
-  `.card.highlight` – Highlighted card.
-  `.card.compact` – Compact padding card.
-  `.card.spacious` – Spacious padding card.

## Forms

-  `.form-group` – Form wrapper.
-  `.form-group label` – Label styling.
-  `.form-group input` – Input field styling.
-  `.form-group textarea` – Textarea styling.
-  `.form-group select` – Dropdown styling.
-  `.form-group input:focus` – Focus effect on input.
-  `.form-group textarea:focus` – Focus effect on textarea.
-  `.form-group select:focus` – Focus effect on select.

## Responsive Utilities

-  `.hide-mobile` – Hide on mobile devices.
-  `.show-mobile` – Show only on mobile devices.

### `@media (max-width: 768px)`

-  `.hide-mobile` – Applies hiding at this breakpoint.
-  `.show-mobile` – Applies showing at this breakpoint.
-  `.grid` – Adjusted grid layout.
-  `.flex` – Adjusted flex layout.
-  `.flex.mobile-row` – Forces flex row on mobile.
-  `.hero` – Responsive tweaks for hero.
-  `.hero-cta` – Responsive layout for call-to-action.
-  `.hero-btn` – Adjusted button styles.

## Theming

-  `.theme-dark` – Enables dark mode theme.
-  `.theme-dark .card` – Dark styled cards.
-  `.theme-dark .form-group input` – Dark themed input.
-  `.theme-dark .form-group textarea` – Dark textarea.
-  `.theme-dark .form-group select` – Dark dropdown select.

## Profile Pictures

-  `.profile-picture-square`
-  `.profile-picture-square-sm`
-  `.profile-picture-circle`
-  `.profile-picture-circle-sm`

## Floating Elements

-  `.floating` – Floating animation or effect.
-  `@keyframes floating` – Floating keyframe definition.

## Gradients

-  `.gradient-1`
-  `.gradient-2`
-  `.gradient-3`
-  `.gradient-4`

## Animations

### Keyframes

-  `@keyframes fadeIn`
-  `@keyframes fadeInUp`
-  `@keyframes fadeInDown`
-  `@keyframes fadeInLeft`
-  `@keyframes fadeInRight`
-  `@keyframes slideInUp`
-  `@keyframes slideInDown`
-  `@keyframes slideInLeft`
-  `@keyframes slideInRight`
-  `@keyframes scaleIn`
-  `@keyframes scaleInCenter`
-  `@keyframes scaleUp`
-  `@keyframes rotateIn`
-  `@keyframes flipInX`
-  `@keyframes flipInY`
-  `@keyframes bounce`
-  `@keyframes pulse`
-  `@keyframes shake`
-  `@keyframes staggerFadeInUp`

### Animation Classes

-  `.anim-fadeIn`
-  `.anim-fadeInUp`
-  `.anim-fadeInDown`
-  `.anim-fadeInLeft`
-  `.anim-fadeInRight`
-  `.anim-slideInUp`
-  `.anim-slideInDown`
-  `.anim-slideInLeft`
-  `.anim-slideInRight`
-  `.anim-scaleIn`
-  `.anim-scaleInCenter`
-  `.anim-rotateIn`
-  `.anim-flipInX`
-  `.anim-flipInY`
-  `.anim-bounce`
-  `.anim-pulse`
-  `.anim-shake`
-  `.anim-fast` – Fast animation.
-  `.anim-slow` – Slow animation.
-  `.anim-slower` – Slower animation.
-  `.anim-delay-1` to `.anim-delay-5` – Delays from 1 to 5.

### Hover Animations

-  `.hover-scaleUp`
-  `.hover-scaleUp:hover`
-  `.hover-pulse`
-  `.hover-pulse:hover`
-  `.hover-pulse:not(:hover)`

### Stagger Animations

-  `.stagger-container > *:nth-child(1)` through `.stagger-container > *:nth-child(6)` – Staggered animations by order.

### **Forms (Additional Input Group System)**

#### Input Group System

-  `.input-group` – Wrapper around form controls for enhanced UX.
-  `.input-field` – Input with floating label behavior.
-  `.input-field:focus` – Triggers label and underline changes.
-  `.input-field:valid + .input-label` – Keeps label floated on valid input.
-  `.input-label` – Floating label for inputs.
-  `.input-group::after` – Underline element.
-  `.input-field:focus ~ .input-group::after` – Focus animation for underline.
-  `.input-group:focus-within::after` – Alternate focus trigger for underline.
-  `.input-group.success`, `.input-group.error`, `.input-group.warning` – State variants.
-  `.input-group.success .input-field:focus`, etc. – Adjust label and underline styles based on validation state.

---

### **Navbar**

## Navbar

-  `.navbar` – Navbar wrapper.
-  `.navbar-logo` – Logo container.
-  `.navbar-menu` – Main nav links container.
-  `.navbar-menu a` – Individual nav links.
-  `.navbar-menu a:hover` – Hover style for nav links.
-  `.navbar-toggle` – Toggle icon for mobile nav.
-  `.navbar-toggle span` – Hamburger lines.
-  `.navbar-menu-mobile` – Mobile-specific menu.
-  `.navbar.open .navbar-menu-mobile` – Mobile nav in open state.

**Responsive (@media max-width: 768px):**

-  `.navbar-menu` – Responsive behavior.
-  `.navbar-toggle` – Display toggle icon on mobile.
-  `.navbar.open .navbar-menu-mobile` – Shows the mobile nav menu.

---

## Code Blocks

-  `.code-block` – Container for styled code display.
-  `.code-block:hover` – Hover state with enhancements.
-  `.code-block-header` – Header above code (e.g., with language or actions).
-  `.code-block-header::before` – Decorative element.
-  `.code-block-language` – Language label.
-  `.code-block-actions` – Action buttons container (e.g., copy).
-  `.code-block-content` – Scrollable content wrapper.
-  `.code-block-content::before` – Visual embellishment for content area.
-  `.code-block pre` – Preformatted text container.
-  `.code-block code` – Inline code styling.
-  `.code-block-content::-webkit-scrollbar` – Custom scrollbar styling.
-  `.code-block-content::-webkit-scrollbar-track` – Scrollbar track.
-  `.code-block-content::-webkit-scrollbar-thumb` – Scrollbar thumb.
-  `.code-block-content::-webkit-scrollbar-thumb:hover` – Hover effect for thumb.

**Responsive:**

-  `.code-block`, `.code-block-header`, `.code-block-content`, `.code-block pre` – Mobile layout adjustments.

---

### **Utility / Miscellaneous**

#### Text

-  `.text-white` – Applies white text color.
