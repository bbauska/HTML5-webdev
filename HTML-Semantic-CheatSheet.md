<h1>Semantic HTML cheat sheet</h1>

There are hundreds of semantic tags available to help describe the meaning of your HTML documents. Below is a cheat sheet with some of the most common ones you’ll use in your development career. 

<h2>Sectioning tags</h2>
<p>Use the following tags to organize your HTML document into structured sections.</p>

| Tag          | Description |
|--------------|-----------------------------------------------------------------------------------|
| <b><mark>&lt;header&gt;</mark></b>  | The header of a content section or the web page. The web page header often contains the website branding or logo. |
| <b><mark>&lt;nav&gt;</mark></b>     | The navigation links of a section or the web page. |
| <b><mark>&lt;footer&gt;</mark></b>  | The footer of a content section or the web page. On a web page, it often contains secondary links, the copyright notice, privacy policy and cookie policy links.|
| <b><mark>&lt;main&gt;</mark></b>    | Specifies the main content of a section or the web page. |
| <b><mark>&lt;aside&gt;</mark></b>   | A secondary set of content that is not required to understand the main content. |
| <b><mark>&lt;article&gt;</mark></b> | An independent, self-contained block of content such as a blog post or product. |
| <b><mark>&lt;section&gt;</mark></b> | A standalone section of the document that is often used within the body and  article elements. |
| <b><mark>&lt;details&gt;</mark></b> | A collapsed section of content that can be expanded if the user wishes to view it. |
| <b><mark>&lt;summary&gt;</mark></b> | Specifies the summary or caption of a <b><mark>&lt;details&gt;</mark></b> element. |
| <b><mark>&lt;h1&gt;&lt;h2&gt;&lt;h3&gt;&lt;h4&gt;&lt;h5&gt;&lt;h6&gt;</mark></b> | Headings on the web page. <b><mark>&lt;h1&gt;</mark></b> indicates the most important heading whereas <b><mark>&lt;h6&gt;</mark></b> indicates the least important. |

<h2>Content tags</h2>

| Tag          | Description |
|--------------|-----------------------------------------------------------------------------------|
| <b><mark>&lt;blockquote&gt;</mark></b> | Used to describe a quotation. | 
| <b><mark>&lt;dd&gt;</mark></b> | Used to define a description for the preceding &lt;dt&gt; element. |
| <b><mark>&lt;dl&gt;</mark></b> | Used to define a description list. |
| <b><mark>&lt;dt&gt;</mark></b> | Used to describe terms inside <b><mark>&lt;dl&gt;</mark></b> elements. |
| <b><mark>&lt;figcaption&gt;</mark></b> | Defines a caption for a photo image. |
| <b><mark>&lt;figure&gt;</mark></b> | Applies markup to a photo image. |
| <b><mark>&lt;hr&gt;</mark></b> | Adds a horizontal line to the parent element. |
| <b><mark>&lt;li&gt;</mark></b> | Used to define an item within a list. |
| <b><mark>&lt;menu&gt;</mark></b> | A semantic alternative to <b><mark>&lt;ul&gt;</mark></b> tag. |
| <b><mark>&lt;ol&gt;</mark></b> | Defines an ordered list. |
| <b><mark>&lt;p&gt;</mark></b> | Defines a paragraph. |
| <b><mark>&lt;pre&gt;</mark></b> | Used to represent preformatted text. Typically rendered in the web browser using a monospace font. |
| <b><mark>&lt;ul&gt;</mark></b> | Unordered list. |

<h2>Inline tags</h2>

| Tag      | Description |
|--------------|-----------------------------------------------------------------------------------|
| <b><mark>&lt;a&gt;</mark></b>  | An anchor link to another HTML document.  |
| <b><mark>&lt;abbr&gt;</mark></b> | Specifies that the containing text is an abbreviation or acronym. |
| <b><mark>&lt;b&gt;</mark></b> | Bolds the containing text. When used to indicate importance use <b><mark>&lt;strong&gt;</mark></b> instead. |
| <b><mark>&lt;br&gt;</mark></b> | A line break. Moves the subsequent text to a new line. |
| <b><mark>&lt;cite&gt;</mark></b> | Defines the title of creative work (for example a book, poem, song, movie, painting or sculpture). The text in the <b><mark>&lt;cite&gt;</mark></b> element is usually rendered in italics. |
| <b><mark>&lt;code&gt;</mark></b> | Indicates that the containing text is a block of computer code. |
| <b><mark>&lt;data&gt;</mark></b> | Indicates machine-readable data. |
| <b><mark>&lt;em&gt;</mark></b> | Emphasizes the containing text. |
| <b><mark>&lt;i&gt;</mark></b> | The containing text is displayed in italics. Used to indicate idiomatic text or technical terms.  |
| <b><mark>&lt;mark&gt;</mark></b> | The containing text should be marked or highlighted. |
| <b><mark>&lt;q&gt;</mark></b> | The containing text is a short quotation. |
| <b><mark>&lt;s&gt;</mark></b> | Displays the containing text with a strikethrough or line through it.  |
| <b><mark>&lt;samp&gt;</mark></b> | The containing text represents a sample.  |
| <b><mark>&lt;small&gt;</mark></b> | Used to represent small text, such as copyright and legal text.  |
| <b><mark>&lt;span&gt;</mark></b> | A generic element for grouping content for CSS styling.  |
| <b><mark>&lt;strong&gt;</mark></b> | Displays the containing text in bold. Used to indicate importance.  |
| <b><mark>&lt;sub&gt;</mark></b> | The containing text is subscript text, displayed with a lowered baseline.  |
| <b><mark>&lt;sup&gt;</mark></b> | The containing text is superscript text, displayed with a raised baseline.  |
| <b><mark>&lt;time&gt;</mark></b> | A semantic tag used to display both dates and times.  |
| <b><mark>&lt;u&gt;</mark></b> | Displays the containing text with a solid underline.  |
| <b><mark>&lt;var&gt;</mark></b> | The containing text is a variable in a mathematical expression. |

<h2>Embedded content and media tags</h2>

| Tag      | Description |
|--------------|-----------------------------------------------------------------------------------|
| <b><mark>&lt;audio&gt;</mark></b> | Used to embed audio in web pages. |
| <b><mark>&lt;canvas&gt;</mark></b> | Used to render 2D and 3D graphics on web pages. |
| <b><mark>&lt;embed&gt;</mark></b> | Used as a containing element for external content provided by an external application such as a media player or plug-in application. |
| <b><mark>&lt;iframe&gt;</mark></b> | Used to embed a nested web page. |
| <b><mark>&lt;img&gt;</mark></b> | Embeds an image on a web page. |
| <b><mark>&lt;object&gt;</mark></b> | Similar to <b><mark>&lt;embed&gt;</mark></b> but the content is provided by a web browser plug-in.  |
| <b><mark>&lt;picture&gt;</mark></b> | An element that contains one <b><mark>&lt;img&gt;</mark></b> element and one or more <b><mark>&lt;source&gt;</mark></b> elements to offer alternative images for different displays/devices. |
| <b><mark>&lt;video&gt;</mark></b> | Embeds a video on a web page. <b><mark>&lt;source&gt;</mark></b> Specifies media resources for <b><mark>&lt;picture&gt;</mark></b>, <b><mark>&lt;audio&gt;</mark></b> and <b><mark>&lt;video&gt;</mark></b> elements. |
| <b><mark>&lt;svg&gt;</mark></b> | Used to define Scalable Vector Graphics within a web page. |

<h2>Table tags</h2>

| Tag      | Description |
|--------------|-----------------------------------------------------------------------------------|
| <b><mark>&lt;table&gt;</mark></b>  | Defines a table element to display table data within a web page.  |
| <b><mark>&lt;thead&gt;</mark></b> | Represents the header content of a table. Typically contains one <b><mark>&lt;tr&gt;</mark></b> element. |
| <b><mark>&lt;tbody&gt;</mark></b> | Represents the main content of a table. Contains one or more <b><mark>&lt;tr&gt;</mark></b> elements.  |
| <b><mark>&lt;tfoot&gt;</mark></b> | Represents the footer content of a table. Typically contains one <b><mark>&lt;tr&gt;</mark></b> element.  |
| <b><mark>&lt;tr&gt;</mark></b> | Represents a row in a table. Contains one or more <b><mark>&lt;td&gt;</mark></b> elements when used within <b><mark>&lt;tbody&gt;</mark></b> or <b><mark>&lt;tfoot&gt;</mark></b>. When used within <b><mark>&lt;thead&gt;</mark></b>, contains one or more <b><mark>&lt;th&gt;</mark></b> elements. |
| <b><mark>&lt;td&gt;</mark></b> | Represents a cell in a table. Contains the text content of the cell.  |
| <b><mark>&lt;th&gt;</mark></b> | Defines a header cell of a table. Contains the text content of the header.  |
| <b><mark>&lt;caption&gt;</mark></b> | Defines the caption of a table element.  |
| <b><mark>&lt;colgroup&gt;</mark></b> | Defines a semantic group of one or more columns in a table for formatting.  |
| <b><mark>&lt;col&gt;</mark></b> | Defines a semantic column in a table. |
