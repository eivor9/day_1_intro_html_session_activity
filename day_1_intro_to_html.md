# Intro To HTML Day 1

<details> 
  <summary> 🎯 Objectives</summary> <br>

By the end of this session, participants will be able to:

- 🔄 Understand the Basics of HTML: Learn foundational HTML structure (e.g., `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`) and create a basic HTML document from scratch.
- 📚 Apply HTML Tags to Structure Content: Use tags like `<h1>`, `<p>`, `<strong>`, `<em>`, and `<img>` to format text and embed images, converting plain text into a structured, well-formatted HTML document.
- 🔗 Embed Multimedia Elements into Web Pages: Incorporate elements such as `<img>`, `<video>`, and `<audio>` with proper attributes to enhance web pages with multimedia content for engagement and accessibility.
____
</details> 

<details> 
  <summary> 👨🏾‍🏫 Coaching </summary> <br>
<details> 
  
  <summary> What/Why?:</summary> <br>
  
 CHATGPT Q/A: 
  The development and adoption of HTML (Hypertext Markup Language) as the standard for the web is a fascinating story that intertwines technological innovation with the need for a universal and easy-to-use language to create web pages. Let's address your questions one by one:

### How did HTML become the standard for the web?

HTML became the standard for the web primarily because it was proposed by Tim Berners-Lee, the inventor of the World Wide Web, while he was working at CERN in 1990. His vision for the web was a space where researchers could share and access documents through a system of hypertext links. HTML was designed to be simple enough for non-technical people to write and understand, which greatly contributed to its widespread adoption. The establishment of the World Wide Web Consortium (W3C) in 1994, which Tim Berners-Lee founded to lead the web to its full potential, also played a crucial role in standardizing HTML and guiding its development.

### What were people doing before HTML file?

Before HTML and the creation of the web, information sharing among researchers and academics was largely limited to physical media, like published papers or direct file transfers via FTP (File Transfer Protocol) on the internet's precursor, the ARPANET. Electronic mail (email) was also used for sharing text-based information. However, these methods lacked the interconnectedness and ease of access that the web would later provide.

### Do you have an example of some early HTML files being sent between researchers?

While specific examples of early HTML files being sent between researchers are part of historical archives and not readily accessible in a digital format for public viewing, Tim Berners-Lee's original proposal for the World Wide Web itself and the first website at CERN serve as foundational examples. The first website, created by Berners-Lee, was hosted on a NeXT computer at CERN and provided information about the World Wide Web project itself. It described the basics of the web, how to access other people's documents, and how to set up your own server.

### Why did HTML come about?

HTML came about as a solution to the problem of sharing and linking documents in a networked information system. Tim Berners-Lee envisioned a globally connected space through which researchers could easily access each other's work via hypertext, which led to the development of HTML as a simple markup language to create those hypertext documents.

### Why did websites need to become so interactive?

Websites needed to become more interactive to meet the growing demands of users and the expanding capabilities of the internet. As the web evolved from a simple document-sharing platform to a medium for complex multimedia content, e-commerce, social media, and applications, a more interactive user experience became necessary. This interactivity allows users to not only consume content but also to create content, engage with other users, and perform tasks online, making the web more dynamic and versatile.

### Are there any other languages that can be placed in an HTML page?

Yes, several languages can be used in conjunction with HTML to enhance web pages:
- **CSS (Cascading Style Sheets)** is used for styling HTML elements.
- **JavaScript** is used to create interactive effects and dynamic content.
- **SVG (Scalable Vector Graphics)** can be embedded for vector-based graphics.
- **XML data** can be included for data exchange, particularly in AJAX (Asynchronous JavaScript and XML) applications.

### What does XHTML?

XHTML (Extensible Hypertext Markup Language) is a reformulation of HTML 4 as an XML 1.0 application. It was developed to combine the flexibility of HTML with the stricter syntax of XML, ensuring that documents are well-formed and easily processed by standard XML tools. XHTML aimed to increase the interoperability and portability of web documents.

### What are the updates in HTML5?

HTML5 introduced several major updates and new features designed to make web development more powerful and efficient:
- **New semantic elements** like `<article>`, `<section>`, `<nav>`, `<header>`, and `<footer>` for better document structure.
- **Form control attributes** like placeholder, autofocus, and autocomplete for improved form handling.
- **Audio and video elements** (`<audio>` and `<video>`) for embedding media without needing third-party plugins.
- **Canvas and SVG for in-browser graphics**, allowing for dynamic, scriptable rendering of 2D shapes and bitmap images.
- **Geolocation API**, allowing websites to request the user's location.
- **Web storage and offline capabilities** for creating web applications that can store data locally and operate offline.
- **WebSocket support** for more efficient, real-time communication between the client and server.

These advancements made HTML5 a pivotal update in the evolution of the web, significantly enhancing the capability of developers to create rich, interactive web applications.
  
  
  - **What?** HTML is the standard markup language used to create and structure web pages and web applications. With HTML, you can create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes, and other items.
  
  - **Why?** HTML is foundational to web development because it provides the basic structure of sites, upon which CSS and JavaScript are applied to manipulate appearance and functionality. Understanding HTML is crucial for web development, as it is the starting point for building web content and applications. It allows content to be structured in a way that is accessible to web browsers and users, enabling the creation of engaging, interactive web experiences.
<details>
<summary>Lack of Standardized Web Structure</summary>

Without HTML, there would be no standard way to structure and display content on the web. This would lead to inconsistency in how information is presented across different websites and platforms, making it difficult for users and web browsers to interpret and navigate web content effectively.

</details>

<details>
<summary>Inaccessibility of Web Content</summary>

HTML provides semantic meaning to web content, which is crucial for accessibility. Without HTML's structure, it would be challenging to create web pages that are accessible to people with disabilities, as screen readers and other assistive technologies rely on the semantics provided by HTML tags to interpret content for users.

</details>

<details>
<summary>Difficulty in Styling and Interactivity</summary>

CSS (Cascading Style Sheets) and JavaScript, which are used for styling and adding interactivity to web pages, respectively, rely heavily on the structure provided by HTML. Without HTML elements and tags to target, customizing the appearance and behavior of web content would be significantly more complex and limited.

</details>

<details>
<summary>Compromised Search Engine Optimization (SEO)</summary>

Search engines use the structure and semantics of HTML to index and rank web pages. Without HTML, optimizing content for search engines would be nearly impossible, leading to decreased visibility of web content and difficulties in finding information online.

</details>

<details>
<summary>Challenges in Web Development and Maintenance</summary>

The standardized nature of HTML allows for the development of tools, libraries, and frameworks that streamline web development and maintenance. Without HTML, developers would face significant challenges in creating and managing web content, leading to increased development time and costs.

</details>
</details>


<details> 
  <summary> Guided:</summary>
<br>
### **Step 1: Start with Your Content**

Begin with the core content of your webpage. This might include titles, paragraphs, and any other text you plan to include. At this stage, focus solely on the text, without worrying about any HTML tags.

**Example Content:**
```
The Revival of City Parks: A Breath of Fresh Air

In cities across the globe, urban parks are experiencing a renaissance...
```

### **Step 2: Add Structure with Headings and Paragraphs**

Introduce structure to your document by wrapping your headings in `<h1>`, `<h2>`, etc., tags, and your paragraphs in `<p>` tags. This step is crucial for defining the document's hierarchy and improving readability.

**Instructions:**
- Use `<h1>` for your main title.
- Subtitles can use `<h2>` (and lower, depending on sub-sections).
- Enclose paragraphs with `<p>` tags.

### **Step 3: Organize Content Semantically**

Enhance your document's structure and semantics by grouping related content using `<article>`, `<section>`, `<header>`, `<footer>`, and `<nav>` tags.

**Instructions:**
- Wrap individual content pieces or related groups of content in `<section>` or `<article>` tags.
- Use `<header>` for introductory content and `<footer>` for concluding content or contact information.
- If your document includes navigation links, enclose them within a `<nav>` element.

### **Step 4: Embed Multimedia Elements**

Make your webpage more engaging by adding images, videos, and audio. Remember to use the `alt` attribute for images to ensure accessibility.

**Instructions:**
- To add an image, use `<img src="image-path.jpg" alt="description">`.
- For videos, use `<video>` with `<source>` tags inside it.
- Embed audio with the `<audio>` tag and `<source>` tags.

### **Step 5: Create Links**

Connect your content to other webpages or resources using `<a>` tags. This step is key for web navigation and linking related content.

**Instructions:**
- Use `<a href="URL">link text</a>` to create hyperlinks.

### **Step 6: Structure the Document Head**

Define the metadata and title of your document in the `<head>` section. This part of the document includes the title and character set declaration, which are essential for web browsers.

**Instructions:**
- Declare the character set with `<meta charset="UTF-8">`.
- Set your webpage's title using `<title>Your Page Title</title>`.

### **Step 7: Declare the Document Type**

Finally, start your document with the `<!DOCTYPE html>` declaration to ensure the browser correctly processes it as an HTML5 document.

**Instructions:**
- Place `<!DOCTYPE html>` at the very beginning of your HTML document.



</details>

_____
</details> 
  
  
<details> 
  <summary> 📚 Additional Material </summary> <br>
  <details> 
    <summary> Labs </summary>
  </details>
  <details> 
    <summary> Good Frontend/Bad Frontend </summary>
  </details>
  <details> 
    <summary> Resources </summary>
  </details>
</details>
