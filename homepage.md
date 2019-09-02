# Home page

> Create a page that will display information about Marie Curie

The page should display:

  * page title with the text: Marie Curie
  * a page description with the text: Brief biography of Polish-French physicist Marie Curie.
  * page headline with the text: Marie Curie
  * date of birth and death: 7 November 1867 – 4 July 1934
  * a quote: Nothing in life is to be feared, it is only to be understood. Now is the time to understand more, so that we may fear less.
  * a link to list of quotes with text View all famous quotes (linked to the quotes.html page)
  * list of links to page sections for quick jump to section navigation with the following sections:

```
  - Life
    - Early years
    - New life in Paris
    - New elements
    - Nobel prizes
    - Death
  - Legacy
  - Awards
```

  Note: Life, Legacy and Awards are on the same level.
  While Early years, New life in Paris, New elements, Nobel prizes and Death are all on the same level, nested in Life.

You can find the content for each section here:

  * Content for section Early years: content/life/early-years.txt
  * Content for section New life in Paris: content/life/new-life-in-Paris.txt
  * Content for section New elements: content/life/new-elements.txt

    images:
      link: https://upload.wikimedia.org/wikipedia/commons/6/6c/Pierre_and_Marie_Curie.jpg

      text: Pierre and Marie Curie in the laboratory

      add a link for the word Pierre leading to https://en.wikipedia.org/wiki/Pierre_Curie

  * Content for section Nobel Prizes: content/life/nobel-prizes.txt

  * Content for section Death: content/life/death.txt

    images:
      text: 1935 statue, facing the Radium Institute, Warsaw

      link: https://upload.wikimedia.org/wikipedia/commons/6/6c/Sklodowska-Curie_statue%2C_Warsaw.JPG

  * Content for legacy section:
    content/legacy/content-1.txt,
    followed by content/legacy/quote.txt,
    followed by content/legacy/content-2.txt

  * Content for awards section:
    content/awards/content-1.txt,
    followed by content/awards/awards-list.txt,
    followed by content/awards/content-2.txt

Whenever a section includes images, add it between paragraphs.
