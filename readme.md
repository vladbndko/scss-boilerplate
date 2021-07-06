## Content

### Backgrounds:
**css class**: `bg-{?breakpoint}-{color-name}-{saturation}` <br>
**variables**: `share/colors.scss` <br>
**examples**: `bg-primary-500`, `bg-md-secondary-900`, `bg-xl-gray-100`

### Spacing
**css class**: `{m|p}{?t|b|l|r|y|x|auto}-{?breakpoint}-{0-10}` <br>
**value**: `1 === 5px, 10 === 50px` <br>
**examples**: `mt-5`, `mx-auto`, `py-10`, `mb-sm-0`, `pl-xl-6`

### Color:
**css class**: `text-color-{?breakpoint}-{color-name}-{saturation}` <br>
**variables**: `share/colors.scss` <br>
**examples**: `text-color-primary-500`, `text-color-xl-danger-900`

### Font sizes:
**css class**: `font-size-{?breakpoint}-{1-8}` <br>
**variables**: `share/variables.scss` in `$font-sizes` <br>
**examples**: `font-size-5`, `font-size-md-1`

### Font weights:
**css class**: `font-weight-{?breakpoint}-{400|600|700}` <br>
**variables**: `share/variables.scss` in `$font-weights` <br>
**examples**: `font-weight-400`, `font-weight-sm-700`

### Align
**css class**: `text-align-{?breakpoint}-{left|center|right|justify}` <br>
**examples**: `text-align-center`, `text-align-xl-right`

### Other:
`lowercase`, `uppercase`, `capitalize`, `text-truncate`, `text-nowrap`, `font-primary`, `font-secondary`

### Buttons:
**css class**: `button is-{style}-{?soft|outline} {?is-small|is-large} {?is-loading} {?is-icon}` <br>
**variables**: `share/variables.scss` in `Buttons section` <br>
**examples**: `button is-primary`, `button is-secondary-outline is-large is-loading`
