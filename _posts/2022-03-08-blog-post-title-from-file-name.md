<noscript><iframe height="0" src="//www.googletagmanager.com/ns.html?id=GTM-NJXWQL" style="display:none;visibility:hidden" width="0"></iframe></noscript>

 <template id="be-nav"></template> 

<nav class="slp-sticky slp-left-0 slp-right-0 slp-top-0 slp-bg-white slp-z-90" id="global-nav" style="z-index: 1000000;"><be-navigation></be-navigation></nav>

<div class="search-box js-search-box"><input class="search-input js-search st-header" placeholder="Search..."> </div>

<div class="blank-header">![Gitlab hero border pattern left svg](/images/home/icons-pattern-left.svg) ![Gitlab hero border pattern right svg](/images/home/icons-pattern-right.svg)

<div class="header-content">

# Handbook Markdown Guide

</div>

</div>

<div id="highlight-tooltip" role="tooltip">[<span class="sr-only">Share on Twitter</span>](#) [<span class="sr-only">Edit this page</span>](#) [<span class="sr-only">Open Web IDE</span>](#)</div>

<div class="wrapper sidebar-layout-wrapper clearfix">

<aside class="tocs-sidebar">

<div class="codeowners">

<div>

#### Maintained by<span class="hidden-md hidden-lg">:</span>

</div>

<div class="codeowners-list">[![Susan Tacker](/images/team/susantacker-crop.jpg "Susan Tacker") ](https://gitlab.com/susantacker) [ ![Diana Logan](/images/team/dianalogan-crop.jpg "Diana Logan") ](https://gitlab.com/dianalogan) [![Kati Paizee](/images/team/katipaizee-crop.jpg "Kati Paizee")](https://gitlab.com/kpaizee) </div>

</div>

##### Contribute to this page

<div>[View source](https://gitlab.com/gitlab-com/www-gitlab-com/blob/master/sites/handbook/source/handbook/markdown-guide/index.html.md) • [Open in Web IDE](https://gitlab.com/-/ide/project/gitlab-com/www-gitlab-com/edit/master/-/sites/handbook/source/handbook/markdown-guide/index.html.md)</div>

</aside>

<div class="container md-page">

1.  You are here:
2.  [Handbook](/handbook/)
3.  Handbook Markdown Guide

<input class="st-handbook" id="search-handbook" placeholder="Search through the handbook...">

<div class="hidden-md hidden-lg">

<div class="codeowners">

<div>

#### Maintained by<span class="hidden-md hidden-lg">:</span>

</div>

<div class="codeowners-list">[![Susan Tacker](/images/team/susantacker-crop.jpg "Susan Tacker") ](https://gitlab.com/susantacker) [ ![Diana Logan](/images/team/dianalogan-crop.jpg "Diana Logan") ](https://gitlab.com/dianalogan) [![Kati Paizee](/images/team/katipaizee-crop.jpg "Kati Paizee")](https://gitlab.com/kpaizee) </div>

</div>

</div>

## On this page

*   [Markdown Style Guide for about.GitLab.com](#markdown-style-guide-for-aboutgitlabcom)
    *   [Blog](#blog)
*   [Headings](#headings)
*   [Paragraphs, breaks, and horizontal lines](#paragraphs-breaks-and-horizontal-lines)
    *   [Wrapping Text](#wrapping-text)
        *   [Regular paragraphs and automatic join](#regular-paragraphs-and-automatic-join)
    *   [Additional breaks](#additional-breaks)
    *   [Horizontal lines](#horizontal-lines)
*   [Emphasis: bold and italic](#emphasis-bold-and-italic)
*   [Links](#links)
    *   [Inline Links](#inline-links)
    *   [Relative links](#relative-links)
    *   [Mailto links](#mailto-links)
    *   [Identifiers](#identifiers)
*   [Lists](#lists)
    *   [Ordered lists](#ordered-lists)
    *   [Unordered lists](#unordered-lists)
    *   [Split lists](#split-lists)
*   [Images](#images)
*   [Diagrams](#diagrams)
    *   [Mermaid](#mermaid)
    *   [PlantUML](#plantuml)
*   [Videos](#videos)
    *   [Display videos from YouTube](#display-videos-from-youtube)
    *   [Display local videos (HTML5)](#display-local-videos-html5)
    *   [Display other videos](#display-other-videos)
    *   [Display multiple videos](#display-multiple-videos)
*   [Table of Contents (ToC)](#table-of-contents-toc)
*   [Tables](#tables)
*   [Collapse](#collapse)
*   [Code blocks](#code-blocks)
    *   [In-line](#in-line)
    *   [Fenced](#fenced)
    *   [Indented](#indented)
    *   [Nested](#nested)
    *   [In lists](#in-lists)
*   [Blockquotes](#blockquotes)
*   [Notes](#notes)
*   [Comments](#comments)
*   [Anchors](#anchors)
*   [Font Awesome](#font-awesome)
    *   [Puzzle Icon](#puzzle)
    *   [Purple GitLab Tanuki](#tanuki-purple)
    *   [Orange GitLab Tanuki](#tanuki-orange)
*   [Classes, IDs, and attributes](#classes-ids-and-attributes)
    *   [Special classes](#special-classes)
        *   [Shadow](#shadow)
        *   [Note](#note)
        *   [Colors](#colors)
        *   [Text Align](#text-align)
*   [Mix HTML + Markdown Markup](#mix-html--markdown-markup)
*   [Mix ERB + Markdown](#mix-erb--markdown)
*   [Colorful sections](#colorful-sections)
    *   [Additional Information](#additional-information)
    *   [Warnings](#warnings)
    *   [Danger](#danger)
    *   [Do's and Don'ts](#dos-and-donts)
    *   [Custom alert panels and alert boxes](#custom-alert-panels-and-alert-boxes)
        *   [GitLab Orange Alert Panel](#gitlab-orange-alert-panel)
        *   [GitLab Orange Alert Box](#gitlab-orange-alert-box)
        *   [GitLab Purple Alert Panel](#gitlab-purple-alert-panel)
        *   [GitLab Purple Alert Box](#gitlab-purple-alert-box)
    *   [GitLab Webcast Alert Box](#gitlab-webcast-alert-box)
*   [Styles](#styles)
*   [Embed documents](#embed-documents)
    *   [Google products](#google-products)
        *   [Google Sheets](#google-sheets)
        *   [Google Slides](#google-slides)
        *   [Google Docs](#google-docs)
    *   [SlideShare](#slideshare)
*   [Embed Tweets](#embed-tweets)
*   [Embed Instagram posts](#embed-instagram-posts)
*   [Embed GitLab Snippets](#embed-gitlab-snippets)
*   [Markdown Editors](#markdown-editors)
*   [Complementary Notes](#tips--tricks)

## Markdown Style Guide for [about.GitLab.com](/)

This style guide is for [about.gitlab.com](/). For styles in the GitLab UI, see the [GitLab Flavored Markdown documentation](https://docs.gitlab.com/ee/user/markdown.html).

This website was generated by [Middleman](https://middlemanapp.com/), a blog-aware Static Site Generator ([SSG](https://www.staticgen.com/)) widely used by web developers. [Markup language](https://en.wikipedia.org/wiki/Markup_language) is part of the structure of any SSG. It is a system to write documents making them somehow syntactically distinguishable from text. [Lightweight markup languages](https://en.wikipedia.org/wiki/Lightweight_markup_language) have a simplified and unobtrusive syntax, designed to be easily written within any text editor. That's what we use to write our content. The majority of SSGs use markdown engines for this purpose. Read through our blog post on [Modern Static Site Generators](/2016/06/10/ssg-overview-gitlab-pages-part-2/) to understand how they work.

For [about.GitLab.com](/) we use [kramdown](http://kramdown.gettalong.org/), which is an advanced Markdown engine with a lot of interesting features that most of the other engines don't have, such as [inline attribute lists](https://kramdown.gettalong.org/syntax.html#inline-attribute-lists) (IALs), which enable easy styling beyond the standard Markdown options.

If you never have written a single line in markdown markup, don't worry, it's easy to learn and even easier to use. You'll probably be surprised how handy it is once you get used to it. And you'll miss it whenever the tech you're using doesn't support markdown.

In most of GitLab text areas you'll find markdown support. Not all of them run with kramdown, so the markup will not behave equally "GitLabwide". For **GitLab.com**, **GitLab CE** and **GitLab EE** text areas, the markdown engine is currently [CommonMarker](https://github.com/gjtorikian/commonmarker). Here you can find the [markdown style guide](https://gitlab.com/help/user/markdown.md) for them.

This guide has been made to make it easier for everyone to use kramdown features and save a lot of time writing content for [about.GitLab.com](/), including handbook pages, website pages, blog posts and everything else within the project [www-GitLab-com](https://gitlab.com/gitlab-com/www-gitlab-com).

There are different possible syntaxes for most of the markups described below, but this guide is to be considered the standard for [about.GitLab.com](/).

**Note:** this document is maintained by the [Technical Writing](../) Team.

### Blog

For our [Blog](/blog/), everything in this guide can be applied. Read through the [Blog Formatting Guidelines](/handbook/marketing/blog#formatting-guidelines) for further information.

* * *

## Headings

<div class="highlight">

    ## Heading h2

    ### Heading h3

    #### Heading h4

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

## Heading h2

### Heading h3

#### Heading h4

</div>

</div>

Notes:

*   We don't use `h1` headings, as they already are displayed on every page as its title, and we should not apply more than one `h1` per page.

    > _When you use a top level heading, or an <h1>, you’re setting up a semantic relationship between that heading and the remainder of the content on a page, describing what it is about. If you then use a second <h1> on the same page, you’re creating some potential confusion, because someone, or a search engine might see that as the ending of the semantic relationship between the content after the first <h1> and the start of this new <h1>._ [SEO Guide](http://www.seobythesea.com/2012/01/heading-elements-and-the-folly-of-seo-expert-ranking-lists/)

*   Always start with `h2` (`##`), and respect the order h2 → h3 → h4\. Never skip the hierarchy level, such as h2 → h4.

    > _The six heading elements, H1 through H6, denote section headings. Although the order and occurrence of headings is not constrained by the HTML DTD, documents **should not skip levels** (for example, from H1 to H3), as converting such documents to other representations is often problematic._ [W3C](https://www.w3.org/MarkUp/html-spec/html-spec_5.html#SEC5.4)

*   Always leave a blank space between the hash `#` and the text next to it, otherwise it won't render properly.
*   For keeping the text clear and the markdown consistent, [jump a line](#jump-a-line) between any heading and its subsequent paragraph.

* * *

## Paragraphs, breaks, and horizontal lines

Regular paragraphs are obtained by just writing text lines. If you hit **enter** between two lines, both lines will be joined into a single paragraph, which is called [wrapping text](/2016/10/11/wrapping-text/#do-wrap-it). But, if you leave a blank line between them, they will split into two paragraphs.

In some Git tools, `diffs` in future MRs may be easier to understand with additional line breaks, however GitLab's web interface as well as many desktop Git tools feature substring change highlighting within lines and side-by-side or similar version comparison so there is no need for artificial line breaks.

### Wrapping Text

Splitting long lines (preferably up to 100 characters) can make it easier to provide feedback on small chunks of text. Do not leave blank spaces after the last word of the line broken within a paragraph, unless you want it to be intentionally broken with a `<br>`.

#### Regular paragraphs and automatic join

<div class="highlight">

    This text is a paragraph.
    This won't be another paragraph, it will join the line above it.

    This will be another paragraph, as it has a blank line above it.

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

This text is a paragraph. This won't be another paragraph, it will join the line above it.

This will be another paragraph, as it has a blank line above it.

</div>

</div>

### Additional breaks

In case you need an additional break (or some extra space between lines), you can simply use the HTML break tag `<br>`, leaving blank lines above and below it:

<div class="highlight">

    Text A
    <!-- blank line -->
    <br>
    <!-- blank line -->
    Text B

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Text A

Text B

</div>

</div>

### Horizontal lines

A sequence of three or more dashes will produce a horizontal line, but let's use always **4** as standard. Leave blank lines after and before it:

<div class="highlight">

    Text
    <!-- blank line -->
    ----
    <!-- blank line -->
    Text

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Text

* * *

Text

</div>

</div>

* * *

## Emphasis: bold and italic

To display bold or italic text, wrap it in 2 stars (for bold) or underscores (for italic). For both italic and bold, wrap it in 3 stars:

<div class="highlight">

    This is **bold** and this is _italic_.

    This is ***bold and italic***.

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

This is **bold** and this is _italic_.

This is **_bold and italic_**.

</div>

</div>

Markdown doesn't natively support underlined text. If necessary you can hardcode it with the HTML tag `ins` (`<ins>underlined text</ins>`), however, it is inadvisable to do so.

* * *

## Links

There are a few different ways to display links with markdown markup, but to keep some standards, let's try to use the following options only.

Important notes:

*   Don't take it as a restrictive rule, but [avoid using meaningless text for links](/handbook/communication/#writing-style-guidelines) as "this article" or "read here." The link text should be meaningful even if taken out of context; this makes the links more useful and accessible for people using screen readers.
*   Check for broken links: [http://www.deadlinkchecker.com/](http://www.deadlinkchecker.com/)

### Inline Links

We'd rather use inline links, such as `[Text to display](link)`, as they are easier to maintain. To make an inline link open in a new tab, you can add {:target="_blank"} to the end. Ex: `[Text to display](link){:target="_blank"}`

### Relative links

Use relative links when referring to links found on [about.gitlab.com](/). For example, a link to our blog handbook should look like this `/handbook/marketing/blog/` and **not** this `https://about.gitlab.com/handbook/marketing/blog/`. Remove everything from the `https` through `about.gitlab.com`, but retain the forward slash after `.com`.

Learn more in the [Markdown Guide](/handbook/style-guide/#links).

For links to GitLab.com or anywhere else you must use the entire link, including the `http:`.

### Mailto links

If you're adding an email address to a page be sure to format your link with `mailto` to avoid creating broken links. For example, `[example@gitlab.com](mailto:example@gitlab.com)`

### Identifiers

When there are **repeated** links across a single page, you can opt for using identifiers.

Place the identifiers at the end of the paragraph (or the section), arranging them in alphabetical order.

<div class="highlight">

    [Text to display][identifier] will display a link.

    [Another text][another-identifier] will do the same. Hover the mouse over it to see the title.

    [This link] will do the same as well. It works as the identifier itself.

    [This link][] (same as above), has a second pair of empty brackets to indicate that the following parenthesis does not contain a link.

    <https://example.com> works too. Must be used for explicit links.

    <!-- Identifiers, in alphabetical order -->

    [another-identifier]: https://example.com "This example has a title"
    [identifier]: http://example1.com
    [this link]: http://example2.com

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

[Text to display](http://example1.com) will display a link.

[Another text](https://example.com "This example has a title") will do the same. Hover the mouse over it to see the title.

[This link](http://example2.com) will do the same as well. It works as the identifier itself.

[This link](http://example2.com) (same as above), has a second pair of empty brackets to indicate that the following parenthesis does not contain a link.

[https://example.com](https://example.com) works too. Must be used for explicit links.

</div>

</div>

Note:

*   Identifiers **are not** case sensitive. They can be single words as `[link]` or `[multiple words too]`.

* * *

## Lists

Both ordered and unordered lists are very straightforward to produce. There are a few ways to produce the same results, but let's stick with the following, again, to maintain some standards.

Always use **3** blank spaces to indent a nested list (to create sub items).

Tip: don't leave blank lines **between the items**, unless you have a reason to do so.

**Important:** always leave a blank line between the paragraph or heading and the subsequent list! If you don't, the list will not render.

### Ordered lists

Ordered lists are pretty easy to create. Couldn't be more intuitive:

<div class="highlight">

    Paragraph:

    1. Item one
       1. Sub item one
       2. Sub item two
       3. Sub item three
    2. Item two

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Paragraph:

1.  Item one
    1.  Sub item one
    2.  Sub item two
    3.  Sub item three
2.  Item two

</div>

</div>

To be practical and avoid errors on the numbers, use "1" for all the items. The markdown engine will output them in the correct order.

<div class="highlight">

    Paragraph:

    1. Item one
       1. Sub item one
       1. Sub item two
    1. Item two
    1. Item three

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Paragraph:

1.  Item one
    1.  Sub item one
    2.  Sub item two
2.  Item two
3.  Item three

</div>

</div>

### Unordered lists

Unordered lists are very easy to create too:

<div class="highlight">

    Paragraph:

    - Item 1
    - Item 2
    - Item 3
       - Sub item 1
       - Sub item 2
    - Item 4

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Paragraph:

*   Item 1
*   Item 2
*   Item 3
    *   Sub item 1
    *   Sub item 2
*   Item 4

</div>

</div>

### Split lists

Let's say, for some reason, you want to split a list in different parts. To do that, use the markup `^` to indicate the end of a list and the beginning of the next:

<div class="highlight">

    - list one - item 1
    - list one - item 2
       - sub item 1
       - sub item 2
    - list one - item 3
    ^
    - list two - item A
    - list two - item B
    ^
    - list three - item _i_
    - list three - item _ii_

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

*   list one - item 1
*   list one - item 2
    *   sub item 1
    *   sub item 2
*   list one - item 3

*   list two - item A
*   list two - item B

*   list three - item _i_
*   list three - item _ii_

</div>

</div>

* * *

## Images

To insert images to your markdown file, use the markup `![ALT](/path/image.ext)`. The path can either be relative to the website, or a full URL for an external image. The supported formats are `.png`, `.jpg`, `.gif`. You might be able to use some `.svg` files too, depending on its structure.

<div class="highlight">

    ![Semantic description of image](/images/path/to/folder/image.png "Image Title")

</div>

You can also use an identifier, as we do for [links](#links):

<div class="highlight">

    ![Semantic description of image][identifier]

</div>

If you want to add a caption to your image, it's easily achieved with:

<div class="highlight">

    ![Semantic description of image](/images/path/to/folder/image.png)*My caption*

</div>

For clickable images, simply wrap the image markup into a [link markup](#links):

<div class="highlight">

    [![Semantic description of image](/images/path/to/folder/image.png "Hello World")*My caption*][about.gitlab.com]

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

[![Semantic description of image](/images/about-gitlab-com.png "Hello World")_My caption_](/)

</div>

</div>

**Important notes:**

*   Apply [shadow](#shadow) to your images!
*   All images must be placed [under `/source/images/`](https://gitlab.com/gitlab-com/www-gitlab-com/tree/master/source/images), in an appropriate directory. Only screenshots and public domain images are permitted.
*   The text inside the square brackets is an image attribute called `ALT`, which stands for _alternative text_. [Including descriptive alt text](https://webaim.org/techniques/alttext/) helps maintain accessibility for every visitor and should always be included with an image. When you add alt text be sure to describe the content and function of an image. In addition to the accessibility benefits, `ALT` is useful for SEO, and it is displayed when, for some reason, that image is not loaded by the browser.
*   For the same reasons, the image must contain a name related to it. Example: instead of `image-01.jpg`, name it `black-dog.jpg`, if it's a photo of a black dog.
*   It's also recommendable adding an image title, as the "Hello World" exemplified above.

* * *

## Diagrams

There are two ways to insert diagrams via Markdown:

1.  Mermaid
2.  PlantUML

### Mermaid

See the [examples in the GitLab docs](https://docs.gitlab.com/ee/user/markdown.html#mermaid) on how to use Mermaid. We have a number of Handbook-specific example in the [Tools and Tips Section](/handbook/tools-and-tips/#using-mermaid).

### PlantUML

You can use [PlantUML](http://plantuml.com/) in Markdown blocks. For example:

<div class="highlight">

    ```plantuml
    !define ICONURL https://raw.githubusercontent.com/tupadr3/plantuml-icon-font-sprites/v2.1.0
    skinparam defaultTextAlignment center
    !include ICONURL/common.puml
    !include ICONURL/font-awesome-5/gitlab.puml
    !include ICONURL/font-awesome-5/java.puml
    !include ICONURL/font-awesome-5/rocket.puml
    !include ICONURL/font-awesome/newspaper_o.puml
    FA_NEWSPAPER_O(news,good news!,node) #White {
    FA5_GITLAB(gitlab,GitLab.com,node) #White
    FA5_JAVA(java,PlantUML,node) #White
    FA5_ROCKET(rocket,Integrated,node) #White
    }
    gitlab ..> java
    java ..> rocket
    ```

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

<div class="imageblock">

<div class="content">![](https://plantuml.gitlab-static.net/png/U9oDa4zhma0GnU_v52kzf93izWzUUYYaOiKsLR5QZs5DnhWrsLrs9ree_UvE31J4YvTXbldjl7clLy16QM3ZmNIodATiYsZzan1E7dYfSDki6mykDnf18yzDBR2nid2FmbPIOrDNiQ9fl24YzjOf12_s3_oUtmL-fxILJjQCH6HJuG9-CAbKgMjQnd8gu8AUqddL5Fyd21AfZUQMTbyEJpho0DxK4FS5dLZ9zNNijzpBwqXdyXtW5QpGSF1MMd2PwV3N99iCLv-pP3QSPzEmdKUbCGLhkrwaJG6tx6QrfPpOBz7zR3HUfCbBs3c9HWfJCaGPdB4dyYtvIiBMHJHhirz-f9VCV3fu7ox2pa4qfeHB9n6AS_8lwEGOvy-itHYqvVJgVWP72b2u4m00)</div>

</div>

</div>

</div>

## Videos

There are two ways of displaying videos: within HTML5 `<video>` tags and within `<iframe>` tags.

### Display videos from YouTube

This method works for YouTube videos and any other embed video within an `<iframe>` tag.

1.  Copy the code below and paste it into your markdown file. Leave a blank line above and below it. **Do NOT edit the code block** (e.g., remove spaces - the video iframe may not render properly)
2.  Go the video URL you want to display
3.  Click on "Share", then "Embed"
4.  Copy the `<iframe>` source (`src`) URL **only**, and paste it replacing the `src` below:

<div class="highlight">

    <!-- blank line -->
    <figure class="video_container">
      <iframe src="https://www.youtube.com/embed/enMumwvLAug" frameborder="0" allowfullscreen="true"> </iframe>
    </figure>
    <!-- blank line -->

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

<figure class="video_container"><iframe src="https://www.youtube.com/embed/enMumwvLAug" frameborder="0" allowfullscreen="true"></iframe></figure>

</div>

</div>

### Display local videos (HTML5)

This method works for any video uploaded to somewhere retrievable from the internet from a URL, or from a relative path like `path/to/video.mp4`.

1.  Read through the [w3schools HTML5 video guide](http://www.w3schools.com/tags/tag_video.asp), or the [MDN `<video>` guide](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video).
2.  Record or export the video in these three formats to achieve cross-browser and cross-device compatibility: `.mp4`, `.ogg` and `.webm`.
3.  Get the URL for your video
4.  Choose an image to use as a poster
5.  Copy the code below and paste it to your file
6.  Replace the `src` URLs for your video URLs

<div class="highlight">

    <!-- blank line -->
    <figure class="video_container">
      <video controls="true" allowfullscreen="true" poster="path/to/poster_image.png">
        <source src="path/to/video.mp4" type="video/mp4">
        <source src="path/to/video.ogg" type="video/ogg">
        <source src="path/to/video.webm" type="video/webm">
      </video>
    </figure>
    <!-- blank line -->

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

<figure class="video_container"><video controls="true" allowfullscreen="true" poster="/images/default-blog-image.png"><source src="html5-demo.mp4" type="video/mp4"></video> </figure>

</div>

</div>

_**Note:** in case you don't have all formats recommended by **w3schools**, you can use just one of them, but your video most likely won't be supported in all devices and browsers. The video above (`.mp4` only) worked on Mozilla Firefox for macOS, Android, and Windows, and on Chrome for Android and for Windows. But it may not work on other devices/browser, such as Chrome for macOS and iOS, or Safari. In fact, the best option is using YouTube or Vimeo embed videos in `<iframe>` tags._

### Display other videos

For any other videos, such as from Vimeo or Google Drive, grab the video iframe only, and proceed like we do for [YouTube videos](#display-videos-from-youtube), wrapping the `<iframe>` within a `<figure class="video_container">`, for responsiveness. Copy and paste the code below, replacing **only** the iframe URL with your own:

<div class="highlight">

    <!-- blank line -->
    <figure class="video_container">
      <iframe src="https://drive.google.com/file/d/0B6m34D8cFdpMZndKTlBRU0tmczg/preview" frameborder="0" allowfullscreen="true"> </iframe>
    </figure>
    <!-- blank line -->

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

<figure class="video_container"><iframe src="https://drive.google.com/file/d/0B6m34D8cFdpMZndKTlBRU0tmczg/preview" frameborder="0" allowfullscreen="true"></iframe></figure>

</div>

</div>

### Display multiple videos

To display multiple videos on the same page, just repeat the `figure` code block where you want them to show up, replacing the video ID with the respective ID corresponding to your videos.

To display multiple videos in a sequence, just copy the `figure` code block and paste it as many times as necessary. Always leave a blank line between the blocks. Do **NOT** remove the spaces, otherwise your videos may not render properly.

<div class="highlight">

    <!-- blank line -->
    <figure class="video_container">
      <iframe src="https://drive.google.com/file/d/0B6m34D8cFdpMZndKTlBRU0tmczg/preview" frameborder="0" allowfullscreen="true"> </iframe>
    </figure>

    <figure class="video_container">
      <iframe src="https://drive.google.com/file/d/0B6m34D8cFdpMZndKTlBRU0tmczg/preview" frameborder="0" allowfullscreen="true"> </iframe>
    </figure>

    <figure class="video_container">
      <iframe src="https://drive.google.com/file/d/0B6m34D8cFdpMZndKTlBRU0tmczg/preview" frameborder="0" allowfullscreen="true"> </iframe>
    </figure>
    <!-- blank line -->

</div>

* * *

## Table of Contents (ToC)

With kramdown, creating a Table of Contents is the easiest thing ever! The automatic ToC will include every heading in the document, unless you don't want it to be included. You do not need to add anchors individually to every title. This is an automated process.

<div class="highlight">

    ----

    ## On this page
    {:.no_toc}

    - TOC
    {:toc}

    ----

</div>

As always, leave a blank line before and after the markup. Note that there are four dashes beginning and closing the block, which is not required, but recommendable for keeping the same standards throughout [about.GitLab.com](/).

The heading "On this page" can be adapted to your case, e.g., "In this tutorial", or "In this guide", etc. It's not required either, but recommended.

The markup `{:.no_toc}` is used every time you don't want to include a heading into the ToC. Just add it right below the heading, and it won't be included into the ToC. In fact `no_toc` is a [custom class](#classes-ids-and-attributes), as described later in this guide.

The **output** ToC can be found at the very beginning of this page.

Alternatively, you can use ordered ToC too, displaying numbers at the beginning of the list. Just use the markup for ordered lists and kramdown will be smart enough to understand what you want:

<div class="highlight">

    1. TOC
    {:toc}

</div>

* * *

## Tables

Tables for markdown are challenging. So, we have two possible approaches: use markdown whenever possible, but if you need pretty advanced table layouts, you are free to add them in HTML markup instead.

> _Markdown is not a replacement for HTML, or even close to it. ([John Gruber](http://daringfireball.net/projects/markdown/syntax#html))_

As explained by John Gruber, the creator of markdown, it was not created to replace HTML, so there are situations we can't avoid using HTML. With complex tables, that's the case.

The following table has a header (first line), then markup to define the desired alignment (dashes and colons), then the table body. You can go ahead and add separators to create subsequent table bodies.

However you prepare your table, its design will depend upon the CSS styles defined for them.

The last markup `{: .custom-class #custom-id}` **can** be used in case you want to attribute a [custom class and/or a custom ID](#classes-ids-and-attributes) to the `<table>` element.

<div class="highlight">

    | Default aligned | Left aligned | Center aligned  | Right aligned  |
    |-----------------|:-------------|:---------------:|---------------:|
    | First body part | Second cell  | Third cell      | fourth cell    |
    | Second line     | foo          | **strong**      | baz            |
    | Third line      | quux         | baz             | bar            |
    |-----------------+--------------+-----------------+----------------|
    | Second body     |              |                 |                |
    | 2nd line        |              |                 |                |
    |-----------------+--------------+-----------------+----------------|
    | Third body      |              |                 | Foo            |
    {: .custom-class #custom-id}

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

<table class="custom-class" id="custom-id">

<thead>

<tr>

<th>Default aligned</th>

<th style="text-align: left">Left aligned</th>

<th style="text-align: center">Center aligned</th>

<th style="text-align: right">Right aligned</th>

</tr>

</thead>

<tbody>

<tr>

<td>First body part</td>

<td style="text-align: left">Second cell</td>

<td style="text-align: center">Third cell</td>

<td style="text-align: right">fourth cell</td>

</tr>

<tr>

<td>Second line</td>

<td style="text-align: left">foo</td>

<td style="text-align: center">**strong**</td>

<td style="text-align: right">baz</td>

</tr>

<tr>

<td>Third line</td>

<td style="text-align: left">quux</td>

<td style="text-align: center">baz</td>

<td style="text-align: right">bar</td>

</tr>

</tbody>

<tbody>

<tr>

<td>Second body</td>

<td style="text-align: left"></td>

<td style="text-align: center"></td>

<td style="text-align: right"></td>

</tr>

<tr>

<td>2nd line</td>

<td style="text-align: left"></td>

<td style="text-align: center">Hello World</td>

<td style="text-align: right"></td>

</tr>

</tbody>

<tbody>

<tr>

<td>Third body</td>

<td style="text-align: left"></td>

<td style="text-align: center"></td>

<td style="text-align: right">Foo</td>

</tr>

</tbody>

</table>

</div>

</div>

The bars, spaces, and dashes were used symmetrically in the previous example to help future page developers if they need to edit the table's contents. The symmetry isn't required.

Some development tools can help you create your own complex table if you need to merge lines or columns, or if you require a more complex layout. This [table generator](http://www.tablesgenerator.com/html_tables) may be able to help you do this.

To add a numbered list in a table cell, add a blank line between the heading and the table to render the table correctly. Otherwise, the text and formatting won't appear.

See the [kramdown syntax guide](http://kramdown.gettalong.org/syntax.html#tables) for more information about tables.

* * *

## Collapse

A collapsed content section is used to hide information until a user chooses to reveal it with a click or tap on the summary text. The hidden content is revealed inline. For example, this code:

<div class="highlight">

    <details>
      <summary markdown="span">This is the summary text, click me to expand</summary>

      This is the detailed text.

      We can still use markdown, but we need to take the additional step of using the `parse_block_html` option as described in the [Mix HTML + Markdown Markup section](#mix-html--markdown-markup).

      You can learn more about expected usage of this approach in the [GitLab UI docs](https://gitlab-org.gitlab.io/gitlab-ui/?path=/story/base-collapse--default) though the solution we use above is specific to usage in markdown.
    </details>

</div>

results in:

<details><summary>This is the summary text, click me to expand</summary>

This is the detailed text.

We can still use markdown, but we need to take the additional step of using the `parse_block_html` option as described in the [Mix HTML + Markdown Markup section](#mix-html--markdown-markup).

You can learn more about expected usage of this approach in the [GitLab UI docs](https://gitlab-org.gitlab.io/gitlab-ui/?path=/story/base-collapse--default) though the solution we use above is specific to usage in markdown.

</details>

The GitLab handbook also supports nested details sections.

<div class="highlight">

    <details>
    <summary markdown="span">First level collapsible item</summary>
    **Lorem ipsum dolor sit amet...**
    <details>
    <summary markdown="span">Second level collapsible item</summary>
    *Sed ut perspiciatis unde omnis iste natus...*
    </details>
    </details>

</div>

results in:

<details><summary>First level collapsible item</summary>

**Lorem ipsum dolor sit amet…**

<details><summary>Second level collapsible item</summary>

_Sed ut perspiciatis unde omnis iste natus…_

</details></details>

To add a table in the collapsed heading, be sure to add:

<div class="highlight">

    <details markdown="1">

</div>

* * *

## Code blocks

There are a few options for displaying code blocks with kramdown. Most of them use backticks ```.

### In-line

This is an ``in-line`` code block.

<div class="panel panel-info">

**Output**

<div class="panel-body">

_In-line_

This is an `in-line` code block.

</div>

</div>

### Fenced

<div class="highlight">

    ```
    def hello
       puts "Hello world!"
    end
    ```

</div>

_Fenced Highlighted_

<div class="highlight">

    ```ruby
    def hello
       puts "Hello world!"
    end
    ```

</div>

or

<div class="highlight">

    ```
    def hello
       puts "Hello world!"
    end
    ```
    {: .language-ruby}

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

_Fenced_

<div class="highlight">

    def hello
       puts "Hello world!"
    end

</div>

_Fenced Highlighted_

<div class="highlight">

    def hello
       puts "Hello world!"
    end

</div>

or

<div class="highlight">

    def hello
       puts "Hello world!"
    end

</div>

</div>

</div>

### Indented

Add 4 white spaces before every line:

<div class="highlight">

        def hello
           puts "Hello world!"
        end

</div>

_Indented Highlighted_

<div class="highlight">

        def hello
           puts "Hello world!"
        end
    {: .language-ruby}

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

_Indented_

<div class="highlight">

    def hello
       puts "Hello world!"
    end

</div>

_Indented Highlighted_

<div class="highlight">

    def hello
       puts "Hello world!"
    end

</div>

</div>

</div>

### Nested

Add 4 white spaces before every line. This is used when you want to display a code block within a code block.

<div class="highlight">

        ```
        def hello
           puts "Hello world!"
        end
        ```

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

_Nested_

<div class="highlight">

    ```
    def hello
       puts "Hello world!"
    end
    ```

</div>

</div>

</div>

### In lists

Indent the text of each item in 3 white spaces. Leave blank lines between the code block and the list items, and ident the code block in 5 white spaces:

<div class="highlight">

    1\.   Item 1
    1\.   Item 2

         ```ruby
         def hello
            puts "Hello world!"
         end
         ```

    1\.   Item 3

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

1.  Item 1
2.  Item 2

    <div class="highlight">

        def hello
           puts "Hello world!"
        end

    </div>

3.  Item 3

</div>

</div>

* * *

## Blockquotes

Blockquotes are good resources to mentioning someone else's quotes, like we did [just above](#quote). Also, can be used to emphasize a sentence or a small paragraph.

<div class="highlight">

    > This is a blockquote.
    >     On multiple lines.
    That may be lazy.
    >
    > This is the second paragraph.

    ----

    > This is a paragraph.
    >
    > > A nested blockquote.
    >
    > ### Headers work
    >
    > * lists too
    >
    > and all other block-level **elements**.
    >
    > Even code blocks:
    >
    >      def hello
    >        puts "Hello world!"
    >      end
    > {: .language-ruby}

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

> This is a blockquote. On multiple lines. That may be lazy.
> 
> This is the second paragraph.

* * *

> This is a paragraph.
> 
> > A nested blockquote.
> 
> ### Headers work
> 
> *   lists too
> 
> and all other block-level **elements**.
> 
> Even a code block:
> 
> <div class="highlight">
> 
>      def hello
>        puts "Hello world!"
>      end
>     
> 
> </div>

</div>

</div>

* * *

## Notes

<div class="highlight">

    This is a regular paragraph.

    **Note:** a note is something that needs to be mentioned but is apart from the context.
    {: .note}

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

This is a regular paragraph.

**Note:** a note is something that needs to be mentioned but is apart from the context.

</div>

</div>

* * *

## Comments

_Markdown markup_

<div class="highlight">

    This is a paragraph
    {::comment}
    This is a comment which is
    completely ignored.
    {:/comment}
    ... paragraph continues here.

</div>

_Regular HTML markup_

<div class="highlight">

    <!-- This is accepted as a comment too -->

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

This is a paragraph … paragraph continues here.

</div>

</div>

* * *

## Anchors

Add an anchor anywhere with:

<div class="highlight">

    [](){: name="hello-world"}

    Some text

</div>

Or simply use an ID:

<div class="highlight">

    Some text
    {: #hello-world}

</div>

* * *

## Font Awesome

Yes, we can use fancy [Font Awesome](http://fontawesome.io/icons/) icons too.

_Regular_

<div class="highlight">

    ### <i class="fas fa-puzzle-piece" aria-hidden="true"></i> Puzzle Icon
    {: #puzzle}

</div>

And you can go further, such as the following.

_Styled_

<div class="highlight">

    ### <i class="fab fa-gitlab fa-fw" style="color:rgb(107,79,187); font-size:.85em" aria-hidden="true"></i> Purple GitLab Tanuki
    {: #tanuki-purple}

    ### <i class="fab fa-gitlab fa-fw" style="color:rgb(252,109,38); font-size:.85em" aria-hidden="true"></i> Orange GitLab Tanuki
    {: #tanuki-orange}

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

_Regular_

### Puzzle Icon

* * *

_Styled_

### Purple GitLab Tanuki

### Orange GitLab Tanuki

</div>

</div>

When doing something like this to a heading, it's important give it a custom ID (e.g., `{: #puzzle}`), otherwise the one automatically created by kramdown will sound very awkward.

The class `fa-fw` is used when you want to display the icons as a list. They will be aligned, as well as the text right beside them.

See live examples [on this post](/2016/06/10/ssg-overview-gitlab-pages-part-2/), where the icons are used to illustrate the text.

* * *

## Classes, IDs, and attributes

Defining CSS classes, and elements IDs and attributes with markdown is definitely something unusual (kramdown magic!).

But yes, if you know how to use it, you'll love it! Check how easy it is to do that with kramdown:

<div class="highlight">

    Paragraph
    {: .class .class-1 .class-2}

    Paragraph
    {: #custom-id}

    Paragraph
    {: .class .class-1 #custom-id-1}

    ## Heading
    {: .class .class-1 #custom-id-2}

    Paragraph
    {: .class #custom-id-3 style="padding-top:0" key="value"}

    ## Heading {#hello}

    List:

    - {: .class} List item with custom class
    - {:#id} List item with custom id

    To a [link]{: #link}, in-line.

    This is a [link][google-es]{:hreflang="es"} in Spanish.

    [link]: https://google.com
    [google-es]: https://google.es

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Paragraph

Paragraph

Paragraph

### Heading

Paragraph

### Heading

List:

*   List item with custom class
*   List item with custom id

To a [link](https://google.com), in-line.

This is a [link](https://google.es) in Spanish.

</div>

</div>

### Special classes

#### Shadow

The CSS class called `shadow` should be used when your image edges are not clearly defined. This happens when it has a white background or when it's a screenshot with text (for example, a screenshot of our user interface). For example, this image can be mistaken as part of the text:

![text screenshot](/images/handbook/marketing/markdown-guide-image-plain-text.png)

Now, if you apply the class `shadow` to the image, it's discreetly highlighted from the text:

![text screenshot with box shadow](/images/handbook/marketing/markdown-guide-image-plain-text.png)

To do that, apply the class directly to the image by adding the markup `{: .shadow}` right after the image markup:

<div class="highlight">

    ![image alternative text](/path/to/image.png){: .shadow}

</div>

#### Note

As [previously](#notes) explained, you can add the class `note` to paragraphs that you don't want to call attention to:

**Note:** this is something I don't want to call attention to.

Markup:

<div class="highlight">

    **Note:** this is something I don't want to call attention to.
    {: .note}

</div>

#### Colors

Add a custom class to a heading or paragraph using the following special classes.

**GitLab Orange**

#### GitLab Orange Heading

Markup:

<div class="highlight">

    ### GitLab Orange Heading
    {: .gitlab-orange}

</div>

**GitLab Purple**

#### GitLab Purple Heading

Markup:

<div class="highlight">

    ### GitLab Purple Heading
    {: .gitlab-purple}

</div>

#### Text Align

By default, the text will always be aligned to the left. You have a few options to customize it with custom classes:

*   Center: `.text-center`
*   Right: `.text-right`
*   Justify: `.text-justify`

For demonstrations purposes, they are aligned in an [alert box](#colorful-sections), but this can be applied to regular paragraphs and headings.

**Align to the center**

Center-aligned

Alert box markup:

<div class="highlight">

    Center-aligned
    {: .alert .alert-info .text-center}

</div>

Paragraph markup:

<div class="highlight">

    Center-aligned
    {: .text-center}

</div>

Heading markup:

<div class="highlight">

    ### Center-aligned
    {: .text-center}

</div>

**Align to the right**

Right-aligned

<div class="highlight">

    Right-aligned
    {: .alert .alert-info .text-right}

</div>

**Justify**

Justified

<div class="highlight">

    Justified
    {: .alert .alert-info .text-justify}

</div>

* * *

## Mix HTML + Markdown Markup

Mixing HTML markup with markdown is something almost "unthinkable" to someone used to regular markdown. And it's all over this document!

Use the following markup at the beginning of your document:

<div class="highlight">

    {::options parse_block_html="true" /}

</div>

And feel free to mix everything up:

<div class="highlight">

    Something in **markdown**.

    <p>Then an HTML tag with crazy **markup** _all over_ the place!</p>

</div>

<div class="panel panel-info">

**Output**

<div class="panel-body">

Something in **markdown**.

Then an HTML tag with crazy **markup** _all over_ the place!

</div>

</div>

You can close the markup parser tag at any point, if you want to:

<div class="highlight">

    {::options parse_block_html="false" /}

</div>

* * *

## Mix ERB + Markdown

You may want to use Embedded Ruby (ERB) in your markdown, for example, to include a [`partial`](https://middlemanapp.com/basics/partials/). To do this, make sure your file extension is `.html.md.erb` as `.html.md` will not parse the Embedded Ruby.

## Colorful sections

To add notes and warning blocks into colorful boxes, we are making use of Bootstrap's [panel blocks](https://getbootstrap.com/components/#panels-alternatives) and [alert boxes](https://getbootstrap.com/components/#alerts).

Colorful sections are applied for very specific purposes and must not be overused.

Use panels when your description contains more than one paragraph, or a long paragraph. For single and short paragraphs, use alert boxes instead.

When using panels, make sure to add the HTML parser markup to the beginning of your document's body: `{::options parse_block_html="true" /}`.

Copy paste the following code according to what you want to present to the user and replace only the description. The available colors are: blue (`info`), green (`success`), amber (`warning`) and red (`danger`), as follows.

### Additional Information

Use the following code for **important notes** and additional information:

<div class="highlight">

    <div class="panel panel-info">
    **Note**
    {: .panel-heading}
    <div class="panel-body">

    NOTE DESCRIPTION

    </div>
    </div>

</div>

To apply to a single paragraph, use an alert box:

<div class="highlight">

    My important paragraph.
    {: .alert .alert-info}

</div>

Blue panels render like:

<div class="panel panel-info">

**Note**

<div class="panel-body">

NOTE DESCRIPTION

</div>

</div>

And blue alert boxes render like:

My important paragraph.

If you want the text inside the alert box to be blue as well, we need to apply [custom styles](#styles) to the markdown document. They will override the existing ones. Add the following `style` tag to the end of your file.

<div class="highlight">

    <style>
    .alert-info {
      color: rgb(49,112,143) !important;
    }
    </style>

</div>

### Warnings

Use the following code for warnings, like information that may have a different result if not used correctly:

<div class="highlight">

    <div class="panel panel-warning">
    **Warning**
    {: .panel-heading}
    <div class="panel-body">

    WARNING DESCRIPTION

    </div>
    </div>

</div>

To apply to a single paragraph, use an alert box:

<div class="highlight">

    My warning paragraph.
    {: .alert .alert-warning}

</div>

Amber panels render like:

<div class="panel panel-warning">

**Warning**

<div class="panel-body">

WARNING DESCRIPTION

</div>

</div>

And amber alert boxes render like:

My warning paragraph.

If you want the text inside the alert box to be amber as well, we need to apply [custom styles](#styles) to the markdown document. They will override the existing ones. Add the following `style` tag to the end of your file.

<div class="highlight">

    <style>
    .alert-warning {
      color: rgb(138,109,59) !important;
    }
    </style>

</div>

### Danger

Use the following code for crucial warnings, like commands that result in loss of data:

<div class="highlight">

    <div class="panel panel-danger">
    **Danger**
    {: .panel-heading}
    <div class="panel-body">

    DANGER DESCRIPTION

    </div>
    </div>

</div>

To apply to a single paragraph, use an alert box:

<div class="highlight">

    My danger paragraph.
    {: .alert .alert-danger}

</div>

Red panels render like:

<div class="panel panel-danger">

**Danger**

<div class="panel-body">

DANGER DESCRIPTION

</div>

</div>

And red alert boxes render like:

My danger paragraph.

If you want the text inside the alert box to be red as well, we need to apply [custom styles](#styles) to the markdown document. They will override the existing ones. Add the following `style` tag to the end of your file.

<div class="highlight">

    <style>
    .alert-danger {
      color: rgb(169,68,66) !important;
    }
    </style>

</div>

### Do's and Don'ts

You can use the combination of green and red panels or alert boxes for "Do's and Don'ts":

<div class="highlight">

    <div class="panel panel-success">
    **Do's**
    {: .panel-heading}
    <div class="panel-body">

    THINGS TO DO

    </div>
    </div>

</div>

or, use an alert box:

<div class="highlight">

    TO DO.
    {: .alert .alert-success}

</div>

Not to do:

<div class="highlight">

    <div class="panel panel-danger">
    **Don'ts**
    {: .panel-heading}
    <div class="panel-body">

    THINGS NOT TO DO

    </div>
    </div>

</div>

or, use an alert box:

<div class="highlight">

    NOT TO DO.
    {: .alert .alert-danger}

</div>

By doing so, the green panels for "DO'S" will look like:

<div class="panel panel-success">

**Do's**

<div class="panel-body">

THINGS TO DO

</div>

</div>

or, if you chose an alert box:

TO DO.

If you want the text inside the alert box to be green as well, we need to apply [custom styles](#styles) to the markdown document. They will override the existing ones. Add the following `style` tag to the end of your file.

<div class="highlight">

    <style>
    .alert-green {
      color: rgb(60,118,61) !important;
    }
    </style>

</div>

And for your "DON'TS" within red panels will look like:

<div class="panel panel-danger">

**Don'ts**

<div class="panel-body">

THINGS NOT TO DO

</div>

</div>

or, if you chose a red alert box:

NOT TO DO.

### Custom alert panels and alert boxes

All the previously mentioned alert boxes and panels are available by default by [Bootstrap](http://getbootstrap.com/components/#alerts). If we want them in a different color, we need [custom styles](#styles). At [about.GitLab.com](/), we can use the orange and the purple one, as follows.

When using panels, don't forget to add to the beginning of your file the [HTML parser markup](#html-parser) to be able to mix HMTL + Markdown: `{::options parse_block_html="true" /}`.

#### GitLab Orange Alert Panel

<div class="panel panel-gitlab-orange">

**Heading**

<div class="panel-body">

Text in markdown.

</div>

</div>

Panel block markup:

<div class="highlight">

    <div class="panel panel-gitlab-orange">
    **Heading**
    {: .panel-heading}
    <div class="panel-body">

    Text in markdown.

    </div>
    </div>

</div>

#### GitLab Orange Alert Box

My text in an orange box.

Box block markup:

<div class="highlight">

    My text in an orange box.
    {: .alert .alert-gitlab-orange}

</div>

#### GitLab Purple Alert Panel

<div class="panel panel-gitlab-purple">

**Heading**

<div class="panel-body">

Text in markdown.

</div>

</div>

Panel block markup:

<div class="highlight">

    <div class="panel panel-gitlab-purple">
    **Heading**
    {: .panel-heading}
    <div class="panel-body">

    Text in markdown.

    </div>
    </div>

</div>

#### GitLab Purple Alert Box

My text in an purple box.

Box block markup:

<div class="highlight">

    My text in an purple box.
    {: .alert .alert-gitlab-purple}

</div>

### GitLab Webcast Alert Box

To be used in a CTA for webcast announcement in blog posts. You can use it for other purposes as well. Use it together with the [HMTL parser](#html-parser):

The webcast I want to announce - [Register here](#)!

<div class="highlight">

    {::options parse_block_html="true" /}

    <i class="fab fa-gitlab" style="color:rgb(107,79,187); font-size:.85em" aria-hidden="true"></i>&nbsp;&nbsp;
    The webcast I want to announce - [Register here][webcast-link]!
    &nbsp;&nbsp;<i class="fab fa-gitlab" style="color:rgb(107,79,187); font-size:.85em" aria-hidden="true"></i>
    {: .alert .alert-webcast}

</div>

* * *

## Styles

Yes, guess what?

This:

<div class="highlight">

    <style>
      .purple {
        color:inherit;
      }
      .purple:hover {
        color:rgb(107,79,187);
      }
    </style>

</div>

<style>.purple { color:inherit; } .purple:hover { color:rgb(107,79,187); }</style>

Plus:

<div class="highlight">

    Hey! Hover the cursor over me and guess what?! :)
    {: .purple}

</div>

Equals to:

<div class="panel panel-info">

**Output**

<div class="panel-body">

Hey! Hover the cursor over me and guess what?! :)

</div>

</div>

And yes, the `<style>` tag is _in_ this very markdown file. Believe it or not!

* * *

## Embed documents

It's easy to embed Google Docs, Sheets, Slides, and pretty much everything that provides an iframe to use with. The only thing you need to do is use the following code inside your markdown file and replace the iframe from the document you want to embed:

<div class="highlight">

    <figure class="video_container">
    <iframe IFRAME CONTENT></iframe>
    </figure>

</div>

### Google products

For Google products, with your document opened, click **File** -> **Publish to the web**. For example, here's what Google sheets will look like:

![Google Sheets - File - Publish to the web](/images/markdown-guide/file-publish-to-the-web.png)

Choose **Embed**, check your settings, click on **Publish** and copy the `<iframe>`. Then go to your markdown file and wrap the iframe into a `<figure>` tag with the responsive `video_container` class, as shown [in the beginning](#embed-documents).

#### Google Sheets

Let's exemplify with this [simple spreadsheet](https://docs.google.com/a/gitlab.com/spreadsheets/d/1jAnvYpRmNu8BISIrkYGTLolOTmlCoKLbuHVWzCXJSY4/edit?usp=sharing). Follow the info [above](#google-products) to find the iframe:

![Google Sheets - Embed iframe](/images/markdown-guide/embed-google-sheet.png)

Copy the code below and paste to your markdown file (leave a blank line above and below it). Then replace the `<iframe>` with your own:

<div class="highlight">

    <figure class="video_container">
    <iframe src="https://docs.google.com/spreadsheets/d/1jAnvYpRmNu8BISIrkYGTLolOTmlCoKLbuHVWzCXJSY4/pubhtml?widget=true&amp;headers=false"></iframe>
    </figure>

</div>

#### Output:

<figure class="video_container"><iframe src="https://docs.google.com/spreadsheets/d/1jAnvYpRmNu8BISIrkYGTLolOTmlCoKLbuHVWzCXJSY4/pubhtml?widget=true&amp;headers=false"></iframe></figure>

#### Google Slides

Let's exemplify with this [GitLab slide deck](https://docs.google.com/presentation/d/1fWjiVgSNMKTHyC6_nWDY5rDhvdm-zEQMQytZysIXAzk/edit?usp=sharing). Follow the steps [above](#embed-documents) to find the iframe:

![Google Slides - Embed iframe](/images/markdown-guide/embed-google-slides.png)

Copy the code below and paste to your markdown file (leave a blank line above and below it). Then replace the `<iframe>` with your own:

<div class="highlight">

    <figure class="video_container">
    <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vS_iuMXnp61wlo4amm5nvHr4Ir8VUzisJSBsr7YEL7fKWAiT-9bmehyngtb9TYaFEsFnRokCyIXwsvY/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    </figure>

</div>

#### Output:

<figure class="video_container"><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vS_iuMXnp61wlo4amm5nvHr4Ir8VUzisJSBsr7YEL7fKWAiT-9bmehyngtb9TYaFEsFnRokCyIXwsvY/embed?start=false&amp;loop=false&amp;delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></figure>

#### Google Docs

Embedding Google Docs is not a recommended practice. Prefer converting your document content to markdown instead. If you need to embed it anyway, follow the same instructions and the same logic as we presented for Google Sheets and Slides, wrapping the `<iframe>` with a `<figure>` tag:

<div class="highlight">

    <figure class="video_container">
    <iframe src="https://docs.google.com/document/d/1mHhOhvvrz7xgUPyn5VWCNuKgew5MRRGZp761B9prPqs/pub?embedded=true"></iframe>
    </figure>

</div>

### SlideShare

To embed from SlideShare, go to the document you want to embed and hit the **Share** button located below the slides. Copy the code under **Embed** and place it inside the `figure` tag.

Be careful to only include the iframe content and strip anything else. SlideShare will also add some other information in the embed code which you will have to remove, otherwise the markdown page will be broken.

For example, let's say we wanted to include the slides from [Ivan's talk on GitLab Pages](http://www.slideshare.net/creatop/how-to-use-any-static-site-generator-with-gitlab-pages). Copying the embed code and stripping everything else except from the iframe, would result in this:

<div class="highlight">

    <figure>
    <iframe src="//www.slideshare.net/slideshow/embed_code/key/EixD8OUMBX65Jy" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>
    </figure>

</div>

You can safely omit the `<figure>` tag since SlideShare's widget is already responsive, but we are showing this that way in order to be consistent with the rest of the handbook.

#### Output:

<figure><iframe src="//www.slideshare.net/slideshow/embed_code/key/EixD8OUMBX65Jy" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe></figure>

* * *

## Embed Tweets

To add tweets to markdown, copy both `<blockquote>` and `<script>` tags from the twitter post and paste it into your file. To make it look much nicer, wrap the script into a `div.center` (created for this specific purpose).

**Important:** if you used the [HTML parser](#mix-html--markdown-markup) in your post or page, you'll need to set it to `false` before the `div`.

<div class="center">

> Thanks to [@gitlab](https://twitter.com/gitlab) for joining [@RailsGirlsCluj](https://twitter.com/RailsGirlsCluj)! [pic.twitter.com/NOoiqDWKVY](https://t.co/NOoiqDWKVY)
> 
> — RailsGirlsCluj (@RailsGirlsCluj) [October 8, 2016](https://twitter.com/RailsGirlsCluj/status/784847271645028352)

</div>

Markup:

<div class="highlight">

    {::options parse_block_html="false" /}

    <div class="center">

    <blockquote class="twitter-tweet" data-partner="tweetdeck"><p lang="en" dir="ltr">Thanks to <a href="https://twitter.com/gitlab">@gitlab</a> for joining <a href="https://twitter.com/RailsGirlsCluj">@RailsGirlsCluj</a>! <a href="https://t.co/NOoiqDWKVY">pic.twitter.com/NOoiqDWKVY</a></p>&mdash; RailsGirlsCluj (@RailsGirlsCluj) <a href="https://twitter.com/RailsGirlsCluj/status/784847271645028352">October 8, 2016</a></blockquote>
    <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

    </div>

</div>

For more than one Tweet, copy and paste all the code blocks from Twitter into one `div.center`:

<div class="highlight">

    {::options parse_block_html="false" /}

    <div class="center">

    <!-- first tweet -->
    <blockquote class="twitter-tweet" data-partner="tweetdeck"><p lang="en" dir="ltr">Thanks to <a href="https://twitter.com/gitlab">@gitlab</a> for joining <a href="https://twitter.com/RailsGirlsCluj">@RailsGirlsCluj</a>! <a href="https://t.co/NOoiqDWKVY">pic.twitter.com/NOoiqDWKVY</a></p>&mdash; RailsGirlsCluj (@RailsGirlsCluj) <a href="https://twitter.com/RailsGirlsCluj/status/784847271645028352">October 8, 2016</a></blockquote>
    <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

    <!-- second tweet -->
    <blockquote class="twitter-tweet" data-partner="tweetdeck"><p lang="en" dir="ltr">Thanks to <a href="https://twitter.com/gitlab">@gitlab</a> for joining <a href="https://twitter.com/RailsGirlsCluj">@RailsGirlsCluj</a>! <a href="https://t.co/NOoiqDWKVY">pic.twitter.com/NOoiqDWKVY</a></p>&mdash; RailsGirlsCluj (@RailsGirlsCluj) <a href="https://twitter.com/RailsGirlsCluj/status/784847271645028352">October 8, 2016</a></blockquote>
    <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

    </div>

</div>

* * *

## Embed Instagram posts

To embed posts from Instagram, begin by pasting the following code into your file:

<div class="highlight">

    {::options parse_block_html="false" /}

    <div align="center">

</div>

Then go to the relevant Instagram post on the web: Go to the post URL if you have it, or you can search for the username on [Instagram.com](https://www.instagram.com/), visit their profile, and then click the post to expand it. Click the more […] button and select "Embed."

Copy the code and paste it below `<div align="center">`.

Add `</div>` after the code you pasted from Instagram.

## Embed GitLab Snippets

To embed [GitLab Snippets](https://docs.gitlab.com/ee/user/snippets.html#embedded-snippets) to a markdown file, copy the embed code from your public snippet and paste it in the file.

Markup:

<div class="highlight">

    <!-- leave a blank line here -->
    <script src="https://gitlab.com/gitlab-org/gitlab-ce/snippets/1717978.js"></script>
    <!-- leave a blank line here -->

</div>

Renders:

* * *

## Markdown Editors

Please use the editors available on GitLab.com, one of the following code editors, or your preferred **code editor** to write in markdown.

It is **not** recommended writing your document in a regular text editor like Google Docs, Microsoft Word, or macOS's Pages, then copy-pasting to markdown, as it most likely will bring some characters with a different encoding (non UTF-8), which will cause the markdown to not render correctly.

In case you don't have a choice and need to import a text already written in a text editor, paste it to your markdown file using **command+shift+V** on a Mac, or **control+shift+V** on Windows or Linux. You might minimize the cause of trouble by pasting without format. But yet, is not guaranteed it is going to work, so double check your output.

If the document was in Google Docs, you can install the [Docs to Markdown](https://workspace.google.com/marketplace/app/docs_to_markdown/700168918607) add-on, which helps convert the Google Docs to markdown. You'll likely need to make minor updates or edits to the markdown that the add-on generates.

_Editors Available on GitLab.com_

*   [Web IDE](https://docs.gitlab.com/ee/user/project/web_ide/)
*   [Web Editor](https://docs.gitlab.com/ee/user/project/repository/web_editor.html)

_Regular Code Editors_

*   [Sublime Text 3](https://www.sublimetext.com/3)
*   [VS Code](https://code.visualstudio.com/)
*   [Atom](https://atom.io/) _(Atom is due to be [discontinued](https://github.blog/2022-06-08-sunsetting-atom/) from December 2022)_

_Markdown editors (type and preview simultaneously)_

*   Markdown editors for Mac: [MacDown](https://macdown.uranusjr.com/), [iA Writer](https://ia.net/writer/)
*   In-browser markdown editor: [StackEdit](https://stackedit.io/)
*   [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables)

If you're not used to writing markdown, these editors can be helpful. Many editors offer realtime previews and while these previews may not be exactly the same as the final result they can be a very good approximation, which gives you a good idea of what the output will be while you type.

[StackEdit](https://stackedit.io/) is awesome too, you can work on a markdown file even if you're away from your computer, or out of resources. It works from every major browser and automatically saves your work to Google Drive.

Do you want a simple way of copying a hyperlink title and address in markdown? The [Format Link](https://chrome.google.com/webstore/detail/format-link/pocemhmkmchpgamlnocemnbhlcjcbjgg) extension offers a quick and easy way to do this, along with allowing you to customize any number of other formats. [View detailed instructions and examples](https://docs.google.com/document/d/1y3xdjwgiVsTpVBAEFhK1nn7G6iJm8p5nIEfAoKt_oBk/edit#heading=h.51mhaa5pq2zt).

If you're looking for just the ability to copy something as markdown, try these [Firefox add-ons](https://addons.mozilla.org/firefox/search/?q=copy+markdown) or [Chrome extensions](https://chrome.google.com/webstore/search/copy+markdown).

* * *

## Complementary Notes

*   Words must be separated by one single space only. Do not leave more blank spaces than the necessary, they can render differently than expected and can cause other issues.
*   Do not leave blank spaces at the end of sentences.
*   Always leave a blank line between block-level markup elements, except between list items. Example:

    <div class="highlight">

          ---- (markup for horizontal line)
          <!-- blank line -->
          Paragraph.
          <!-- blank line -->
          Do not leave blank lines within list items:
          <!-- blank line -->
          - Item 1
          - Item 2
          - Item 3

    </div>

*   As explained [above](#headings), do **not** skip headings. Always do h1 → h2 → h3 → h4\. Never h2 → h4.
*   Prefer short titles and headings. Do not punctuate them (unless they require a question mark or an exclamation).
*   Try not to punctuate list items, but if you do, be consistent and do that throughout the list.
*   If you have to mention a non-clickable URL, prefer using backticks: `http://an-example.com`.
*   To add fancy emojis to your file, click `control+cmd+space` on your Mac and check the ⭐️ **magic** ⭐ or use a website like [Emoji Finder](https://emojifinder.com/). Do not overuse them, please!
*   If you are confused about any markup that you've found in this file, you can check its [`raw` file](https://gitlab.com/gitlab-com/www-gitlab-com/-/raw/master/sites/handbook/source/handbook/markdown-guide/index.html.md) for reference, where you'll be able to see exactly how everything was written to produce the results you are seeing on this page.

## More

Anything else you know of and is not described here? Any new magic? Any trick? Please contribute!

</div>

</div>

<div style="display: none">[Open in Web IDE](https://gitlab.com/-/ide/project/gitlab-com/www-gitlab-com/edit/master/-/sites/handbook/source/handbook/markdown-guide/index.html.md) [View source](https://gitlab.com/gitlab-com/www-gitlab-com/blob/master/sites/handbook/source/handbook/markdown-guide/index.html.md)</div>

<script>//<![CDATA[ $.ajax({ url: '//munchkin.marketo.net/munchkin.js', dataType: 'script', cache: true, success: function() { Munchkin.init('194-VVC-221'); } }); //]]></script>
