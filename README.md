# Technical debt

Since I started to like writing blogs, I think it became around time to write one about one of my favorite topics: technical debt. Before you read this, note that I'm not a manager, that I don't know anything about economics and that I'm only sharing my own thoughts here. It's ok to disagree with me, but now you have at least the ability to read my point of view.

## Objectively, what is tech debt?
According to the free encyclopedia Wikipedia, technical debt means 'a concept in programming that reflects the extra development work that arises when code that is easy to implement in the short run is used instead of applying the best overall solution'. So, if you avoid time and 'hack some stuff together', it will decrease overall quality and could potentially cost the company a lot of money.

## Bad code
A product where technical debt occurs, usually has a bad codebase. There are a lot of things that could make a codebase look bad. The most important reasons in my opinion are lack of structure and readability. Structure because you need to build further on the project. It needs to be easy to change a single part of the product and everybody needs to understand the source code. Whenever something is not clear, a programmer could be tempted to create a new implementation instead of using code that already exists. It's also possible you no longer remember the purpose of a method or function. In case something is not clear and there's a hard deadline, it's very tempting to make assumptions on how the code works and those assumptions could be horribly wrong.

## The developers fault?
Since I'm a developer myself, I wouldn't declare that all of this is the developers fault. I mean, it can be, because someone is inexperienced or lazy, but it's usually not the only problem. Technical debt is all about attitude, both your personal attitude as well as the attitude of the company. Whenever there are strict rules about code styling, best practices, sharing knowledge, code reviews, .... everybody will live them by.

Whenever no one in a company cares about healthy code, a new developer won't neither. He could try, but in the end, everybody will finish their tasks faster than he does and will probably even receive negative feedback about wasting time.

## Time, quantity, quality
When building a product, basically three things are really important: time, quantity and quality. Companies tend to care the most about time and quantity. A mentallity like 'create as much as possible as quickly as possible'. This is how technical debt gets created. When time decreases and quantity increases, quality will decrease as well. You could even use it as a formula: ql = t / qn (call it the Jakez debt formula). Why did I make up a formula? To make clear there is no possible way to increase all three factors and compromises need to be made.

## Paralyzed
But why care about the technical quality of your product, all that matters is sales right? It's all about whatever happens tomorrow. There is no such thing as temporary solutions, whatever is in a product is in there and will be in there forever. So, whenever you don't see a problem when using a 'quick and dirty' solution, you will keep on doing it.

This is the reason technical debt is, in my opinion, more dangerous than any other kind of debt: you don't see an immediate impact on the product or company. Just because you don't see a problem, doesn't mean there is no problem at all. Technical debt will slowly paralyze your company. Development time will take longer and longer, there will be more and more issues as the amount of users increase and unexpected behaviour will happen more often. It's not like everything suddenly goes black, your servers crash, people delete your app simultanously, no. It's more like development time takes up so much time and resources, you can no longer compete against your competitors.

Whenever you start to notice the company is paralyzed, you're in deep trouble. Unlike some other problems, this is not one that can be easily fixed with money. It takes time, a lot of time and in many cases way too much time to ever get out of the mess.

## How to prevent this?
* Take your time, time is an essential resource to build a product. It's easy to decrease the amount of features or the move a deadline, but it's impossible to guarantee the same quality in less time.
* Make clear rules about code quality and make sure everybody lives them by
* Care about your product and not only the money it generates

I hope I explained my point of view well.
Thanks for reading!



Greets,
Jakez
