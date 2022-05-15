# Dojo - Landing Page

Welcome to the Dojo Landing Page repository!

In this Dojo, we are going to develop a Landing Page for the LGPDes confectionery. Use the `index.html` and `style.css` files to write your code.

## Requirements

1. Create a header for the page:

    - Add an `id` to your header;
    - Make the background color `#FFC5E5`;
    - Make the position absolute;
    - Use the `left` and `top` properties to strip whitespace.

2. Create a menu for the header:

    - Add 3 `h3` elements with the names _"ABOUT"_, _"SERVICES"_ and _"CONTACT"_, which should be to the right of the header;
    - Add an `h1` element with the name _"LGPDoces"_, which should be on the left of the header;
    - **Tip:** Use the `display: inline-block`.

3. Make **all** the fonts of the **Arial** family and color `#1f1c0d`.
4. Make the `body` color `#FEE9FC`.
5. Create a **section** and assign a `class` and an `id` to it:

    - Make this section have margins in relation to the **top**, **right** and **left**;
    - Create an `h2` with the text _"About us"_ inside the section and add an `id` to it;
    - Create a paragraph with the text _"We are LGDoces, a confectionery that has been in the market for 10 years offering the best in confectionery. Our mission is to bring more flavor and joy to all consumers and you can be one of them! that we offer."_ and add an `id` to it;
    - Make the title have a size of `32px` and a **margin** in relation to the left;
    - Make the **paragraph** `20px` in size.

6. Create a **section** and assign a `class` and an `id` to it:

    - Make this section have margins in relation to the **top**, **right** and **left**;
    - Create an `h2` inside this section with a font of `32px` and a margin in relation to the **left**;
    - Inside the `img` folder, there are 4 images of products offered. For each image, inside the section created in this step (6), create an `article` and place the image and the related text inside it. For the cake _"We have delicious cakes for you!"_; for the brigadiers _"Try our famous gourmet brigadiers"_; for cupcakes _"The best cupcakes for your parties and everyday life"_; for the pie _"Try our tasty pies too"_. Code example:

        ```
         <section>
            <h2 id="services-title">Our Services</h2>
              <article>
                  <img src="./img/bolo.jpg" alt="photo chocolate cake with strawberries" class="right">
                  <h3 class="product">We have delicious cakes for you!</h3>
              </article>
         </section
        ```

7. Make the images side by side with their respective texts. Example: next to the cake image must be the text referring to it.
8. Create a **section** and assign a `class` and an `id` to it:

    - Inside this section, add an `h2` with the text _"Contact us through our social networks!"_ ;
    - In the `img` folder there are 3 images referring to social network icons. For each of the icons, inside the section created in this step (8), create an element `a` that will receive the icon of the social network so that, when clicked, it will redirect to a new page. Code example:

    ```
    <a href="https://www.whatsapp.com/?lang=pt_br" target="_blank">
        <img src="./img/whatsapp.png" alt="WhatsApp Icon" class="socialmedia-icon">
    </a>
    ```

    - Make icons `64px` wide;
    - Remove the `text-decoration` attribute from all `a` tags.

9. Create a `footer` for the page:

    - Make this footer have an `id`;
    - Create a paragraph inside the footer with the text _"All rights reserved | LGDoces | 2022"_;
    - Set a `height` for the footer;
    - Set that its width will occupy 100% of the screen;
    - Make its position absolute and use the `left` property to remove whitespace;
    - Set a margin in relation to the **top**;
    - Make the footer background color `#FFC5E5`;
    - Set a margin in relation to the **left** and **top** for the **paragraph**.

10. Create an internal navigation on the site:
    - Use the `a` tag to create an internal navigation through the site's header menu. By clicking on "ABOUT", the person should be redirected to the first section (which talks about the bakery); when clicking on "SERVICES", you should be redirected to the section that lists the sweets produced; by clicking on "CONTACT", you should be redirected to the section with links to social networks.
