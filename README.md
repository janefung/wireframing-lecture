## Objectives

- Explain what a wireframe is.
- Explain why a wireframe is important.
- Use a wireframe to design a viable product.
- Identify common user interface patterns.

## What's a wireframe?

A **wireframe** is a semi-realistic representation of what an application might look like and how it might behave. A wireframe is typically a hand drawn, black and white illustration that does not include any visual styling like color, typography, or images. It shows the basic nature and prioritization of content using placeholder text and images. At a typical company, a product team will create many wireframe iterations, starting with rough outlines that eventually lead to late stage illustrations. A late stage wireframe often contains [lorem ipsum](https://hipsum.co/?paras=4&type=hipster-centric) filler text for content and recognizable shapes for lists, buttons, images, and videos. In short, a wireframe is meant to be created quickly, iterated upon, and thrown away.

Here's an example of some rough outline wireframe iterations for a profile page of an application.

![](https://students-gschool-production.s3.amazonaws.com/uploads/asset/file/535/wireframe.png)

And here's an example of a late stage wireframe for the same profile page.

![](https://students-gschool-production.s3.amazonaws.com/uploads/asset/file/533/Profilewireframe.png)

At the other end of the spectrum, you'll find mockups. A **mockup** is a realistic representation of what an application will likely look like and how it'll likely behave. A mockup includes high fidelity visual styling such as approximations of content, color, typography, and images. While some people prefer to draw a mockup using graphic software, others use straight HTML and CSS. A product team will often create many mockup iterations. However, mockups are typically not cast aside so easily as it's common for the final application to look nearly identical one of the mockup iterations.

![](https://students-gschool-production.s3.amazonaws.com/uploads/asset/file/534/01-Free-perspective-website-mockup-824x542.jpg)

### Exercise

Turn to a neighbor and explain what a wireframe is in your own words. In your explanation, include the differences between a wireframe and a mockup.

## Why is a wireframe important?

A wireframe is important because it increases the chances that your product will be viable. A **viable product** is one that helps a user achieve their goals. Studies of successful products that go to market repeatedly show that users don't care that much about features. They only care about achieving their goals. The following diagram illustrates the difference between building a Minimum Viable Product (MVP) by focusing on product features versus focusing on user goals.

![](https://public-media.interaction-design.org/images/uploads/e110f6dc07d9e8ebe1ea8251eab2a359.png)

It's easy to imagine what a product should look like or how it should behave. But until you create a wireframe, these are just unvalidated assumptions that may not lead to a viable product. The assumptions you make about a product as you develop it may not be the same assumptions that a user will make the first time they interact with it. With a wireframe, you can have a conversation with the product's potential users and other stakeholders without having to discuss the nitty-gritty details.

Take the next ten seconds to imagine an automobile in your head. Think about its make, model, and color. What was the picture you created? What assumptions did you make?

After we've dicussed the results of this exercise as a class, go ahead and click on the following link which explains [how to build a Minimum Viable Product (MVP)](https://public-media.interaction-design.org/images/uploads/9f7f5b30ed9905117b65572ab6949a9f.png).

A good wireframe increases the chances that your product will be viable by meeting the following user experience (UX) best practices.

### Customer Focus

- Define the minimum set of product features based on the user's goals
- Prioritize the minimum set of features based on the user's goals

### Content Hierarchy

- Identify which information is most important to the user and their goals
- Layout the information appropriately according to the order of importance

### Consistency

- Apply visual and textual content consistently to avoid confusion
- Use established design patterns that adhere to the principal of least surprise

Finally, it's important for you to learn how to create a wireframe because it shows potential hiring managers that you have the ability to plan and test your assumptions before you spend time coding up a product that might not be viable.

### Exercise

In your own words, write down why a wireframe is important.

## How do you use a wireframe to design a viable product?

The best way to come up with a viable product is to do some light experimentation. For many of you, your first viable product may be your Q1 Project. For this project, your task is to experiment with a web API or technology that interests you. Take a weather service API, for example. One way to experiment with a web API is to send it HTTP requests and see what kind of information you get back in the HTTP response. In this case, it's likely respond with a weather forecast for the day.

To see a forecast for the day, run the following command.

```shell
http GET 'http://api.openweathermap.org/data/2.5/weather?APPID=cc4654c8e15f6d08b13954b915a0d0b1&q=Seattle'
```

And you should see something [like this](https://gist.github.com/ryansobol/22c1198849818eb1ec2a8b39ad82c1d5).

Once you figure out how a web API works, start thinking about the problems you could solve with this information. Using our weather service API, one problem worth solving could be this.

> I'd like to know whether or not it's a good day to bring an umbrella to school.

Go ahead and write down this problem on your [wireframe template][wireframe] under the "Your Idea" section.

Now that you have a problem worth solving, let's figure out who might have this problem. If you think about it, there are quite a few people who might. You might, your classmates might, your instructors might, people who work at your campus might. However, each group of people will have different needs and expectations when using your product. Some may want it to look and feel simple, clean, and elegant. Others might want it to have lots of options. So rather than trying to solve a problem for the generic everybody, which is impossible, you'll want to solve a problem for a specific somebody. This is where defining a primary user can help.

A **primary user** is a specific person, but is not a real individual, who's eager to use your product. A primary user represents a specific group of viable users and is synthesized from observations about many people. For example, take Cynthia.

> Cynthia is a mid-20s go-getter who's currently enrolled in Galvanize's Web Development Immersive. Spring is always wet season and she doesn't want her brand new Macbook Pro to get wet as she waits for the bus to and from school . She's on a tight budget so she can't afford to buy a new laptop if it happens to get wet.

Go ahead and write down this primary user on your [wireframe template][wireframe] under the "Primary User" section.

Now that your product has a primary user, the next piece of the puzzle to consider is the context. Simply put, **context** is when and where the primary user is most likely going to use your product. One possible context for Cynthia is this.

> Cynthia is often running late in the morning and keeps her laptop in her bag. Her umbrella stays by the door so she can quickly grab it on the way out while she checks the weather on her phone.

Go ahead and write down Cynthia's context on your [wireframe template][wireframe] under the "Context" section.

Now that you've identified a problem worth solving, a primary user, and the context for using this product, you have all the pieces necessary to create a primary use case. A **primary use case** is the steps your primary user might take to successfully achieve his or her goal by using your product. The primary use case for Cynthia includes the following.

1. See whether or not they should bring an umbrella to school today, the percent chance for rain today, and the temperature for today.
1. See all of the above information for a 3-day forecast. (i.e. tomorrow and the next day)
1. See all of the above information for a 7-day forecast.

Go ahead and write down Cynthia's primary use case on your [wireframe template][wireframe] in the "Primary Use Case" box.

With the primary use case complete, you can now draw a rough outline of its steps. It's important to imagine how the user will move from step to step. This movement is usually triggered by a user event. For example, clicking on a button, scrolling down a page, hovering over some content, etc.

Take the next ten minutes to illustrate how Cynthia will achieve her primary use case.

In addition to the primary use case, a primary user will often have secondary use cases. A **secondary use case** is the steps your primary user might take to successfully achieve an infrequent goal by using your product. Cynthia's secondary use case is the following.

1. See a [doppler radar](http://www.king5.com/weather/340-mile-range-radar) of today's forecast.

Take a few minutes to illustrate how Cynthia will achieve her secondary use case.

The storyboard of primary and secondary use cases will now drive your subsequent design decisions of your late stage illustrations. These illustrations often use a 12-column grid to layout approximations for filler text for content and recognizable shapes for lists, buttons, images, and videos.

### Exercise

Take the next 10 minutes to create a late stage illustration of the first box (i.e. the landing page) of your storyboard using a [12-column grid template][wireframe].

## How do you identify common user interface patterns?

- [Account Registration](http://ui-patterns.com/patterns/AccountRegistration)
- [Autocomplete](http://ui-patterns.com/patterns/Autocomplete)
- [Calendar Picker](http://ui-patterns.com/patterns/CalendarPicker)
- [Good Defaults](http://ui-patterns.com/patterns/GoodDefaults)
- [Inplace Editor](http://ui-patterns.com/patterns/InplaceEditor)
- [Pagination](http://ui-patterns.com/patterns/Pagination)
- [Product page](http://ui-patterns.com/patterns/ProductPage)
- [Shopping Cart](http://ui-patterns.com/patterns/ShoppingCart)

## Resources

- [How To Build A Tire Swing – A Case For Agile Development](http://blogs.perficient.com/perficientdigital/2011/07/22/how-to-build-a-tire-swing-a-case-for-agile-development/)
- [How To Read a Wireframe](http://blog.fuzzymath.com/wp-content/uploads/2011/07/Fuzzy-Math-How-to-read-a-wireframe.pdf)
- [Medium - User Experience: Primary and Secondary Users in Healthcare](https://medium.theuxblog.com/user-experience-primary-and-secondary-users-in-healthcare-8dd4c5c61490#.t43i3b6jt)
- [Minimum Viable Product (MVP) and Design - Balancing Risk to Gain Reward](https://www.interaction-design.org/literature/article/minimum-viable-product-mvp-and-design-balancing-risk-to-gain-reward)
- [Pttrns (mobile only)](http://pttrns.com/)
- [UI Patterns](http://uipatterns.io/)
- [User Interface Design Patterns](http://ui-patterns.com/)
- [Wikipedia - Principle of Least Astonishment](https://en.wikipedia.org/wiki/Principle_of_least_astonishment)
- [Wikipedia - Website wireframe](https://en.wikipedia.org/wiki/Website_wireframe)
- [Yahoo Design Library](https://developer.yahoo.com/ypatterns/)

## Wireframe Tools

- [Wireframe.cc (free)](https://wireframe.cc)
- [Draw.io (free)](https://www.draw.io/)
- [InVision (free)](https://www.invisionapp.com/)
- [Balsamiq (trial)](https://balsamiq.com/)
- [LucidChart (free / flow diagrams)](https://www.lucidchart.com/)
- [Gliffy (free / architecture mapping...)](https://www.gliffy.com/)
- [UIStencils (cool / only semi-related)](http://www.uistencils.com/)

[wireframe]: https://students-gschool-production.s3.amazonaws.com/uploads/asset/file/507/Wireframe_Template.pdf
