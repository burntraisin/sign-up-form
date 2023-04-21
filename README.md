# sign-up-form
This is a simple sign-up form for TOP's intermediate HTML and CSS Course.

# What I learned
* background-image
    * A helpful snippet:
        ```css
        background-size: cover; /* Resizes the bg img horizontally and vertically depending on the window's size while maintaining its aspect ratio */
        height: 100vh;
        overflow: hidden;
        background-repeat: no-repeat;
        ```
* Hiding elements but allow screen readers to see it
    * Snippet ([source](https://www.nomensa.com/blog/how-improve-web-accessibility-hiding-elements)):
        ```css
        .hide-element {
            border: 0;
            clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
            clip: rect(1px, 1px, 1px, 1px);
            height: 1px;
            margin: -1px;
            overflow: hidden;
            padding: 0;
            position: absolute;
            width: 1px; 
        }    
        ```

# Future todos
* Responsiveness
* User-friendliness