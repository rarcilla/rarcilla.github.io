---
layout: post
title: 4 Things I Learned from Building my first SwiftUI Project
description:
---

1. Encapsulation is key for reactive programming not only for organization purposes, but also to improve application runtime. Remember the ten subview limit!

2. Develop with relative sizes in mind, its a good idea to take care of this from the onset to avoid having to go back to refactor later. (I'll make sure to prioritize this for next time! 😬🤞) `GeometryReader` is your friend!

3. Reactive programming projects won't always necessarily follow the MVVM pattern. In simpler and smaller projects such as this one, "MV" will suffice.

4. The different SwiftUI property wrappers and their use cases are _extremely_ important to understand! It's easy to get them confused. I referred to this [article by Jared Sinclair](https://jaredsinclair.com/2020/05/07/swiftui-cheat-sheet.html?utm_campaign=%20SwiftUI%20Weekly&utm_medium=email&utm_source=Revue%20newsletter) more than a handful of times.

---

View the project [here](https://rarcilla.github.io/projects/3_covid19-tracker/).
