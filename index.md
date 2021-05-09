# Introduction

## Motivation

TBD

## Getting started

TBD

# Tutorials

## Add a new tutorial

Run the following command to add a new presentation in Hugo's `content` directory:

```
hugo new --kind tutorial subject-two/my-tutorial
```

## Content syntax

The presentations can be created using [Markdown](https://daringfireball.net/projects/markdown/) syntax.

Along with the Markdown syntax, you can use the following custom [Hugo shortcodes](https://gohugo.io/content-management/shortcodes):

**Info callout box**

{% raw %}
```
{{< info >}}
Lorem [impsum](https://example.com) dolor sit amet.
{{< /info >}}
```
{% endraw %}

**Tip callout box**

{% raw %}
```
{{< tip >}}
Lorem [impsum](https://example.com) dolor sit amet.
{{< /tip >}}
```
{% endraw %}

**Warning callout box**

{% raw %}
```
{{< warning >}}
Lorem [impsum](https://example.com) dolor sit amet.
{{< /warning >}}
```
{% endraw %}

# Presentations

## Presentation syntax

The presentations can be created using plain HTML with the [reveal.js](https://revealjs.com/) syntax.

## Add a new presentation

Run the following command to add a new presentation in Hugo's `content` directory:

```
hugo new --kind presentation subject-two/my-presentation
```

# Imprint

See [experimental-software.com](http://notes.experimental-software.com/Impressum.html)