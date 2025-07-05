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

-  `.danger-box` – Box styled to indicate danger or error (usually red).

-  `.success-box` – Box styled to indicate success (usually green).

-  `.info-box` – Box styled to show informational messages.

-  `.page` – Wrapper for page-level container.

-  `.container` – Central layout container.

-  `.container.narrow` – Restricts container width to a narrow layout.

-  `.container.wide` – Expands container to a wider layout.

## Sections

-  `.section` – Content section wrapper.
-  `.section.compact` – Section with reduced padding.
-  `.section.spacious` – Section with increased padding.

## Spacing Utilities

### Padding Top (`pt-`)

-  `.pt-1` to `.pt-10` – Adds increasing top padding from 1 to 10 units.

### Padding Bottom (`pb-`)

-  `.pb-1` to `.pb-10` – Adds increasing bottom padding from 1 to 10 units.

### Padding Left (`pl-`)

-  `.pl-1` to `.pl-10` – Adds increasing left padding from 1 to 10 units.

### Padding Right (`pr-`)

-  `.pr-1` to `.pr-10` – Adds increasing right padding from 1 to 10 units.

### Padding Horizontal (`px-`)

-  `.px-1` to `.px-10` – Adds increasing horizontal padding (left & right).

### Padding Vertical (`py-`)

-  `.py-1` to `.py-10` – Adds increasing vertical padding (top & bottom).

## Hero Components

-  `.hero` – Main hero section container.
-  `.hero::before` – Pseudo-element for background or overlay styling.
-  `.hero-content` – Container for hero text and elements.
-  `.hero-title` – Styling for main hero heading.
-  `.hero-subtitle` – Styling for hero subtitle text.
-  `.hero-cta` – Container for call-to-action buttons in hero.
-  `.hero-btn` – Base button styling inside hero.
-  `.hero-btn--primary` – Primary styled hero button.
-  `.hero-btn--primary:hover` – Hover state for primary hero button.
-  `.hero-btn--secondary` – Secondary styled hero button.
-  `.hero-btn--secondary:hover` – Hover state for secondary hero button.
-  `.hero[data-colors]` – Hero with customizable color properties.

### Hero Color Variants

-  `.hero-red`
-  `.hero-green`
-  `.hero-purple`
-  `.hero-orange`
-  `.hero-pink`
-  `.hero-teal`
-  `.hero-dark`

## Quotes

-  `.quote` – Styles blockquotes or quote elements.
-  `.quote:hover` – Hover state for quote.
-  `.quote::before` – Decorative quote mark or icon.

## Spacing Between Elements

-  `.space > * + *` – Adds default spacing between direct children.
-  `.space.tight > * + *` – Reduced spacing between children.
-  `.space.loose > * + *` – Increased spacing between children.
-  `.space.huge > * + *` – Very large spacing between children.

## Buttons

-  `.btn` – Base button styling.
-  `.btn:hover` – Hover effect on button.
-  `.btn.secondary` – Secondary button style.
-  `.btn.secondary:hover` – Hover state for secondary button.
-  `.btn.success` – Success (green) button style.
-  `.btn.danger` – Danger (red) button style.
-  `.btn.large` – Large button size.
-  `.btn.small` – Small button size.

## Cards

-  `.card` – Base card style.
-  `.card:hover` – Hover effect on card.
-  `.card.highlight` – Highlighted card appearance.
-  `.card.compact` – Compact card with less padding.
-  `.card.spacious` – Spacious card with more padding.

## Forms

-  `.form-group` – Wrapper for form fields.
-  `.form-group label` – Styles form labels.
-  `.form-group input` – Styles input fields.
-  `.form-group textarea` – Styles textareas.
-  `.form-group select` – Styles select dropdowns.
-  `.form-group input:focus` – Focus style for inputs.
-  `.form-group textarea:focus` – Focus style for textareas.
-  `.form-group select:focus` – Focus style for selects.

## Responsive Utilities

-  `.hide-mobile` – Hides elements on mobile.
-  `.show-mobile` – Shows elements only on mobile.

## Media Queries

### `@media (max-width: 768px)`

-  `.hide-mobile` – Hides on small screens.
-  `.show-mobile` – Shows on small screens.
-  `.grid` – Adjusts grid for mobile.
-  `.flex` – Adjusts flex for mobile.
-  `.flex.mobile-row` – Forces flex direction to row on mobile.
-  `.hero` – Responsive adjustments for hero section.
-  `.hero-cta` – Responsive hero CTA container.
-  `.hero-btn` – Responsive hero buttons.

## Theming

-  `.theme-dark` – Applies dark theme styles globally.
-  `.theme-dark .card` – Dark-themed cards.
-  `.theme-dark .form-group input` – Dark-themed inputs.
-  `.theme-dark .form-group textarea` – Dark-themed textareas.
-  `.theme-dark .form-group select` – Dark-themed selects.

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
-  `.anim-fast` – Fast animation speed.
-  `.anim-slow` – Slow animation speed.
-  `.anim-slower` – Slower animation speed.
-  `.anim-delay-1` to `.anim-delay-5` – Animation delays from shortest to longest.

### Hover Animations

-  `.hover-scaleUp:hover` – Scales element up on hover.
-  `.hover-pulse:hover` – Pulses element on hover.

### Stagger Animation Helpers

-  `.stagger-container > *:nth-child(1)` through `.stagger-container > *:nth-child(6)` – Apply stagger delays for children.

## Demo Components

-  `.demo-section` – Container for demo content.
-  `.demo-section h2` – Heading style inside demo section.
-  `.color-demo` – Displays color swatches or palettes.

## Gradients

-  `.gradient-1`
-  `.gradient-2`
-  `.gradient-3`
-  `.gradient-4`
