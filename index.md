---
layout: default
---

<style>
  /* === Global Reset & Background === */
  body, html {
    background: rgba(10, 0, 20, 0.85); /* translucent dark purple */
    color: #f0f0ff;
    line-height: 1.6;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    backdrop-filter: blur(6px); /* subtle blur effect */
  }

  /* === Headings (Neon Purple) === */
  h1, h2, h3, h4, h5, h6 {
    color: #d700ff; /* neon purple */
    text-shadow: 0 0 5px #d700ff;
  }

  /* === Links === */
  a {
    color: #9b59b6;
    text-decoration: none;
    transition: 0.3s;
  }
  a:hover {
    color: #ffffff;
    text-shadow: 0 0 10px #d700ff;
  }

  /* === Buttons === */
  .btn {
    display: inline-block;
    padding: 10px 16px;
    background-color: #d700ff;
    color: white;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 0 10px #d700ff;
    transition: background-color 0.3s ease, box-shadow 0.3s ease;
  }
  .btn:hover {
    background-color: #a200c2;
    box-shadow: 0 0 15px #ff00f2;
  }

  /* === Code blocks === */
  pre, code {
    background: rgba(40, 0, 60, 0.7);
    color: #f6f6ff;
    padding: 10px;
    border-radius: 4px;
    overflow-x: auto;
  }

  /* === Blockquotes === */
  blockquote {
    border-left: 4px solid #d700ff;
    margin: 1em 0;
    padding-left: 1em;
    color: #ddd;
    background: rgba(80, 0, 100, 0.2);
  }

  /* === Tables === */
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid rgba(255, 255, 255, 0.2);
    padding: 8px;
    text-align: left;
  }
  th {
    background-color: rgba(50, 0, 80, 0.4);
  }

  /* === Footer === */
  footer {
    text-align: center;
    font-size: 0.8em;
    color: #aaa;
    margin-top: 4rem;
  }
</style>

# Projects

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
