# highlightjs Reference

## Getting Started

    <link rel="stylesheet" href="/path/to/styles/default.css">
    <script src="/path/to/highlight.min.js"></script>
    <script>hljs.initHighlightingOnLoad();</script>

This will find and highlight code inside of `<pre><code>` tags; it tries to detect the language automatically. If automatic detection doesn’t work for you, you can specify the language in the class attribute:

## `html` class attributes

If automatic detection doesn’t work for you, you can specify the language in the class attribute:

    <pre><code class="html">...</code></pre>

Classes may also be prefixed with either language- or lang-.

    <pre><code class="language-html">...</code></pre>

## Plaintext and Disabling Highlighting

To style arbitrary text like code, but without any highlighting, use the plaintext class:

    <pre><code class="plaintext">...</code></pre>

To disable highlighting of a tag completely, use the nohighlight class:

    <pre><code class="nohighlight">...</code></pre>

## Supported languages

https://github.com/highlightjs/highlight.js/blob/master/SUPPORTED_LANGUAGES.md



# References
* https://highlightjs.org/usage/
* https://highlightjs.org/static/demo/

