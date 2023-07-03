---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: home
---

## Description
{{ site.description }}

See some [examples of carpentry lessons]({{ page.lesson-example }}).

More details about this website are available from the [About page](about).


{% assign favourite = site.books | where:"author", "Barbara Kingsolver" | first %}
One of my favourite books is {{ favourite.title }}.
[See my reading list](about#books)

If you could recommend me one book, what would it be? [I'd love to hear about it, or any thoughts you may have!](mailto:{{ site.email }})
