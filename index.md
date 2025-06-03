---
layout: home
title: "Welcome to My Site"
excerpt: "A place where I document my learning journey, projects, and thoughts."
author_profile: true
---

# Hello, I'm Joy 👋

Welcome to my personal website! I'm passionate about **Artificial Intelligence**, **Web Development**, and **Data Science**. Here’s a bit of what you’ll find:

## 🛠 Projects

- **Payroll System** — Full-stack project using C#, MySQL, React.js, and TypeScript.
- **Lastles** — A ladies’ shoe e-commerce site.
- **MemorySoft** — A payroll and HR platform.

## 📚 Recent Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) — _{{ post.date | date: "%B %d, %Y" }}_
{% endfor %}

## 💡 About Me

I'm from **Kericho, Kenya**, and I love reading, swimming, and discovering new ways to grow. Currently diving deep into **AI and Data Science**, especially in the healthcare space.

> _"When you want something, all the universe conspires in helping you to achieve it."_ — Paulo Coelho, *The Alchemist*

---

*Thanks for stopping by! Feel free to explore and connect with me on [Instagram](https://instagram.com/_ms.cheruto).*
