# Analyzing My Website Theme: Bootstrap Clean Blog
## Lines 1 - 2
&lt;!DOCTYPE html&gt; &lt;html lang="en"&gt;
### Mark the beginning of the html landing page and chose english as the language of choice.
## Lines 3 - 17
 &lt;head&gt; &lt;meta&gt; &lt;title&gt; &lt;link&gt; &lt;script&gt;
### Make up the head of the document in which you can find the meta data of the website such as character set, page description, keywords, author of the document, and viewport settings. This information is used is used by browsers, search engines (keywords), and other web services.
### The title tag shows in the page's tab, it also provides a title for the page when it is added to favorites and displays a title for the page in search-engine results.
### The link tag inside the head providdes an icon next to the page's tab. and search engines.
### Lines 11 to 14 link to multiple fonts that can be used on the website.
### And the last link before the head tag closes links the CSS style sheet to the Index.html
## Lines 18 - 36
&lt;body&gt; &lt;nav&gt; &lt;div&gt; &lt;a&gt; &lt;button&gt; &lt;i&gt; &lt;ul&gt; &lt;li&gt;
### Create and link the navbar to the top of the index.html and creates buttons to link to other html files such as index.html, about.html, post.html, and contact.html
## Bootstrap shorthand specific examples. For Lines 18 - 36
### The navbar has a "navbar-light" bootstrap element that gives it a light/white background color. It also has a "navbar-expand-lg" element so it can expand everything inside the dropdown element when it's on a desktop or a big enough monitor/screen.
### There is also a container div with shorthand bootstrap of "px-4" where P=Padding so we can use 16px(browsers default root font size) * 4(1.5) that will give us a 24px of padding for X=both the left and right sections of the div.
### Then we have "px-lg-5" which means Padding on the left and right is set to 16px * 5(3) = 48px when we are on a lg display (desktop or bigger display)
### The items inside the navbar have a "ms-auto" element sets the margin on the left side to auto so the browser can define the margin for us.
### Another element for the navbar items is "py-4" giving them a padding of 4 for the top and bottom but if the display is on a lg screen the padding is set to 0.
## Lines 37 - 49
&lt;header&gt; &lt;div&gt; &lt;H1&gt; &lt;span&gt;
### Make up the header of the website by adding a background image an H1 title and a sub heading for the landing page.
## Bootstrap Specific examples for Lines 37 - 49
### we have a container div with a "position-relative" so it can move around depending on its initial position.
### Then we have a "px-4" element that gives this div a padding of bootstrap 4 on the left and right sides for all screens except lg. because we have a "px-lg-5" element that gives larger screen a padding of bootstrap 5 to the sides.
### The second div for the row class has an element of "gx-4" which gives us a horizontal gutter with a padding of 4. but on a lg screen the padding will be 5 because of "gx-lg-5 and then we use some flexbox to justify-content-center and have everything in the middle.
### Then we have the columns. And all columns have different padding depending on the size of the screen. A medium screen has a padding of "col-md-10" 10. For larger screens we have a padding or "col-lg-8" 8. And in this case for screens with a width of 1200px and above we have a padding of "col-xl-7" 7.
## Lines 50 - 111
&lt;div&gt; &lt;a&gt; &lt;H2&gt; &lt;H3&gt; &lt;p&gt; &lt;hr&gt;
### Make up the main content of the website, and inside the main content container we have the post preview divs for the columns which include href tags that link to the post.html articles.
## Bootstrap Specific examples for Lines 50 - 111
### In the main content we have the articles, and these articles are inside a container div with padding for left and right of 4 "px-4" And padding for the left and right of 5 on larger screens "px-lg-5".
### Then we have horizontal row gutters for the articles of padding of 4 "gx-4" and padding of 5 on lg screens "gx-lg-5".
### Then again, we have columns with different padding depending on the size of the screen. A medium screen has a padding of "col-md-10" 10. For larger screens we have a padding or "col-lg-8" 8. And in this case for screens with a width of 1200px and above we have a padding of "col-xl-7" 7.
### The body has paragraph breaks or dividers &lt;hr&gt; with a margin of 4 for the top and bottom "my-4".
### the button has a "d-flex" container that is moved to the right by using "justify-content-end" and has a margin of 4 at the bottom "mb-4"
## Lines 112 - 147
&lt;footer&gt; &lt;div&gt; &lt;ul&gt; &lt;li&gt; &lt;a&gt; &lt;i&gt; &lt;span&gt;
### Make up the footer of the website and adds the icons with some copyright text at the bottom.
## Bootstrap Specific examples for Lines 112 - 147
### The footer has a container div with padding of 4 from left to right "px-4" but on a large screen it has a padding of 5 "px-lg-5".
### Then we have horizontal row gutters for the icons and padding of 4 "gx-4" and padding of 5 on lg screens "gx-lg-5". We also justify things to the middle of the screen with "justify-content-center".
### And for the third time we have columns with different padding depending on the size of the screen. A medium screen has a padding of "col-md-10" 10. For larger screens we have a padding or "col-lg-8" 8. And in this case for screens with a width of 1200px and above we have a padding of "col-xl-7" 7.
### All icons have a "list-inline-item" class to make them responsive with screen size by using font awesome and customizing our icons both in size "fa-lg" or color "fa-inverse".
## Lines 148 - 153
&lt;script&gt; end of &lt;body&gt; end of &lt;html&gt;
### At the end of the html file we have the .JS files that are used for logic on the website. It's a best practice to put these lines of code at the end of the index so the website can load faster.

