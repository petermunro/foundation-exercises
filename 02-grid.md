# Foundation UI Exercises


## Getting to know the Grid

1. Open [foundation-4-example/01-four-items.html](foundation-4-example/01-four-items.html) in a browser.
   It starts like this:

    ```
    <div class="row">
    
        <div class="large-3 small-12 columns">
            <div class="panel">
                <p>One</p>
            </div>
        </div>
        <div class="large-3 small-12 columns">
            <div class="panel">
                <p>Two</p>
            </div>
        </div>
        <div class="large-3 small-12 columns">
            <div class="panel">
                <p>Three</p>
            </div>
        </div>
        ...
    </div>
    ```

1. View the HTML and notice these elements:

    ```
    <div class="large-3 small-12 columns">
    </div>
    ```

1. Now, take in these concepts:
    1. The number of columns is _always_ 12 (no matter the device).
    1. The class `large-3` means:
        - on a _large_ device, I will take up 3 columns (1/4 of the screen width)
    1. The class `small-12` means:
        - on a _small_ device, I will take up 12 columns (the full width of the screen)

1. Resize the browser and see how this is true.
   On a small screen, items are the full 12 columns so end up stacked;
   on a large screen, they take up 3 columns so fit four to a row.

1. Further concepts:
    1. After every column declaration, there is the class `columns`
    1. Every set of columns lives in a surrounding `row`

## Your Turn

Create a layout that has 16 cells:
    - on a _small_ screen they appear as 2 columns, each of 8 cells
    - on a _large_ screen they appear as 4 columns, of of 4 cells


## Centering Grid Items

To center grid elements (not their contents),
use `small-centered` or `large-centered`.

- Note that a `small-centered` will carry over to a large screen too.
To swiitch this off, use `large-uncentered`.

1. Create a layout with 4 items, centered horizontally.

## Offsetting the Grid (Manipulating Column Positions)

You can leave 'gaps' in the grid using (for example) `large-offset-2`,
which leaves empty space for a width of 2 items.

1. Modify your layout so that on a small screen,
   no gaps are visible, but on a large screen,
   gaps exist between items.


