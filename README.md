# kuguake.github.com
---
layout: nil
---


/*
 * Fonts
 */

@font-face {
  font-family: 'fontello';
  src: url('font/fontello.eot');
  src: url('font/fontello.eot#iefix') format('embedded-opentype'),
       url('font/fontello.woff') format('woff'),
       url('font/fontello.ttf') format('truetype'),
       url('font/fontello.svg') format('svg');
  font-weight: normal;
  font-style: normal;
}

[class^="icon-"]:before, [class*=" icon-"]:before {
  font-family: "fontello";
  font-style: normal;
  font-weight: normal;
  speak: none;
  display: inline-block;
  text-decoration: inherit;
  width: 1em;
  margin-right: .2em;
  text-align: center;
  font-variant: normal;
  text-transform: none;
}

.icon-github-circled:before { content: '\e800'; } /* '' */
.icon-twitter:before { content: '\e801'; } /* '' */


/*
 * Scaffolding and type
 */

html {
  font-size: 16px;
}
@media (min-width: 48em) {
  html {
    font-size: 20px;
  }
}

body {
  margin: 0;
  font: 1rem/1.5 "PT Sans", sans-serif;
  color: #5a5a5a;
}

a {
  color: #08c;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

h1, h2, h3, h4 {
  margin: 0 0 .5rem;
  font-weight: normal;
  line-height: 1;
  color: #2a2a2a;
  letter-spacing: -.05em;
}
h1 { font-size: 3rem; }
h2 { font-size: 2.5rem; }
h3 { font-size: 1.75rem; }
h4 { font-size: 1.25rem }

p {
  margin: 0 0 1rem;
}
.lead {
  font-size: 1.3rem;
}

blockquote {
  position: relative;
  margin: 0 1rem 1rem;
  font-style: italic;
  color: #7a7a7a;
}
blockquote p {
  margin-bottom: 0;
}

ul li {
  margin-bottom: .25rem;
}

/* Tighten up margin on last items */
p:last-child,
ul:last-child,
blockquote:last-child{
  margin-bottom: 0;
}



/*
 * Code
 */

code,
pre {
  font-family: "PT Mono", Menlo, "Courier New", monospace;
  font-size: 95%;
}
code {
  padding: 2px 4px;
  font-size: 85%;
  color: #d44950;
  background-color: #f7f7f9;
  border-radius: .2rem;
}

pre {
  display: block;
  margin: 0 0 1rem;
  line-height: 1.4;
  white-space: pre;
  white-space: pre-wrap;
}
pre code {
  padding: 0;
  color: inherit;
  background-color: transparent;
  border: 0;
}
.highlight {
  margin: 0;
}
.highlight pre {
  margin-bottom: 0;
}
.highlight + .highlight {
  margin-top: 1rem;
}


/*
 * The Grid
 */

.col {
  padding: 2rem 1rem;
}
.col p {
  max-width: 40rem;
}
.col + .col {
  border-top: 1px solid #dfe1e8;
  background-color: #f7f7f9;
}
@media (min-width: 38em) {
  .col {
    padding: 2rem;
  }
}
@media (min-width: 48em) {
  .section {
    display: table;
    width: 100%;
    table-layout: fixed;
  }
  .col {
    display: table-cell;
    padding: 3rem;
    vertical-align: top;
  }
  .col + .col {
    border-top: 0;
  }
}

/* Make the ToC a whole section */
.toc .col + .col {
  background-color: #fff;
}


/*
 * Masthead
 */

.masthead {
  padding: 3rem 1rem;
  color: rgba(255,255,255,.5);
  text-align: center;
  background-color: #2a3440;
}
.masthead h1 {
  color: #fff;
  margin-bottom: .25rem;
}
.masthead .icon {
  display: inline-block;
  font-size: 3rem;
  margin: 0 .5rem;
}
.masthead-links {
  font-size: 2rem;
}
.masthead-links a {
  color: rgba(255,255,255,.5);
  text-decoration: none;
  transition: all .15s linear;
}
.masthead-links a:hover {
  color: #fff;
}

@media (min-width: 38em) {
  .masthead {
    padding-top: 4rem;
    padding-bottom: 4rem;
  }
}


/*
 * Sections
 */

.heading {
  padding: 2rem 1rem 1.5rem;
  background-color: #dfe1e8;
}

@media (min-width: 38em) {
  .heading {
    padding: 3rem 3rem 2.5rem;
  }
}

.section {
  border-bottom: 1px solid #dfe1e8;
}


/*
 * Footer
 */

.footer {
  padding: 3rem 1rem;
  font-size: 90%;
  text-align: center;
}
.footer p {
  margin-bottom: .5rem;
}

.quick-links {
  list-style: none;
  margin-left: 0;
}
.quick-links li {
  display: inline;
}
