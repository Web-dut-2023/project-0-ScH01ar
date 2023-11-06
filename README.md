[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12744455&assignment_repo_type=AssignmentRepo)

# Project0-2021

## Specification

Your website must meet the following requirements:
Your website should have at least three pages: one for regular Google Search (which must
be called( index.html ), one for Google Image Search, and one for Google Advanced Search.
On the Google Search page, there should be links in the upper-right of the page to go to Image Search or Advanced Search. On each of the other two pages, there should be a link in the upper-right to go back to Google Search.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Search</title>
  </head>
  <body>
    <form action="https://www.google.com/search">
      <input type="text" name="q" />
      <input type="submit" value="Google Search" />
    </form>
  </body>
</html>
```

On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page.
Like Google’s own, your search bar should be centered with rounded corners. The
search button should also be centered, and should be beneath the search bar.
On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own advanced search options)
Find pages with... “all these words:”
Find pages with... “this exact word or phrase:”
Find pages with... “any of these words:” Find pages with... “none of these words:”
Like Google’s own Advanced Search page, the four options should be stacked vertically, and all of the text fields should be left aligned.
Consistent with Google’s own CSS, the “Advanced Search” button should be blue with
white text.
When the “Advanced Search” button is clicked, the user should be taken to the search results page for their given query.
Add an “I’m Feeling Lucky” button to the main Google Search page. Consistent with Google’s own behavior, clicking this link should take users directly to the first Google search result for the query, bypassing the normal results page.
You may encounter a redirect notice when using the “I’m Feeling Lucky” button. Not to
worry! This is an expected consequence of a security feature implemented by Google. The CSS you write should resemble Google’s own aesthetics.
