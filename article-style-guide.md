# A Guide to Writing freeCodeCamp Guide Articles

The freeCodeCamp community is building a massive, searchable "Guide." This reference tool will eventually include thousands of articles that cover all areas of development, design, and data science - all written to be easily understood by people new to coding.

We welcome your help writing these articles. You don't have to be an expert in a topic to write about it - this entire guide is open source, so even if you make a mistake, another contributor will eventually correct it.

We've written this guide to writing guide articles to help you get started contributing.

**Table of Contents**

- [Article title](#article-title)
- [URL structure](#url-structure)
- [Modularity](#modularity)
- [General writing tips](#general-writing-tips)
- [Formatting example code](#formatting-example-code)
- [Proper nouns](#proper-nouns)
- [Where to get help](#where-to-get-help)

## Article title

Article titles should be as short, concise, and to-the-point as possible. We want campers to quickly find the information they're looking for, and the title should reflect the main theme of the article.

Here are some title examples:

- "HTML Lists"
- "CSS Borders"
- "JavaScript For Loop"

## URL structure

Guide pages will have a simple URL structure that can nest as deep as necessary. For example, there will be a section for Web Development, which will contain HTML and CSS subsections, which will then have their own subsections.

Here are some examples of URL structure:

- /Web-Development
- /Web-Development/CSS
- /Web-Development/CSS/Properties
- /Web-Development/CSS/Properties/CSS-Borders
- /Web-Development/HTML
- /Web-Development/HTML/Elements
- /Web-Development/HTML/Elements/HTML-Lists

You should capitalize words and replace spaces and other punctuation with a dash ("-").

There would be an article for each of the example URLs above. For the three HTML ones, the first URL would have an article that introduces and explains what HTML is, the second would have an article that explains what an HTML Element is, and the third would have an article that explains and gives examples of how to create lists in HTML.

## Modularity

Each article should explain exactly one concept, and that concept should be apparent from the article's title.

We can reference other articles by linking to them inline, or in an "Other Resources" section at the end of the article.

Our goal is to have thousands of articles that cover a broad range of technical topics.

## General writing tips

Before you begin writing, create an outline of the topic and think about any coding examples you'll use (if applicable). This helps to organize your thoughts and make the writing process easier.

Articles should be written with short, clear sentences, and use as little jargon as necessary. All jargon should be defined immediately in plain English.

The introduction paragraph should only be 1-2 sentences long and be a simple explanation of the main topic. It should limit the use of any links to other guide articles, as they can be distracting.

Keep paragraphs short (around 1-4 sentences). People are more likely to read several short paragraphs over a wall of text.

Use active voice instead of passive voice. Generally, it's a stronger and more straightforward way to communicate a subject. For example:
  - (Passive) The `for` loop in JavaScript is used by programmers to...
  - (Active) Programmers use the `for` loop in JavaScript to...

If you want to abbreviate a term in your article, write it out fully first, then put the abbreviation in parentheses. For example, "In computer science, an abstract syntax tree (AST) is ..."

Text should use the second person ("you") to help to give it a conversational tone. This way, the text and instructions seem to speak directly to the camper reading it. Try to avoid using the first person ("I", "we", "let's", and "us").

If there are other guide resources you think campers would benefit from, add them at the bottom in an "Other Resources" section.

You can add diagrams, graphics, or visualizations as necessary. You can also embed relevant YouTube videos and interactive REPL.it code editors.

Don't use emojis or emoticons in the guides. freeCodeCamp has a global community, and the cultural meaning of an emoji or emoticon may be different around the world. Also, emojis can render differently on different systems.

Use double quotes where applicable.

Format language keywords as code - this is done with the backtick key (located to the left of the "1" key on a US keyboard) in GitHub-flavored markdown. For example, put backticks around HTML tag names or CSS property names.

Use the Oxford Comma when possible. It’s makes things easier, clearer, and prettier to read.

## Formatting example code

Campers will likely use the guides as a quick reference to look up syntax. Articles should have simple real-world examples that show common-use cases of that syntax.

Here are specific formatting guidelines for any code:

- Use two spaces to indent
- JavaScript statements end with a semicolon
- Use double quotes where applicable
- Show generally-accepted best practices, particularly for accessibility
- Comments made should have a space between the comment characters and the comment themselves

    `// Fix this line`

## Proper nouns

Proper nouns should use correct capitalization when possible. Below is a list of words as they should appear in guide articles.

- JavaScript (capital letters in "J" and "S" and no abbreviations)
- Node.js

Front-end development (adjective form with a dash) is when you working on the front end (noun form with no dash). The same goes with the back end, full stack, and many other compound terms.

## Where to get help

Technical writing, or the literature of science and technology, is hard. You'll need to take a technical (usually abstract) topic and explain it in a clear, accurate, and objective manner. You'll likely go through several rounds of proofreading and editing before you're happy with the result.

Use the [Hemingway App](http://www.hemingwayapp.com/). There’s nothing magical about this simple tool, but it will automatically detect widely agreed-upon style issues:

- passive voice
- unnecessary adverbs
- words that have more common equivalents

The Hemingway App will assign a “grade level” for your writing. You should aim for a grade level of 6.

Also, there's a community of support from a whole team of contributors, whom you can bounce ideas off of and ask for input on your writing. Stay active in the [contributors room](https://gitter.im/freecodecamp/contributors) and ask lots of questions.

With your help, we can create a comprehensive reference tool that will help millions of people who are learning to code for years to come.
