---
layout: post
title: "Why Programming Languages Die"
thumbnail: [/assets/images/posts/rip.jpg, "image of a gravestone"]
description: "A blog post considering why some programming languages die and some survive"
preview: true
---

{% include post-image.html link="/assets/images/posts/rip.jpg" alt="image of a gravestone" %}

Hundreds, maybe even thousands of programming languages have existed since the days of the first computers. Some languages have lasted the test of time, while others have been snuffed out soon after their conception. This made me ponder the question, "Why do languages such as Fortran which is now over 60 years old seem to survive the test of time, while newer more capable languages seem to fade into obscurity?".
<!--more-->
For a programming language to survive I believe four major factors come into play. The languages niche, relevance, popularity and accessibility.

## The niche

Almost all long-lived programming languages have a well-defined niche. Being able to excel in areas that others cannot is a benefit, this truth holds for programming languages (and the underlying technologies that support them) as does it for humans. Fortran is a good example of a language that has survived due to its niche. It had been "designed from the ground-up for computationally intensive applications in science and engineering" (fortran-lang.org, 2020), and so it is often used by major tech players such as IBM and Oracle. While the C language, on the other hand, is around 50 years old and had found its niche in general computing system environments such as system programs, applications, drivers and utilities. Ada, around 40 years old, is a fairly obscure language unless you happen to work in the defence and aerospace sectors.

### Relevance

While relevance is strongly linked to a niche, other factors can influence language relevance. Fortran, C and Ada have had numerous language revisions over the years to maintain their relevance. This is often brought about through the advancement of hardware technology or the discovery of new programming paradigms. And so, languages evolve similar to how spoken languages do. With that in mind a well-maintained language, its syntax and various implementations must remain relevant to the times.

### Accessibility

The more accessible a language is to a wider audience the more influence it will garner. Nearly all the most popular languages today are freely available to download and use. This was not always the case because I remember a time when learning to program in a new language was a real privilege. Looking back to when I started programming in the late 90s, it was all too common that the budding developer had to purchase not only compilers for a specific language but also a supporting IDE, libraries and related licenses. All of which would cost a small fortune. This is why my first introduction to programming was not at home but in high school. Today computing is cheap, someone can learn to program on a small inexpensive computer such as a Raspberry PI, there exist many IDE and software development tools that are freely available to use. And while paying the financial expense in the form of licenses and subscriptions for the privilege of using a language still exists, such costs are usually directed towards those developing software under very specialized circumstances. Regardless, the point is that accessibility to the language is an important factor in remaining relevant in today's world. Most programming languages should ideally be freely accessible for them to gain popularity. 

### Popularity

Popularity has a direct relationship to the previous three factors. In that, a popular language will exist within a niche and will appeal to a certain type of developer. The language must be relevant and perform the function of developing software for that niche. Lastly, a general rule could be stated that the more accessible a language is the more popular it can become. Even poorly conceptualized programming languages can become popular under the right conditions. JavaScript or rather ECMAScript is an example of how an initial poorly conceived language became popular, because it filled a very specific niche, had few competitors, and was made widely available across many devices. One could say that JS's popularity today is due to it holding a de facto position for many, many years.

## How they die or are at least banished to obscurity

Fundamentally, lacking any of the first three factors mentioned can cause the death of a language, that is lacking a niche, relevance and availability.

### Death by niche

There are two main ways a programming language can die by niche. The first is that the niche disappears. Most likely this would be brought about by some technological revolution. If the niche goes the language will most likely go with it. An example of a language that is on death's door is Adobe's ActionScript, which was designed for scripting Adobe Flash applications and animations. Over time the support for adobe flash animations waned as the world gradually came to favour HTML5's canvas animations, which utilise JavaScript. The possibility of there being any real future for ActionScript is unlikely. 
This leads nicely to the second way a language can die by niche: a programming language can be killed off by another language. For developing, windows applications the scripting language VB (Visual Basic) was superseded by Visual Basic .NET. VB only lasted seven years, a short life, but during its day it was very popular. Microsoft saw the future in the .NET framework, and because VB's technologically lacked compatibility with .Net, Microsoft abandoned it. Thus VB .NET was born to allow developers of VB to transition over to .NET. Both languages are syntactically similar yet are fundamentally different in their own right. 

### Death by unavailability

A fairly common occurrence throughout the history of programming languages is that a language will die because it is not accessible to a wider community. Most languages are developed by large enterprise organizations. The cost to do so will likely be great, so it is not uncommon for a business to try and recuperate some of the costs by proposing to release their language to a wider audience. How they do so will often determine if a language will gain popularity or not. Often if the programming language and accompanying technology are accessible to a large community then it has a better chance of surviving. 
Death by irrelevance
Languages can become irrelevant over time, and there can be many reasons for this happening. It could be due to the neglect of those overseeing the language or perhaps a new more relevant language appears on the scene which outcompetes it. Often when a language becomes irrelevant there is some governance issue at hand.

## Considering some languages

### Go lang

* Niche: while it can be used as a general-purpose language, the language, brought to us by Google is specialized in developing software services for cloud-based computing and distributed systems.
* Availability: Freely available
* Popularity: Fairly popular amongst its users.
Future: One of Go's main selling points is that it promotes a faster software development cycle without having to worry about the likes of garbage collection, as is the case with C++. It has been alleged that Go has a similar if not a slightly better performance when compared to Java and considering that Java can fulfil a similar role to Go, it raises the question of why anyone should use Go when there's Java. Yet, technologies like Docker have in their way allowed programs and applications to be shared amongst devices comparable to what was seen with Java applications running on the JVM. So Go, as I see it has a long future ahead of it, it has a well-defined niche, it is relevant, available and popular. 

### Java

* Niche: Android and enterprise services, provides cross-platform applications by utilizing a JVM.
* Relevance: Holds the position as one of the most popular and widely used programming languages of all time. However, its wide use is largely due to it once being the language of Android and cross-platform application development. This position has declined much over recent years with Kotlin being pushed by Android as the preferred language for developing apps. Java is still used by enterprise systems and back-end services and this is where its relevance will remain for many years to come, especially regarding legacy systems.
* Availability: Propriety and Open source development tools are available.
* Popularity: Popular by default, as it used to hold a monopoly in its niche.
* Future: As someone fairly familiar with coding in Java, it is my view that Java will be in a state of slow decline over the coming years. This is because the most important concept to ever come out of the Java project was never the language itself but that of the JVM (Java Virtual Machine). Java the language may die one day, perhaps in a few decades from now, but the JVM will live on. A few third parties, like IBM, have been developing their very own JVM. Additionally, there has been an ongoing trend of maintaining the JVM, while providing support for other languages to compile their code into byte-code to run on the JVM. Groovy and Scala are two such examples, so coding in Java is not a requirement. Another thing to consider is that Oracle has stopped releasing new versions of the JRE (Java Runtime Environment) for desktop computers at version 8. Essentially this means that any modern desktop Java application must ship a modern JRE along with its code. This kind of defeats the point of cross-platform compatibility, as conceptually only one JRE should be installed per device. So while the official JDK (Java Development Kit) continues to be developed for enterprise business systems, the average developer who wants to provide software to the average person is left behind. In the future, we may end up seeing several new languages being developed for the third party implementations of the JVM, but I don't see Java having a bright future ahead.

### Python
* Niche: a general-purpose cross-platform scripting language, with access to an extensive collection of modules. This programming language now has the reputation of being the Swiss army knife of scripting languages. Over the past two decades, it has gained fame in the areas of data analysis, research, business and even server-side scripting. In many ways, Python is unique as it has found its niche as being The Jack of all trades. From the beginning, Python has been community-driven and open source.
* Available: free to download install and run.
* Popularity: If a certain functionality is lacking, there is a community-based incentive to implement the missing functionality in the form of a module. In many ways, this continuous community involvement has resulted in the programming language remaining relevant. Popularity has been on a steady increase, especially around the early 2010s. The language itself has a shallow learning curve making it ideal as a first language and is used regularly as an aid in teaching the fundamentals of computer and data science. As an interpreted programming language. the performance of a Python program is lacking when compared to the same program written in Java (a JIT compiler) or C++ (compiler-based). Yet its popularity and adaptability make up for what it lacks in performance. In truth, it could be argued that the performance provided by a Python program is adequate for most projects.
* Future: As the speed of computer hardware increases, the excuse of not choosing Python simply based on performance will no longer hold as much weight as it has done. I feel that as long as there is a need for a good scripting language and the python community support remains strong, the language has a long life ahead of it. That being said, one downside to Python is the sheer amount of modules available and the support needed to ensure that these modules are maintained over time. The idea of a type of dependency rot is something to take into consideration, that is dependencies expose programs to security vulnerabilities simply because they are no longer maintained.
 
## Final thought

Fundamentally, questioning how much life a programming language has left in it is a primary concern of not only software developers but also businesses. That is, there is a need to ensure the technologies used today to remain relevant for tomorrow within their respective niche. And if we can foresee the potential decline of a particular piece of technology, this provides us with foresight, allowing us to maintain a competitive advantage. Well, that's the thought anywa