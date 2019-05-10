# About

The wrapper in this repository allows to use the [Bulma CSS framework](https://bulma.io/) (currently in version 0.7.4) in SharePoint pages without causing collisions with the global SharePoint styles.

# Usage

In your HTML source code which you want to add to a SharePoint page, simply add the following line:

```html
<link rel="stylesheet" href="https://sharepoint-bulma.netlify.com/sharepoint-bulma.css">
```

This provides the entire, original Bulma library to all child elements inside a wrapper element with the class ``sharepoint-bulma``. To this end, create a root element that wraps your HTML source code to which you add the class ``sharepoint-bulma``.

Complete example:

```html
<!-- Reference to the wrapped Bulma library -->
<link rel="stylesheet" href="https://sharepoint-bulma.netlify.com/sharepoint-bulma.css">

<!-- Wrapper element -->
<div class="sharepoint-bulma">

    <div class="card">
        <div class="card-content">
            <p class="title">“There are two hard things in computer science: cache invalidation, naming things, and off-by-one errors.”</p>
            <p class="subtitle">Jeff Atwood</p>
        </div>
    </div>

</div>
```
