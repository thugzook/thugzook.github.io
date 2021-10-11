# Noah Chong Portfolio Website
## Dependencies
* Jekyll
* TailwindCSS
* PostCSS
* ... Node

## File Structure
### _layouts
* default
* blog
### _data
* Holds dictionary of values, including the navbar
### _includes
* Page components
    * Navbar
### _posts
* Blog posts

## Local Development
* run `jekyll serve`
* https://medium.com/swlh/building-a-personal-coding-portfolio-website-60ccc6137f3

## Updating custom font
* `npx tailwindcss build -i ./assets/styles/tailwind.css -o ./assets/tailwind.css -c ./tailwind.config.js`