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

# CLI Unit Test Generator
Using OpenAI API, Spring Boot, Picocli, and GraalVM native-image.


by Audrey Carmel Jay J. Nanual

---
layout: center
---

# What does the app do?

- automate the process of generating unit test code for a given function or module
- utilizes the **OpenAI API** to generate unit tests based on user-specified inputs (programming language, function to test)
- built using the **Spring Boot** framework and the **Picocli** library for parsing command-line arguments
- compiled using the **GraalVM native-image** compiler

<!-- 

This app automates the process of generating unit test code for a given function or module, which can save developers significant time and effort.

One of the key features of this app is that it utilizes the OpenAI API to generate unit tests based on user-specified inputs such as programming language and the function to test. This allows developers to leverage the power of AI to generate quality test cases quickly and accurately.

The app is built using the Spring Boot framework and the Picocli library for parsing command-line arguments, which makes it easy to use and integrate into existing workflows. Additionally, the app is compiled using the GraalVM native-image compiler, which results in faster startup times and reduced memory footprint.

Overall, this CLI unit test generator app can be helpful for developers who want to automate the process of generating unit tests and improve the quality and reliability of their code.

 -->

---
layout: center
---

# OpenAI API

- provides developers with access to a range of advanced AI technologies developed by OpenAI
- can be used to build applications and services that leverage state-of-the-art AI models without needing to train and maintain our own models
- access is available through a paid subscription service

<!-- 

The OpenAI API is a cloud-based API that provides developers with access to a range of advanced AI technologies developed by OpenAI, including natural language processing (NLP), computer vision, and reinforcement learning.

Developers can use the OpenAI API to build applications and services that leverage state-of-the-art AI models without needing to train and maintain their own models. The API provides easy-to-use interfaces for generating natural language, performing language translation, recognizing images, and solving complex tasks through reinforcement learning.

The OpenAI API is designed to be accessible and flexible, allowing developers to integrate AI capabilities into their projects regardless of their level of expertise. Developers can interact with the API using a variety of programming languages and platforms, including Python, Node.js, and RESTful APIs.

Access to the OpenAI API is available through a paid subscription service, which provides developers with access to compute resources and a range of pre-trained AI models that can be used for a variety of tasks.

 -->

---
layout: center
---

# Spring Boot

- used to create production-grade Spring-based applications with minimum configuration
- reduces boilerplate code and makes it easier to develop, test, and deploy Java-based web applications


<!-- 

Spring Boot is a Java-based framework used to create production-grade Spring-based applications with minimum configuration.

It simplifies the development process by providing default settings and configurations, eliminating the need for manual configuration.

It includes an embedded server and is designed to be opinionated and production-ready.

Overall, Spring Boot reduces boilerplate code and makes it easier to develop, test, and deploy Java-based web applications.

 -->

---
layout: center
---

# Picocli

- a Java library for parsing command-line arguments and generating usage help messages
- provides an API for defining options, parameters, and subcommands for command-line interfaces in Java applications

<!-- 

Picocli is a Java library for parsing command-line arguments and generating usage help messages.

It provides a simple and concise API for defining options, parameters, and subcommands for command-line interfaces in Java applications.

With Picocli, developers can easily parse command-line arguments, handle errors, and generate usage help messages.

It also supports features like type conversion, validation, and command-line completion.

Picocli is lightweight and can be easily integrated into existing Java projects.

 -->

---
layout: center
---

# GraalVM native-image

- a tool that allows developers to compile Java applications into native executable binaries that can run without the need for a JVM

<!-- 

GraalVM native-image is a tool that allows developers to compile Java applications into native executable binaries that can run without the need for a JVM.

This can result in faster startup times and reduced memory footprint.

It works by creating a custom runtime image that includes only the required classes and libraries.

GraalVM native-image is useful for deploying Java applications in environments where a full JVM is not available or not desirable, and for packaging applications as a single, self-contained executable file.

 -->