# Photocard Project

> Created during my time [@CodingBootcampsEurope](https://github.com/coding-bootcamps-eu).
> This repo was just for learning purposes and is not cleaned up.

In this task we were asked to recreate the following website based on a screenshot and a video using html and css.

![image](https://github.com/FlausenImKopf/photo-card-nachbau-mit-sandra/assets/88251068/72b1a254-783c-49bf-a834-b2f328bbcb0a)

https://github.com/coding-bootcamps-eu/2024-02/blob/main/Vollzeit/2024-03-08/task/photo_card_website.mp4

## This was the given html skeleton:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <title>Photo Card</title>
    <link
      rel="stylesheet"
      href="https://unpkg.com/modern-normalize@latest/modern-normalize.css"
    />
  </head>
  <body>
    <header>
      <h1>Photo<br />Card</h1>
      <p>
        On this website you can find a card with a random image from
        <a href="https://www.unsplash.com">unsplash</a>. Try to focus on
        creating the main structure of the HTML and CSS first. Then add the
        details bit by bit. If you make good progress, try to add an animated
        hover effect for the little icon in the image. Oh, and this paragraph
        must only be 65 characters wide.
      </p>
    </header>
    <main>
    </main>
  </body>
</html>
```

## This image link was provided

https://source.unsplash.com/600x600/?nature

## These were some added feature requests:

### 1. Add subtle Transition:
Add a hover effect to the card: the image is supposed to get slightly bogger and the card shadow changes to colour. Make sure the image stays within the limits of the card.

### 2. Dark Mode:
Add a media query prefers-color-scheme dark. Use custom properties for the color scheme

### 3. Add a Footer:
Add a three-fold footer. The footer design should contain Font Awesome icons and be structured like the following example:
![image](https://github.com/FlausenImKopf/photo-card-nachbau-mit-sandra/assets/88251068/1c67ae51-b303-4f41-aa00-277c10452bcd)

### 4. Create a list view:
Create a second stylesheet. The second stylesheet should have the styles for a "list view" of the photocards. Use a media query to make your website more responsive with this "list view" stylesheet.
![image](https://github.com/FlausenImKopf/photo-card-nachbau-mit-sandra/assets/88251068/2836322b-9136-46c1-a73a-3ebb1ba49266)







