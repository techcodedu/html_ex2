# html_ex2

```markdown
## Exercise: Upgrading Non-Semantic to Semantic

**Objective**: Reinforce your understanding of semantic HTML by taking a non-semantic web page and converting it to use meaningful, semantic tags.

### Starting Code: Non-Semantic HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Space Exploration</title>
</head>
<body>
    <div>
        <h1>The Final Frontier</h1>
        <div>
            <ul>
                <li><a href="#planets">Planets</a></li>
                <li><a href="#stars">Stars</a></li>
                <li><a href="#galaxies">Galaxies</a></li>
            </ul>
        </div>
    </div>

    <div id="planets">
        <h2>The Wanderers of the Sky</h2>
        <p>Planets have fascinated humanity for millennia, serving both as reference points in the sky and as inspirations for various myths and legends.</p>
    </div>

    <div id="stars">
        <h2>Our Sun and its Kin</h2>
        <p>Stars are giant nuclear reactors producing light and heat. Our very own sun is a star, and its energy allows life to thrive on Earth.</p>
    </div>

    <div id="galaxies">
        <h2>Island Universes</h2>
        <p>Galaxies are vast collections of stars, dust, and dark matter, held together by gravity. Our Milky Way is just one of billions in the universe.</p>
    </div>

    <div>
        <p>Discover the vastness of the universe and our place within it.</p>
    </div>
</body>
</html>
```

### Instructions:

1. Launch [CodePen](https://codepen.io/) and start a new pen.
2. Paste the "Space Exploration" non-semantic HTML provided into the HTML section of your pen.
3. Your challenge is to enhance this HTML using semantic tags. Replace the generic `div` tags with the most suitable semantic tags. Think about using:
    - `header`
    - `nav`
    - `section`
    - `footer`
    - And others you find relevant!
4. The appearance of the page should not change, only the structure and clarity of the HTML code.
5. After refining your code, save your pen and share with your peers.

**Bonus Challenge**: Incorporate the `main` and `article` tags appropriately within your content. Can you explain why you placed them where you did?
