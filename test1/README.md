# Goal

You must able to identify the reason of why `<aside>` tag is being pushed on next line.

And must also fix it.

### Note

`<section>` tag must have a width of 75%

`<aside>` tag must have a width of 25%

You must not edit `index.html`

# Expected Output

<img src="https://cdn.glitch.com/7373e19d-cfff-4c35-8ae0-a64502512e61%2Fa33902fd-7b6d-44eb-86ed-9a4505811745.image.png?v=1610011580923">

# Your Answer Here

The issue is with the padding. Adding the padding to the established widths would make it exceed a 100%. Adding the property box-sizing with the value border-box helps account the padding.
