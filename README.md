# **Top 10 Docsify-This Tips for Markdown Publishing**

## Quickly Load a Markdown URL into Docsify-This

- Type `docsify-this.net?` in front of a GitHub, Codeberg, or raw source Markdown file URL that you are viewing to instantly set up the Docsify-This Web Page Builder with that file.  
  For example, https://docsify-this.net/?github.com/hibbitts-design/docsify-this-one-page-course/blob/main/home.md

## Automatic "Edit This Page" Links

- Automatically add a link to your GitHub or Codeberg-hosted content for collaborative editing or access to raw Markdown content, which is customizable using the `edit-link`, `edit-link-text`, or `edit-link-emoji` URL parameters.

## Pre-Configured Web Page Builder (WPB) URLs

- Use pre-configured Web Page Builder URLs to save time and instantly load settings like Sidebar levels or consistent visual styling options.  
  For example https://docsify-this.net/?sidebar=true&maxLevel=3&font-family=Merriweather,Georgia,serif

## Enable Lazy-Load Images

- Improve page performance with the `lazy-load-images` URL parameter for loading images only when they appear in the viewport, which is especially useful for image-heavy content.

## Support Dark Mode Viewing

- Use the `dark-mode` URL parameter to switch to dark mode automatically based on System OS settings.  
  For example, https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&dark-mode=true

## Changing Sidebar Header Levels

- Customize the depth of headers shown in your Sidebar with the `maxLevel` URL parameter for improved navigation on complex pages.  
  For example, https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true&maxLevel=3#/

## Add Footers or Navbars

- Create consistent navigation or footer content across your Docsify-This site with custom Footer and Navbars Markdown files.

## Enable Font Awesome SVG Icons

- Use SVG icons for more HTML styling options with the `svg-icons` URL parameter.
  For example, https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=schedule.md&svg-icons=true

## Integrate Mathematical Formulas and Diagrams

- Built-in support for both Latex and Mermaid to support the display of mathematical formulas and diagrams.

## Embed Markdown Pages into Other Platforms

- Seamlessly integrate and Docsify-This content only pages into other platforms (e.g. LMSs) by visually styling content using URL parameters such as `font-family` and `font-size`.  
  For example, https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=module-01.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&font-size=1&hide-credits=true#

# Bonus Tips

## Advanced Web Page Builder

- Automatically show advanced Web Page Builder options like setting a website logo in the Sidebar or setting detailed rendering preferences using the URL parameter `advanced`. For example, https://docsify-this.net?advanced=true (which you can make a bookmark of).

## Multilingual Sites

- Support multiple languages using subfolders with content in each language, including a custom Sidebar, Navbar and Footers.

## Use Docsify.js.org Markdown Content Markup

-  You can include Docsify-specific markup within your Markdown files, for example:

   ```markdown

   ## Hidden Sidebar Header <!-- {docsify-ignore} -->
   
   ```
## View the Docsify-This ReadMe with Docsify-This

- Did you know you can view the Docsify-This ReadMe.md documentation file with Docsify-This itself? Have easier access to the Docsify-This docs in a second Browser tab!
  [View the Docisfy-This ReadMe Now](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this/main&homepage=README.md&edit-link=https://github.com/hibbitts-design/docsify-this/blob/main/README.md&sidebar=true&browser-tab-title=Docsify-This%20ReadMe&edit-link-text=Suggest%20an%20Edit%20on%20GitHub&maxLevel=4&header-weight=600&zoom-images=true&dark-mode=true)
