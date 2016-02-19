# Foundation UI Exercises

## Setting Element Position

The order of the elements in HTML is called the 'source' ordering.
Sometimes, you want an element to move depending on screen size.
You can simply "push" or "pull" it a specified number of columns.

- The `.push-6` class moves an element 6 columns to the right
- The `.pull-4` class moves an element 4 columns to the left

1. Move the item containing panel One 6 columns to the right on a
   small screen.


    ```
	<div class="row">

		<div class="large-4 small-6 small-centered columns">
			<div class="panel">
				<p>One</p>
			</div>
		</div>
		<div class="large-4 small-6 small-centered columns">
			<div class="panel">
				<p>Two</p>
			</div>
		</div>
		<div class="large-4 small-6 small-centered columns">
			<div class="panel">
				<p>Three</p>
			</div>
		</div>

	</div>
    ```


