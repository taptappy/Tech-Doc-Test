<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <link href="TechDoc.css" rel="stylesheet" type="text/css">
        <link href="Documents/bootstrap/css/bootstrap-responsive.min.css" rel="stylesheet" type="text/css">
        <title name="Technical Documentation">
            Technical Documentation
        </title>
    </head>
    <div class="container">
    <nav id="navbar">
        <header>HTML<br> Crash Course</header>
        <ul>
            <li><a class="nav-link" href="#Introduction_to_HTML">Introduction to HTML</a></li>
            <li><a class="nav-link" href="#Getting_Started_With_HTML">Getting Started With HTML</a></li>
            <li><a class="nav-link" href="#The_Head_Element">The Head Element</a></li>
            <li><a class="nav-link" href="#A_Few_HTML_Fundamentals">A Few HTML Fundamentals</a></li>
            <li><a class="nav-link" href="#A_Few_Items_of_Multimedia">A Few Items of Multimedia</a></li>
        </ul>
    </nav>
    </div>
    <body>
        <main id="main-doc">
            <section id="Introduction_to_HTML" class=main-section>
                <header id="intro">Introduction to HTML</header>
                <article>
                    <p>HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content.</p> 

                    <p>"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. </p>
                </article>
            </section>
            <section id="Getting_Started_With_HTML" class=main-section>
                <header id="getting-started">Getting Started With HTML</header>
                <p>
                    HTML (Hypertext Markup Language) is not a programming language; it is a markup language used to tell your browser how to structure the web pages you visit. It can be as complicated or as simple as the web developer wishes it to be. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of the content to make it appear or act a certain way. The enclosing tags can make a bit of content into a hyperlink to link to another page on the web, italicize words, and so on.  For example, take the following line of content:
                </p>
                <pre class="html-sentence">
                  <code class="html sentence">
                      The door is not real.
                  </code>
                </pre>
                <p>If we wanted the line to stand by itself, we could specify that it is a paragraph by enclosing it in a paragraph 
                    <pre>
                    <code> &ltp&gt</code> element:</p>
                    </pre>
            </section>
            <section id="The_Head_Element" class=main-section>
                <header id="the-head">The Head Element</header>
                <p>The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page 
                    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title"> <code> &lttitle&gt</code> </a> , links to CSS (if you choose to style your HTML content with CSS), links to custom favicons, and other metadata (data about the HTML, such as the author, and important keywords that describe the document.)</p>

                    <p>Here is a short example of a couple of elements that can be placed inside the &lthead&gt :</p>
                    <pre>
                      <code>
                        &lthead&gt
                        &ltmeta charset="utf-8"&gt
                        &lttitle>My test page&lt/title&gt
                        &lt/head&gt
                      </code>
                    </pre>
                    
            </section>
            <section id="A_Few_HTML_Fundamentals" class=main-section>
                <header id="fundamentals">A Few HTML Fundamentals</header>
                <p>Structured content makes the reading experience easier and more enjoyable. In HTML, each paragraph has to be wrapped in a <code>&ltp&gt</code> element. 
                
                Some other fundamental elements are:
                <ul>
                    <li><code>&lth1&gt</code></li>
                    <li><code>&ltdiv&gt</code></li>
                    <li><code>&ltbody&gt</code></li>
                    <li><code>&lta&gt</code></li>
                    <li><code>&ltbr&gt</code></li>
                </ul>    
                </p>
            </section>
            <section id="A_Few_Items_of_Multimedia" class=main-section>
                <header id="multimedia">A Few Items of Multimedia</header>
                <p>What would a fun website be without some mulitmedia content. Things like audio files, videos, gifs make great additions to a page when it's warranted.
                    When using some of the tags like &ltimg&gt, &ltaudio&gt, and &ltvideo&gt required for this type of content there is a required attribute needed. That attribute is "src". 
                </p>
            </section>
        </main>
    </body>
</html>
