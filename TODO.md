# TODO: Implement the Kickstarter web scraper

## Step 1: Implement create_project_dict() function
- [x] Use BeautifulSoup to parse fixtures/kickstarter.html
- [x] Select all projects using "li.project.grid_4" selector
- [x] Extract: title, image_link, description, location, percent_funded
- [x] Build nested dictionary structure

## Step 2: Test the implementation
- [x] Run the scraper to verify it works
- [x] Check output structure matches requirements

## CSS Selectors to use:
- Projects: "li.project.grid_4"
- Title: "h2.bbcard_name strong a"
- Image Link: "div.project-thumbnail a img" (src attribute)
- Description: "p.bbcard_blurb"
- Location: "ul.project-meta span.location-name"
- Percent Funded: "ul.project-stats li.first.funded strong"

