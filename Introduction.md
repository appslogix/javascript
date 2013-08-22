INTRODUCTION
----------------------------------------------------------
JavaScript is the colloquial name for a specification known as ECMAScript, developed by Brenden Eich at Netscape 1995 - 1996. It was first called LiveScript and renamed for marketing as JavaScript. Its not a compiled language and it is used to simulate and create special iteractivity on the Web. In 1997 Microsoft and ECMA released first version of ECMAScript standard, the latest version is formalized in the standard known as ECMA-262 5th Edition. See ECMA International - http://ecma-international.org/

DOM is another standard relevant to JavaScript programming developed by W3C. its a platform-and-language-neutral interface that allows programs and scripts to dynamically access and update the content, structure and style of Web documents. It creates a tree structure for HTML and XML documents and enables scripting of those objects.

A JavaScript program consists of statements formed from tokesn, operators and identifiers placed together in an order that is meaningul to a JavaScript interpreter, contained in Browsers.

STATMENT
// Set variable SmallNumber to 4
var SmallNumber = 4;

TOKENS 
//Reserved words
var

// Identifier, Operator, Literal


PSEODOPROTOCOL

// Type in browser address bar
javascript:alert("Hello world");

PLACEMENT

<!-- Within header -->
<head>
  <title>A Web page</title>
  <script>
    Some JavaScript code ...
  </script>
</head>

<!-- Within body -->
<body>
  <script>
    Some JavaScript code ...
  </script>
</body>


UNOBSTRUCTIVE PROGRAMMING
Behaviour seperation. Behaviour calls for structure to be seperated from style. Structure and Style are seperated from Behariour. In this model, HTML, XHTML provides structure while CSS provides style and JavaScript provides the behaviour.

JavaScript is Unobstructive, meaning that any use of JavaScript will fail in a graceful manner. Not assuming that JavaScript will be available, the unobsructive scripter must make sure that the Web page or application will function without JavaScript or use proper methods to ensure that JavaScript is available if its actually required.

DATA TYPES

- Numbers
- Strings
- Booleans
- Null
- Undefined
- Objects
- 
