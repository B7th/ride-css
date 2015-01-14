#ride-placeholders

This mixin will yeld a set of placeholders.

The list:

```
  $block
    display: block
  $bold
    font-weight: 700
  $bolder
    font-weight: 900
  $code-font
    font-family: monospace,serif
    font-size: 1em
  $font-100
    font-weight: 100
  $font-300
    font-weight: 300
  $font-400
    font-weight: 400
  $font-600
    font-weight: 600
  $font-700
    @extend $bold
  $font-900
    @extend $bolder
  $inline-block
    display: inline-block
  $none
    display: none
  $normal
    @extend $font-400
  $pointer
    cursor: pointer
  $table
    display: table
    $cell
      display: table-cell
    $row
      display: table-row
  $table-cell
    display: table-cell
  $table-row
    display: table-row
  $thin
    @extend $font-300
  $thinner
    @extend $font-100
  $above-the-fold
    ride-absolute-page: 0
  $below-the-fold
    ride-absolute-page: 1
  $button
    @extend $inline-block
    @extend $pointer
  $full-background
    background-size: cover
    background-position: center
    background-repeat: repeat-none
  $level-0
    z-index: 0
  $level-1
    z-index: 10
  $level-2
    z-index: 20
  $level-3
    z-index: 30
  $level-4
    z-index: 40
  $level-5
    z-index: 50
  $modal-like
    box-sizing: border-box
    fixed: top 0 left 0
    full-size: 100%
  $no-margin
    margin: 0
  $no-padding
    padding: 0
  $no-horizontal-margin
    margin-horizontal: 0
  $no-vertical-margin
    margin-vertical: 0
  $no-horizontal-padding
    padding-horizontal: 0
  $no-vertical-padding
    padding-vertical: 0
```