---
title: Facets
feature_text:
  A demo of Markdown and HTML includes
feature_image: "https://picsum.photos/2560/600?image=873"
excerpt: "A demo of Markdown and HTML includes"
aside: true
---
- [Albums](https://rjssue.github.io/TS/albums/)

    - [Taylor Swift](https://rjssue.github.io/TS/albums/#taylor-swift)

  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/zh/0/00/Taylor_Swift_album.jpg">
    <figcaption class="caption">Taylor Swift Album Cover</figcaption>
  </figure>

    - [Fearless](https://rjssue.github.io/TS/albums/#fearless-taylor-s-version)

    <figure class="figure  figure--center">
      <img class="image" src="https://upload.wikimedia.org/wikipedia/en/8/86/Taylor_Swift_-_Fearless.png">
      <figcaption class="caption">Fearless Album Cover</figcaption>
    </figure>
    <figure class="figure  figure--center">
      <img class="image" src="https://upload.wikimedia.org/wikipedia/en/5/5b/Fearless_%28Taylor%27s_Version%29_%282021_album_cover%29_by_Taylor_Swift.png">
      <figcaption class="caption">Fearless (Taylor's Version) Album Cover</figcaption>
    </figure>

    - [Speak Now](https://rjssue.github.io/TS/albums/#speak-now-deluxe)

  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/en/8/8f/Taylor_Swift_-_Speak_Now_cover.png">
    <figcaption class="caption">Speak Now Album Cover</figcaption>
  </figure>

    - [Red](https://rjssue.github.io/TS/albums/#red-taylor-s-version)

    <figure class="figure  figure--center">
      <img class="image" src="https://upload.wikimedia.org/wikipedia/en/e/e8/Taylor_Swift_-_Red.png">
      <figcaption class="caption">Red Album Cover</figcaption>
    </figure>
    <figure class="figure  figure--center">
      <img class="image" src="https://upload.wikimedia.org/wikipedia/en/4/47/Taylor_Swift_-_Red_%28Taylor%27s_Version%29.png">
      <figcaption class="caption">Red (Taylor's Version) Album Cover</figcaption>
    </figure>

    - [1989](https://rjssue.github.io/TS/albums/#1989-deluxe)
    
  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/en/f/f6/Taylor_Swift_-_1989.png">
    <figcaption class="caption">1989 Album Cover</figcaption>
  </figure>

    - [Reputation](https://rjssue.github.io/TS/albums/#reputation)

  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/en/f/f2/Taylor_Swift_-_Reputation.png">
    <figcaption class="caption">Reputation Album Cover</figcaption>
  </figure>

    - [Lover](https://rjssue.github.io/TS/albums/#lover)

  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/en/c/cd/Taylor_Swift_-_Lover.png">
    <figcaption class="caption">Lover Album Cover</figcaption>
  </figure>

    - [Folklore](https://rjssue.github.io/TS/albums/#folklore-deluxe-version)

  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/en/f/f8/Taylor_Swift_-_Folklore.png">
    <figcaption class="caption">Folklore Album Cover</figcaption>
  </figure>

    - [Evermore](https://rjssue.github.io/TS/albums/#evermore-deluxe-version)

  <figure class="figure  figure--center">
    <img class="image" src="https://upload.wikimedia.org/wikipedia/en/0/0a/Taylor_Swift_-_Evermore.png">
    <figcaption class="caption">Evermore Album Cover</figcaption>
  </figure>

    - [Other Singles](https://rjssue.github.io/TS/albums/#single)

- Theme
    - love
        - falling in love
        - daily love life
        - fantasy
    - break-up
        - apology
        - redeem
        - reflection
        - accusation
    - death
        - war
        - pandemic
        - cancer
    - fame
        - slander
        - jealousy
    - LGBT
- Emotion
    - happy
    - sad
    - angry
    - yearning
- Genre
    - Pop
    - Country
    - Folk




# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>A small element</small>

[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
