# Protfolio Refactor


## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```


## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

# Steps Needed

- Replace the divs with the semantic HTML elements.
   - Header, nav, section
- Add alt tags to the images



# Setting Up Git

```bash
git init # Create a repository
git add . # Store all the files. BE CAREFUL. It means ALL. 
git commit -m "First commit" # Take a snapshot 
git status # CHeck the Current status
git log # Show the commits 
# We get these from Github because we want to be able to push our local Git repo to Github
git remote add origin git@github.com:TerrellJ504/week-one-homework.git # Add a link to push to
git branch -M main # Set the main branch to main
git push -u origin main # Push to the main branch
```



