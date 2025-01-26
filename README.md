# Tailwind CSS Custom Color Not Applying Bug

This repository demonstrates a common issue when working with custom colors in Tailwind CSS:  the color not being applied correctly.  The bug is caused by an inconsistency between the color definition in `tailwind.config.js` and its usage in the HTML.

## Bug Description
A custom color, `custom-color`, is defined in `tailwind.config.js`, but it does not appear in the HTML element with the class `bg-custom-color`. This might be due to typos, incorrect paths, or a misunderstanding of how to define and use custom colors.

## Solution
The solution involves carefully reviewing the `tailwind.config.js` to make sure your custom color is accurately defined. Double-check the casing and spelling of the color name in both the configuration file and the HTML.  Also, make sure you've correctly configured your `content` array in the `tailwind.config.js` to ensure that your HTML file is being processed.
