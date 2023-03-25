---
# theme for all slides; choose here: https://sli.dev/themes/gallery.html#official-themes
theme: default

# background photo
background: "/assets/images/cat.jpeg"

# apply any windi css classes to the current slide
# https://windicss.org/features/
class: text-center

# tool used for highlighting code
highlighter: shiki

# show line numbers when showing code blocks
lineNumbers: true

# some information about the slides (you can write in markdown syntax)
info: |
    ## audrey's slidev template
    github: https://github.com/audreycj

# persist drawings in exports and build
drawings:
    persist: false

# slide transition
transition: slide-left

# use UnoCSS
css: unocss
---

# こんにちは

this is audrey's personal template for slidev projects

---
layout: center
transition: slide-left
---

# slide with bullet points

paragraph stuff

- idea 1
- idea 2

---
layout: center
transition: slide-left
---

# slide with code snippet

```
System.out.println("こんにちは！お元気ですか？");
```

---
layout: center
transition: slide-left
---

# experimenting with Windi CSS

<p class=""> what the fuck </p>

<style>
.font-mono {
  font-family: ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace;
}
</style>

