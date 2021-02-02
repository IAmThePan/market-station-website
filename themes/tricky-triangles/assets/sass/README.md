# Goals for the CSS/SCSS/SASS

1. The #1 Priority is readability.
  - CSS should not be too closely coupled to the HTML
  - Opt to have near-duplicate HTML over too many CSS conditions
  - Define styling even if it is hidden under normal conditions &
    use complicated nested definitions only to switch properties on/off
  - Use @media queries only to switch properties on/off
  - Lean on SASS variables to implement a theme


There are two ways to use variables throughout this theme:
1. (Recommended) Duplicate this file in the project's directory:
    `project-name/assets/sass/variables.sass`
  Make changes to the file in the project directory, leave the file in the theme directory unchanged.
  Hugo will use the project defined variables.sass file instead of the one in the theme directory.
    Hugo's Lookup Order: https://gohugo.io/templates/lookup-order/
2. Make changes to this file directly.
  Not recommended as you will be making changes to the theme's sourcecode
  which may cuase errors when trying to `git pull` from the theme's repository.
