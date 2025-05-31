# Literary Comparator Widget

This project is a simple web widget that allows users to compare two authors. It constructs a detailed prompt based on the provided author names and opens a new tab to `grok.com` to generate a literary comparison.

## How to Use

1.  Open the `index.html` file in your web browser.
2.  You will see two input fields labeled "Autor 1" and "Autor 2".
3.  Enter the names of the two authors you wish to compare in these fields.
4.  Click the "Comparar" button.

## Functionality

-   The widget takes the two author names entered by the user.
-   It validates that both fields are filled and that the author names are different.
-   If the inputs are valid, it constructs a comprehensive prompt for a literary comparison. This prompt asks for:
    -   Historical and social context.
    -   Recurrent themes.
    -   Narrative style and literary resources.
    -   Most representative works.
    -   Similarities and differences.
    -   Legacy and influence.
-   Finally, it opens a new browser tab with `https://grok.com/` and passes this detailed prompt as a query.

## Technologies Used

-   HTML
-   CSS
-   JavaScript (vanilla)

## How to Run

1.  Clone or download this repository.
2.  Navigate to the project directory.
3.  Open the `index.html` file in any modern web browser.
