# Homework 1
In this assignment, I was tasked to refactor existing code to meet specific criteria and to make it more accesible.

Website Snapshot

=================
![Image](chrome_vGiqS64eLn.png)

## User Story
```
AS A developer
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Criteria

```
GIVEN a webpage meets accessibility standards

- IF source code
-> THEN semantic HTML elements

- IF HTML elements
-> THEN elements follow a logical structure 

- IF image elements
-> THEN accessible alt attributes included

- IF heading attributes
-> THEN sequential 

- IF I  title element
-> THEN concise, descriptive title
```

### Improvements:
1. Ensured links function correctly
2. Cleaned up CSS to make more efficient
3. Consolidated CSS selectors and properties
4. Organiged CSS to follow Semantic stucture of the HTML elements
5. Included comments throughout

### Code Snippet 
- Includes comments that show changes and create structure
- Shows semantic HTML elements that show logical structure
- Added accessability features

```
<!-- ************************ -->
<!-- ******* Content ******** -->
<!-- ************************ -->

<!-- CHANGED: div for article  -->
<article class="content">
    <!-- REMOVED: class="search-engine-optimization" -->
    <!-- ADDED: class="content-box" -->
    <div class="content-box">

        <!-- ADDED: alt tag -->
        <img src="./assets/images/search-engine-optimization.jpg" 
        class="float-left" alt="Notebook with SEO characteristics"/>

        <h2>Search Engine Optimization</h2>

        <p>
            The dominance of mobile internet use means that users are 
            searching for the right business as they travel, shop, 
            or sit on their couch at home. 
            Search Engine Optimization (SEO) allows you to increase 
            your visibility and find the right customers for your 
            business.
        </p>
    </div>

```

 ## Technologies Used
- HTML - used to create elements on the DOM
- CSS - styles html elements on page
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed to GitHub Pages

### Author links
[LinkedIn](https://www.linkedin.com/in/nadine-bundschuh-731233b9)
[GitHub](https://github.com/nadineb1160)

