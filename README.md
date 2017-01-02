# jquery-shortlink
A shortened version of the long URL often used for jQuery

## Why
According to [jQuery.com](https://jquery.com),

> jQuery is a fast, small, and feature-rich JavaScript library. It makes things
> like HTML document traversal and manipulation, event handling, animation, and
> Ajax much simpler with an easy-to-use API that works across a multitude of
> browsers. With a combination of versatility and extensibility, jQuery has
> changed the way that millions of people write JavaScript.

However, one of the most common ways to access jQuery and its wonderful
features is through a hideous link.

```
https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js
```

That link is suggested by [Bootstrap]
(http://getbootstrap.com/getting-started/#template), [W3Schools]
(http://www.w3schools.com/jquery/jquery_get_started.asp), and many other
websites. However, this link is very long, _especially_ when combined with
other text like a `script` tag.

```HTML
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
```

With the added `script` tag it is already 81 characters (over the 79 or 72
characters-per-line limit many want to use). With an added 4 characters of
indentation, it is 85 characters.

## The solution
Based on the problems above, I propose that rather than using the
aforementioned link, we use one like this.

```
https://goo.gl/D5GOyG
```

Isn't it so nice and pretty?

There are actually _two_ links to note here.

1. The link for jQuery 1.12.4, which is [https://goo.gl/D5GOyG]
(https://goo.gl/D5GOyG).
2. The link for jQuery 3.1.1, which is [https://goo.gl/511MjA]
(https://goo.gl/511MjA).

For `script` tags you can also choose one of two choices.

1. The `script` tag for jQuery 1.12.4.

    ```HTML
    <script src="https://goo.gl/D5GOyG"></script>
    ```

2. The `script` tag for jQuery 3.1.1.

    ```HTML
    <script src="https://goo.gl/511MjA"></script>
    ```
