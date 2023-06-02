# Bootstrap modify
## // scss-docs-start theme-color-variables
- $primary:       #f18724 !default;
- $secondary:     $gray-600 !default;
- $success:       $green !default;
- $info:          $cyan !default;
- $warning:       $yellow !default;
- $danger:        $red !default;
- $light:         $gray-100 !default;
- $dark:          $gray-900 !default;
- $black-0 :    #ffffff;
- $black-20 :   #f2f2f2;
- $black-40 :   #d1d1d1;
- $black-60 :   #919191;
- $black-80 :   #525252;
- $black-100 :  #020202;
- // scss-docs-end theme-color-variables

## // scss-docs-start theme-colors-map
- $theme-colors: (
  - "primary":    $primary,
  - "black-0": #ffffff,
  - "black-20": #f2f2f2,
  - "black-40": #d1d1d1,
  - "black-60": #919191,
  - "black-80": #525252,
  - "black-100": #020202,
  - "secondary":  $secondary,
  - "success":    $success,
  - "info":       $info,
  - "warning":    $warning,
  - "danger":     $danger,
  - "light":      $light,
  - "dark":       $dark
- ) !default;
- // scss-docs-end theme-colors-map

## // scss-docs-start spacer-variables-maps
- $spacer: 1rem !default;
- $spacers: (
  - d25: 0.25rem,
  - d5: 0.5rem,
  - d625: 0.625rem,
  - d75: 0.75rem,
  - 1: 1rem,
  - 1d25: 1.25rem,
  - 1d5: 1.5rem,
  - 2: 2rem,
  - 2d25: 2.25rem,
  - 2d5: 2.5rem,
  - 3: 3rem,
  - 3d75: 3.75rem, // 60
  - 5: 5rem,
  - 6d25: 6.25rem,
  - 7d5: 7.5rem,
  - 10: 10rem,
- ) !default;
 
## // Settings for the `<body>` element.
- $body-bg:                   $white !default;
- $body-color:                #020202 !default;
- $body-text-align:           null !default;


## // scss-docs-start border-radius-variables
- $border-radius:               1rem !default; // rounded & rounded-2
- $border-radius-sm:            .2rem !default; // rounded-1
- $border-radius-lg:            10rem !default; // rounded-3
- $border-radius-pill:          50rem !default; // rounded-pill
- // scss-docs-end border-radius-variables