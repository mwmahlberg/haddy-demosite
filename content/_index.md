+++
date = '2025-04-08T08:26:13+02:00'
draft = false
title = 'Welcome'
author = 'Markus Mahllberg'
+++


This is a demo site for haddy - [**H**ugo on C**addy**][haddy].

It uses the [relearn theme][hugo:relearn].

Some of its features include

* [mermaid][mermaid] support:

    ```mermaid {align="center" zoom="true"}
    graph LR;
    If --> Then
    Then --> Else
    ```

* Trees:

    ```tree
    - home | folder
        - [.config](http://example.com) | folder
        - My Documents | folder | magic
          - home.php | fa-fw fab fa-php | #888cc4
    ```

* Awesome code highlighting:

    ```py {lineNos="true" wrap="true" title="python"}
    print("Hello World!")
    ```

See the [theme's shortcodes][relearn:shortcodes] for more.

[haddy]: https://github.com/mwmahlberg/haddy "haddy project site on GitHub"
[hugo:relearn]: https://themes.gohugo.io/themes/hugo-theme-relearn/ "Relearn Theme project page"
[mermaid]: https://mermaid.js.org "Mermaid.js"
[relearn:shortcodes]: https://mcshelby.github.io/hugo-theme-relearn/shortcodes/index.html
