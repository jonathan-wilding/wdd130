# WDD 130 - Web Design Fundamentals
BYU-Idaho Spring 2026

A collection of web design projects built while learning HTML and CSS 
fundamentals.

## Projects

- **Apostle Spotlight** - Converted a wireframe concept into working 
  HTML and CSS, including hover effects on images.
- **Flags** - Practiced CSS Grid to build different color/layout 
  configurations.
- **Gallery** - Compressed and optimized images to reduce file size 
  and improve page load speed.
- **Prophet Cards** - Converted a wireframe into working HTML and CSS, 
  including a hover effect on the card image.
- **Signup** - Practiced styling HTML form elements around pre-written 
  JavaScript provided by the assignment. JavaScript itself is covered 
  later in WDD 131, so this project's focus was observing how the 
  existing JS behavior interacted with the HTML/CSS I wrote, not 
  writing JS myself.
- **CSS Positioning** - Practiced CSS Grid alignment across several 
  different layouts.
- **Father's Day** - Focused on CSS styling and hover effects to give 
  the page a distinct visual identity.
- **Favorite Devotional** - Built forms and tables to collect and 
  display data; added a custom feature to mark an entry as an 
  "All-Time Favorite."
- **White Water Rafting Site** - Built a multi-page site with HTML 
  and CSS. After my TA flagged a styling issue, I debugged two 
  separate path-related bugs:
  - A `<link>` tag pointing to a lowercase `styles/style.css` path 
    when the real folder was `Styles/` (capital S).
  - Every `<img>` tag pointing to a lowercase `images/` path when the 
    real folder was `Images/` (capital I).
  
  Both bugs worked fine locally on Windows (which ignores 
  capitalization in file paths) but broke once published to GitHub 
  Pages, which runs on a case-sensitive server. Tracing both bugs 
  taught me to always verify a site's actual deployed behavior, not 
  just how it looks when tested locally.

## Note on earlier bugs

This README was written before I started using Claude or properly 
tracking my work on GitHub, so the smaller bugs I hit in the earlier 
projects (Apostle Spotlight, Flags, Gallery, etc.) aren't documented - 
I don't have a clear memory of the specifics anymore. That gap is 
part of why I started keeping detailed commit messages and README 
notes going forward: a bug you don't write down is a bug you can't 
talk about clearly six months later.

## Live Site
jonathan-wilding.github.io/wdd130/
