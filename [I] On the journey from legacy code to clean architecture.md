# Title

On the journey from legacy code to clean architecture

# Type

45 minute talk

# Abstract

Buffer for Android was first made in 2012 - and since then it's seen a range of iterations and features. Whilst it's important for a product to grow in-order to meet the needs of users, it's easy for code to become unclean and lose any sense of architecture. This legacy code makes it difficult for us to maintain our product and build new features without the fear of breaking the app.

But there is light! At Buffer we've just started to re-architect and refactor our application for Android using a clean architecture approach. Re-crafting our application feature by feature with the help of RxJava, Dagger and tests in the form of jUnit and Espresso has begun to result in a more stable, better architected and maintainable codebase. Together with our new continuous Integration flow this all helps in providing a better Buffer experience on Android.

In this talk we will explore the journey we took through refactoring from legacy code to a clean architecture. Starting with heart of our app, the Composer, we'll share our learnings and findings discovered on our journey and the benefits from doing so.

The talk will consist of several sections to demonstrate our learnings. We'll be looking at:

The original state of the app . Here we'll look at the original architecture and state of the Android Application, the hurdles it created for us and the reasons why we decided it was time for change

Adding CI to the mix. We will go into our CI structure and how everything is setup and helps us keeping a reliable building and testing environment.

Rebuilding with a clean architecture . In this section of the talk we'll look at beggining of the rebuild journey, starting with the composer. Here we'll look at the transofrmation of the codebase and architecture of the app, applying SOLID principles and how we're creating a more maintainable and extensible codebase

Rebuilding with a clean architecture . In this section of the talk we'll look at beggining of the rebuild journey, starting with the composer. Here we'll look at the transofrmation of the codebase and architecture of the app, applying SOLID principles and how we're creating a more maintainable and extensible codebase

A summary of our learnings . Finally, we'll look at the overall impact these changes have had on the android app as a whole, the increase in code quality and what this holds in place for the future of our app - allowing the listeners to take away some influence to achieve similar implementations.

# Give at

- Londroid December 2016
- Brighton Mobile March 2017
