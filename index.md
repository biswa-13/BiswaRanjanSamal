### My AR Blogs
- [CP1- HelloAR](https://biswa-13.github.io/BiswaRanjanSamal/AR-Blogs/cp1_helloAR.html)

- Advanced
1. [Geo Location Demo](https://biswa-13.github.io/BiswaRanjanSamal/AR-Blogs/index.html)
2. [Image Marker Demo](https://biswa-13.github.io/BiswaRanjanSamal/AR-Blogs/imageBasedMarkerDemo.html)



### How To convert existing Web App. into Dark Mode by 3 lines of code :
=> Execute below function in your application whenever you want to convert your application into Dark Theme mode, either you can call this on adhoc manner or you can call this on loading of your application or based upon some condition/ user inputs, choice is yours and yes below function is also yours, enjoy :) ...

`code
function setDarkMode(){
    document.documentElement.style.filter = 'invert(1) hue-rotate(180deg)';
    document.body.querySelectorAll('img, picture, video').forEach(el => el.style.filter = 'invert(1) hue-rotate(180deg)');
}
setDarkMode()
`code

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------- Page Editing Instructions ----------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/biswa-13/BiswaRanjanSamal/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/biswa-13/BiswaRanjanSamal/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
