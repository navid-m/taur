## Global Elements

-  `*` – Applies universal styles like box-sizing and margin reset.
-  `html` – Base HTML element styling, often sets font and background.
-  `body` – Main container styling, typically sets font-family and color.

## Typography

-  `h1` – Styles the largest heading.
-  `h2` – Styles second-level heading.
-  `h3` – Styles third-level heading.
-  `h4` – Styles fourth-level heading.
-  `h5` – Styles fifth-level heading.
-  `h6` – Styles sixth-level heading.
-  `p` – Applies paragraph text styling.
-  `li` – Styles list items with padding or marker tweaks.

## Grid System

-  `.grid` – Enables CSS grid layout.
-  `.grid.dense` – Collapses grid gaps to create denser layout.
-  `.grid.wide` – Expands grid container width.
-  `.grid.cols-2` – Sets two equal-width grid columns.
-  `.grid.cols-3` – Sets three equal-width grid columns.
-  `.grid.cols-4` – Sets four equal-width grid columns.

## Flex Layout

-  `.flex` – Applies flexbox layout.
-  `.flex.column` – Changes flex direction to column.
-  `.flex.center` – Centers items both horizontally and vertically.
-  `.flex.between` – Justifies content with space between.
-  `.flex.around` – Justifies content with space around.
-  `.flex.end` – Aligns content to the end of container.

## Spacing

-  `.space > * + *` – Adds consistent spacing between siblings.
-  `.space.tight > * + *` – Reduces spacing between items.
-  `.space.loose > * + *` – Increases spacing between items.
-  `.space.huge > * + *` – Adds very large spacing between items.

## Buttons

-  `.btn` – Base button styling.
-  `.btn:hover` – Hover style for primary button.
-  `.btn.secondary` – Secondary button variant.
-  `.btn.secondary:hover` – Hover style for secondary button.
-  `.btn.success` – Success state button styling (green or similar).
-  `.btn.danger` – Danger state button styling (red or similar).
-  `.btn.large` – Increases button size.
-  `.btn.small` – Decreases button size.

## Cards

-  `.card` – Base card component styling.
-  `.card:hover` – Adds hover effect to card.
-  `.card.highlight` – Applies emphasis to a card.
-  `.card.compact` – Reduces padding and spacing in card.
-  `.card.spacious` – Adds extra padding/spacing in card.

## Forms

-  `.form-group` – Groups label and input elements.
-  `.form-group label` – Styles form labels.
-  `.form-group input` – Styles input fields.
-  `.form-group textarea` – Styles textareas.
-  `.form-group select` – Styles select dropdowns.
-  `.form-group input:focus` – Focus style for input.
-  `.form-group textarea:focus` – Focus style for textarea.
-  `.form-group select:focus` – Focus style for select.

## Containers

-  `.container` – Central layout container.
-  `.container.narrow` – Restricts container to a narrow width.
-  `.container.wide` – Expands container to full or wide width.

## Sections

-  `.section` – Defines a content section.
-  `.section.compact` – Reduces padding in section.
-  `.section.spacious` – Increases padding in section.

## Responsive Utilities

-  `.hide-mobile` – Hides element on mobile viewports.
-  `.show-mobile` – Shows element only on mobile viewports.

## Media Queries

### `@media (max-width: 768px)`

-  `.hide-mobile` – Hides elements on smaller screens.
-  `.show-mobile` – Shows elements on smaller screens.
-  `.grid` – Adjusts grid layout for mobile.
-  `.flex` – Adjusts flexbox layout for mobile.
-  `.flex.mobile-row` – Forces flex direction row on mobile.

## Theming

-  `.theme-dark` – Applies dark theme styles.
-  `.theme-dark .card` – Dark-themed card.
-  `.theme-dark .form-group input` – Dark input fields.
-  `.theme-dark .form-group textarea` – Dark-themed textareas.
-  `.theme-dark .form-group select` – Dark-themed select dropdowns.

## Animations (Base)

-  `.animate` – Applies a base animation class.
-  `@keyframes fadeInUp` – Keyframe for upward fade animation.
-  `.animate.delay-1` – Adds short delay before animation starts.
-  `.animate.delay-2` – Adds medium delay before animation starts.
-  `.animate.delay-3` – Adds long delay before animation starts.

## Animation Classes

-  `.anim-fadeIn` – Fades in the element from transparent.
-  `.anim-fadeInUp` – Fades in and slides the element upward.
-  `.anim-fadeInDown` – Fades in and slides the element downward.
-  `.anim-fadeInLeft` – Fades in and slides the element from the left.
-  `.anim-fadeInRight` – Fades in and slides the element from the right.
-  `.anim-slideInUp` – Slides the element upward into view.
-  `.anim-slideInDown` – Slides the element downward into view.
-  `.anim-slideInLeft` – Slides the element in from the left.
-  `.anim-slideInRight` – Slides the element in from the right.
-  `.anim-scaleIn` – Scales the element up from zero.
-  `.anim-scaleInCenter` – Scales and centers the element on entry.
-  `.anim-rotateIn` – Rotates the element into view.
-  `.anim-flipInX` – Flips the element along the X axis.
-  `.anim-flipInY` – Flips the element along the Y axis.

## Demo Components

-  `.demo-section` – Container for demonstration or example blocks.
-  `.demo-section h2` – Heading style for demo sections.
-  `.color-demo` – Displays a color palette or color preview.

## Gradients

-  `.gradient-1` – Applies the first gradient style.
-  `.gradient-2` – Applies the second gradient style.
-  `.gradient-3` – Applies the third gradient style.
-  `.gradient-4` – Applies the fourth gradient style.
