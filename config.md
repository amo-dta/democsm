# Site Configuration

This file contains configuration options for the Alpha - Digital a11y website.

## Menu Options

### Order Menu Items

To specify the order of menu items, use the following option:

```yaml
menu_order: alphabetical
```

Set this to `alphabetical` to order menu items alphabetically. If you want to maintain the order based on the file list returned by the GitHub API, you can set it to `default` or remove this option.

## Footer Configuration

### Footer File Location

Specify the location of the footer markdown file:

```yaml
footer_file: footer1.md
```

This should be the name of the markdown file in your content repository that contains the footer content.

## Future Configuration Options

As the site grows, you can add more configuration options here. For example:

```yaml
# site_title: Alpha - Digital a11y
# theme: light
# show_author: true
```

Remember to update the React application to read and apply these configuration options.