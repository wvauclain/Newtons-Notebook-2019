# Newton's Notebook LaTeX Style Guide

## Fractions

### Math Mode

When used in a display math block, fractions should be displayed using `\frac`, which displays an upright fraction. The negative sign should always be displayed in front of the fraction instead of inside the numerator, as it looks better and prevents the numerator from being pushed to the side by the extra character.

### Text Mode

When fractions are embedded in text, `\nicefrac` from the 'units' package should be used, which displays diagonal fractions. The negative signs in these fractions should be contained in the numerator because `\nicefrac` handles the alignment of the negative sign better that way so it looks better. Additionally, each fraction in text mode should be prefixed by a non-breaking space (`~`), like this: `equal~$\nicefrac{1}{2}$`. This prevents the line from wrapping between the fraction and the word before it, increasing readability.

## Variables

When referencing variables in text, the names should always be inside inline math blocks like this: `\[S\]`. This italicizes the variable and makes it clearer that we are referring to a symbol. Importantly, this is require for any type of greek letter or subscript or any other math notation, so it is more consistent if even simple variable names are referred to this way.
