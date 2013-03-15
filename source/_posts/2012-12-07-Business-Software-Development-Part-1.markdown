---
layout: post
title: "Business Software Development Part 1"
date: 2012-12-07 12:00
comments: true
categories: [Software]
---
This is the first part of my brain dump about Business Software Development.

### The problem
There's no doubts the world's changing, everyday new informations flooding in overwhelmingly, like this exciting piece about [the Next Web](http://blog.alexmaccaw.com/the-next-web). So how would you, as a person or an organization related to the field, feel and act upon such changes? Will you try to pursuit whatever that's new and promising? Or just bury your head in the sand then wait to be forced out with tears bursting out off your face?

Now here's what I proposed to deal with such. Starting with a little bit maybe philosophy.

### How I understand the world
It might be naive, but I believe things in the world are operating under certain set of principles. Only with a firm grasp of such anchors that one could secure his position above water to further breath, observe then explore. Oftentimes, when I found myself confused, I was merely confused by how the details would have been unfolded, not the principles that I choose to believe. 

Then the process for me to understand things could be summarized as follow:

1. I view the world of two distinct kinds: principles and specific objects.
2. Principles are abstract, they are about how I view and explain the world, so they are 'conceptually' stable. Things are what the world really is, and it's so big a world that I couldn't possibly live long enough to experience it all.
3. In order to understand enough about something that is specific, I need to be able to place it to a fixed, known position in my conceptual mind, meaning I need to know exactly to which set of principles they comply.
4. Things that I have yet to deal with may very well end up changing what I used to think of the world. So despite that principles are stable for most of the time, they could as well be altered under different circumstances.
5. There're things in the world that I just don't care about, knowing the principles I value will help sorting those out quickly as possible.

As I see software development non special but one aspect of my life, I expect principles of some kind about the field to be formed so I don't get panic every time dealing with things unfamiliar. Now here's the question: as a developer, Business Software Developer specifically, what kind of principles available that I could follow to make my days a little bit less tough?

(Figuring out such principles will certainly assist a person in shaping his career. And I wouldn't hesitate adding organizations to the benefitting-list)

So let's dive a bit deeper to the subject, by giving a definition to
### Business Software Development
By my definition, is the process of creating interactions between the end users and the business, on a set of computable devices.

* Computable Devices

Business can definitely be operated in many fashions. As a developer, we're focusing on those done through the Computable Devices. Being Computable, it leverages the power of a magic 'device' — special hardware plus the ecosystem around it, for achieving the business goals more efficiently and naturally as human society evolves in favor of higher productivity. 

Think about the transitions we've been through and experiencing: 

1. The mainframe era, computing resources were solely available to academics or maybe some giant corporations. It performs massive data analysis and generates maybe statistical predictions which helps in making business decisions. In this period, there is no direct interactions between the end users and the business through the computable devices. So obviously, no Business Software Developers were required.
2. The Pre-Internet-PC era, less expensive workstations are available, limited connections between the servers and stations could be setup locally. It starts moving into the everyday practices of a business, by improving operational efficiencies and saving cost. We started to see the emergence of word processing, data entry/reporting, printing, etc. In this period, IT administrators were hired, to maintain in-office hardwares and softwares which often came in as a bundle and normally provided by specialized companies taking care of both the software & hardware. But still, no interactions, no Business Software Developers.
3. The Internet-PC era, PCs becomes available and keeps getting cheaper. Software begins its focus on individuals. Then rose the Great Internet, which enables the connection between PCs and PC - Organization, then starts the application of the browser and the Web. Only at this period, the business and the end users began to realize that they could reach out to each other through a cheap browser window. Applications such as corporate websites, web campaigns/marketings, eCommerce models, and the likes became major phenomenons and strong links between the business and the end users. Because of the uniqueness of each business model, in order to convey its intents to the end users, business needs software specialists to implement various of its strategies. A new career line was then created, the Business Software Developer. Since they were mainly dealing with the Web - by creating applications available to browsers, and the browser back then was slow and incompatible b/w brands, these applications tend to be simple. Thus a lot of the business logics are performed at the backend, on the servers running within organizations. This's how we established the classic 3 layer abstraction model for building enterprise applications, namely the Presentation layer, the Business logic layer and the Persistence layer.
4. The Post PC era, this's happening because customers now have more computing powers at hand. Not only through PCs, but other accessories like phone, music player, watch, etc have become computable devices. These magical devices empower people, basically every single one of them, kinds of easy, natural, contextual ways to interact with the digital world. Data and business intents could now be rendered in such an appealing way to the end users that their great satisfactions unlock a whole lot new possibilities to present, perform and deliver business. Business now has more interaction models at their disposal, to reach out for the end users. As a Business Software Developer, he is now required to build applications for specific devices in order to provide the kind of experience the customer needs and knowing what kind of computable device he's building on, what sort of scenarios the device will be used in, and what kind of interactions are expected on that device is crucial for his success. But his main focus remain unchanged, to deliver business to the end user.  

So we could arrive at our first principle: Business Software Development is to bring business to the end users through various types of computable devices. The device's capability and use scenario decide what parts and how much of the business logics the device should contain.

It seems the business logic is moving from within organizations to devices that are much more closer to the end users, from trends of above transitions.

* Business

As a Business, it presents a known domain of rules base on which things could be operated. Business lives by being competitive, able to achieve goals, otherwise it is as good as dead. Because of the dynamics presented by the business itself, competitors and operating environment, for a business to stay successful, responsive decisions needed to be made from time to time. So naturally, Business Software Developers will be tasked to implement such decisions within a limited timeframe, along with making sure obsoleted business strategies implementations retired without breaking up those active ones' proper functioning.

So the second principle: Business Software Development should be done in such a way, that changes are expected and the business logics could be swap in and out, with minimum efforts.

* Interactions

No business could succeed when it fails on communicating to the end users, in a way they understand. To reach out to a customer, you have 2 basic forms: #1 you manage to get a list of customers, then you can ask them how they want to receive your product messages; #2 you have no idea of your customers' where about, but you do have couple communication channels at your disposal. Then base on behavior analysis of customers related to a specific channel, you cook up a special message for that channel, send it and hope it works. And whatever that is, at the very end, when it comes down to implementation for a Business Software Developer, it's to make sure that the end user on a specific communication channel gets the best user experience. Even to communicate the same business idea, you'll have to do it differently for different communication channels.
 
So the third principle: Business Software Development should be done in such a way, that the real implementation of a business logic align with the communication channel that facilitates the interaction.

### Conclusion
The business, computable devices and customer interactions keep evolving, one must realize that there's no points claiming that we have created such thing as the 'Perfect Software'. Development is an ongoing process, when any of the factors presents challenge, the process shall well reflect that. This is the very nature of Business Software Development.

And to recap the 3 principles:

1. The first one is about where to place the business logics, for a specific type of computable device to achieve best performance.
2. The second one is about the granularity of the business logics, so business changes could be applied manageably.
3. The third one is about the business logic implementation is dictated by the communication channel, in order to achieve the best user experience.

We'll see in the next piece how these 3 principles could be realized when structuring your project in certain way. And hopefully, how these could help a developer from understanding and choosing technologies.