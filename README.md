# Planning our application
  1. Answer Questions 
      - What are you building?
      - Who are you building it for?
      - What features pages do you need to have?
  2. User stories
  3. Model our data

## Questions
  1. What are you building? 
      -The main purpose of the site is to showcase my personal work, and generate conversation surrounding it via blog posts. Ultimately, the goal of the site is to show potential employers the skills and passion I have for web development and design. 
  2. What features would you like to have?
      - Posts
          - CRUD actions
          - Markdown
          - Syntax Highlighting
          - Comments (Disqus)
       - Projects
          - CRUD actions
       - Contact
          - Contact form
          - Sendgrid
       - Photography
          - File uploading
          - Fullscreen slideshow
          - Ranking system
## How will you model the data
        - Articles
           - title:string
           - content:string
        - Projects
           - title:string
           - description: text
           - content:string
        - Photography
            - title:string
## Outline the pages needed for your app
        - Home
        - Posts#index
        - Posts#show
        - Projects#index
        - Projects#show
        - Photography#index
        - Photography#show
        - Contact

## User Auth (Devise)


