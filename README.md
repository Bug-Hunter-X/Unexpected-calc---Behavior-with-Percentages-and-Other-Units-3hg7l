# Unexpected calc() Behavior with Percentages and Other Units in CSS

This repository demonstrates a bug encountered when using the `calc()` function in CSS to combine percentages and other units (like pixels). The calculated value is inconsistent across browsers or doesn't produce the expected result.

The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` file provides a potential workaround or demonstrates the correct usage.

## Steps to Reproduce

1. Open `bug.html` in your browser.
2. Observe the unexpected layout or sizing of the element.

## Potential Solutions

The solution might involve:

* Using only one unit type within the `calc()` function.
* Adjusting the values to ensure correct calculation.
* Using a different approach altogether to achieve the desired layout.

This issue highlights the potential complexities of using `calc()` and the importance of thorough testing and understanding its limitations.