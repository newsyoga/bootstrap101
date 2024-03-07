# Bootstrap basics
## installation
- [installation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## Grid Layout
- screen is divided into 12 units of column
- 6 screen-size breakpoints are defined.
  
  | class | column width | screen size |
  | --- | --- | --- |
  | col-xxl-1 | 1 | xxl |
  | col-xl-2 | 2 | xl |
  | col-lg-3 | 3 | lg |
  | col-md-4 | 4 | md |
  | col-sm-6 | 5 | sm |
  | col-xs-12 | 6 | xs |

## container Layout

  | null |<br>Extra small <576px | Small ≥576px | Medium ≥768px | Large ≥992px | X-Large ≥1200px | XX-Large ≥1400px |
  | --- | --- | --- | --- | --- | --- | --- |
  | `.container`            | 100%          | -          | -         | -            | -            | - |
  | `.container-sm`         | 100%          | -          | -         | -            | -            | - |
  | `.container-md`         | 100%          | 100%           | -         | -            | -            | - |
  | `.container-lg`         | 100%          | 100%           | 100%          | -            | -            | - |
  | `.container-xl`         | 100%          | 100%           | 100%          | 100%             | -            | - |
  | `.container-xxl`        | 100%          | 100%           | 100%          | 100%             | 100%              | - |
  | `.container-fluid`      | 100%          | 100%           | 100%          | 100%             | 100%              | 100% |
  
  example : `container-md` full-width: for-small-screen 
