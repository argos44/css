# css
http://mountaincat.atwebpages.com/news.html

in this website, the news.html is calling a news.css, where backgound color is defined, but it is not that which is displayed, but rather the backround color of the css invoked from index.html

so, news.html inherits teh css properties of the parent, index.html, though the background image of news.html is altered by the defined background color in it's respective css (news.css)

the opacity factor in news.css has nothing to do with this, it slightly changes the color effect of news.html backround color defined in index.html, and redefined in news.css

so, it seems, that there is a priority of sort, or a mixing of the inherited default background color defined in the respective css of index.html (mcat.css), and the color of the child html of the main html, that is, index.html, which is the main html, or root html, and news.html is it's child.


there is also minimal php code but it is just a newline, and the dates

oh sorry, not exactly... just had to delete cache from browser history... :)
