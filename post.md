##(WTF is an API?)

##Abstract

APIs, or “Application Programming Interfaces”, have revolutionized the way that we use web and mobile applications by allowing computer programs to talk to each other. Because of this revolution, software development and innovation has radically sped-up over the last 10 years, and apps integrate and communicate in fantastically new ways.

##Introduction
We use our laptops and mobile phones every day to communicate with our friends, family, and coworkers. But how do programs communicate with each other?

APIs, or “Application Programming Interfaces,” are the hidden backbone of our modern world which allow software programs to communicate with one another. Although most of us don’t know it, behind the scenes of every app and website we use is a mesh of computers “talking” to each other through a series of APIs. Today, the “API economy” is quickly changing how the world interacts. Everything from photo sharing, to online shopping, to hailing a cab is happening through APIs. Because of APIs, technical innovation is happening at a faster pace than ever. If you already write software, you are probably familiar with APIs. But the rest of you may be wondering: what exactly are APIs and why are they so important?

##APIs: The Backbone of Software
At the most basic level, an API is a set of rules that dictate how one application communicates with another. APIs aren’t that new either; whenever you use a PC, APIs are what makes it possible to move data between different applications, for instance by copying a link from an email into a Microsoft Word document. Low-level APIs are what make it possible for applications, like Excel or Dropbox, to run in an operating system, like Windows or Macintosh OS X, in the first place [1].

On the web, you can think of APIs like a telephone system: when one application wants to get information from another, it gets that data by “calling” the second application’s API. For example, if you wanted to build an app that showed users the nearest restaurants that their friends liked, you could use the Yelp API (to get restaurant data) [2] and the Facebook API (to get data about what the user’s friends’ like) [3]. When a user opened your app, the application’s code would “call” the Yelp and Facebook APIs to get the data that it needed. Figure 1 shows how this works: a user accesses a website, and the website then calls Facebook’s API to get the data it wants.

![](https://d262ilb51hltx0.cloudfront.net/max/996/1*AmUAIuwgWiY0TfWRcS0Rsw.png)

In the Web API world, big services like Facebook, Google Maps [5], Foursquare [6], and others allow smaller apps to “piggyback” on their data. For example, many applications let users “sign in with Facebook”, which all happens through Facebook’s API. Many websites show locations on Google Maps, which Google allows through their Google Maps API [5].

APIs do all of this by exposing a piece of the software’s internal data and functionality to the outside world in a controlled way [7]. That allows for one application to share data and perform actions on one another’s behalf without requiring software developers to share all of their code. Sharing code at that scale would be massively inefficient in addition to posing major security threats. APIs allow for this type of integration without sharing the actual code that makes the software run. APIs are useful even for open-source software (where the code is freely and publicly available): most developers don’t have the time or patience to look through thousands of lines of code just to use one piece of functionality. Instead, that functionality can be offered through an API.

Without APIs, applications would be incredibly disconnected and therefore confusing. APIs allow applications to talk to each other, and therefore for more innovative and consistent applications to be built. Imagine, for example, if Google Maps didn’t offer an API: every mobile application and website on the internet would have to figure out how to implement their own mapping system from scratch, an incredibly difficult task. APIs can also be useful internally for a company in addition to sharing resources across companies. For example, a software developer at Wikipedia could create one API to support all of the Wikipedia applications used by end users: the website, iOS, Android, and Blackberry apps [8]. Instead of having to duplicate code for each of other apps, they can share data via one API. APIs simplify much of the complexity of software development by limiting outside access to a specific subset of functionality — usually data exchange. Because of this, new software can often be built in weeks instead of months or years.

##Why APIs are Important

In the modern world, APIs are incredibly important because they explain how software developers can engineer new apps that plug into big services: social networks like Twitter and Facebook, or utilities like Dropbox or AccuWeather [9]. The maker of a mobile game, FlappyBird for instance, could use Dropbox to let players store their games and preferences in Dropbox’s cloud instead of building out a cloud storage system from scratch. Or a developer making a mapping application could add the option to hail a cab through the app via the Uber API. APIs can therefore be huge timesavers for both software developers and users. Without the Facebook API for instance, users would have to create a separate username and password for every application instead of having the ability to “log in through Facebook” (which uses the Facebook API)

APIs are what allow for modern Web experiences to work so well. Developers can pick and choose APIs and “mash” them up to create entirely new experiences [10]. From Google, to Twitter, to Facebook, developers have the pick of literally thousands of APIs to work with. For example, when you use your iPhone to search for nearby bars on Yelp, the app plots their locations on an Apple Map instead of trying to create their own map from scratch. This all works through an API. The Yelp iOS app passes the locations it wants plotted to the Apple Maps API which then returns a Map with the bars pinned on it in the correct places. Yelp can then display this to the app’s users. Mobile devices like iOS and Android phones and tablets have many APIs like this built-in. For example, Apple recently announced a new API called “HealthKit” as part of iOS 8 that allows developers to access a user’s health data from a a central place [11].

Another common application of APIs are the “sharing” icons your see on articles, blog posts, and videos across the web (as seen in Figure 2). By clicking on the Facebook, Google+, Twitter, LinkedIn, or Reddit share links next to an article, an API is called that allows users to Tweet or post about an article without leaving the site they’re on. Another common API is for the commenting system that is below many articles and videos known as Disqus. It allows users to post and view comments without the website owner having to do anything extra. As you may have noticed, APIs are extremely pervasive and have allowed the pace of innovation to increase rapidly, where each new software developer can create functionality without having to reinvent the wheel.

![](https://d262ilb51hltx0.cloudfront.net/max/1600/1*rouM6HRN9FeRIhpbaP6mmw.jpeg)

##API Business Models
As you may have already been able to deduce, APIs are often used by companies to make money. Figure 3 shows 4 common API business models that allow companies to further business objectives via their APIs. The term “Developer” in the figure refers to the software developer that would be utilizing the API.

![](https://d262ilb51hltx0.cloudfront.net/max/2000/1*oJWbJB92cFVnvVrBF6U9Ig.png)

In a free API, a company or organization gives away access to an API at no cost, either because having software developers using the API spreads the reach of the company and may allow the company to reach more users (for example when Google or Facebook allows access to its APIs) or because the API is simply free and open source. In a “developer pays” model, the API, or the data provided through it, is so valuable, that a software developer is willing to pay for access. Examples of this include PayPal, which charges for access to its payments API because it makes accepting payments online much simpler. PayPal then charges a transaction fee for each payment made through its API. In a “developer gets paid” model, a company may pay a developer for using its API. This often comes as part of an affiliate program or revenue-share program whereby a developer using the API (e.g. Amazon’s) can get paid for every “lead” she sends to Amazon.com through the API. “Indirect” models cover all of the other possible ways for companies to benefit from APIs. Salesforce (which provides businesses with software to manage their sales cycles), for example, can provide an API as a way to up-sell its business customers on a more expensive contract that provides access to the API (which can be used for custom integrations and needs).

##An API is a Promise
A major issue with APIs is that they aren’t necessarily permanent. Just because a company is making an API available now doesn’t necessarily mean it will be available tomorrow. Twitter infamously limited third-party access to its API at the end of 2012 [14]. This had the effect of killing all alternative Twitter clients and forcing users to use Twitter’s official apps and website, where Twitter can show users ads as it pleases. This was done under the guise of providing a more cohesive user experience, but for many developers who relied on the Twitter API, it meant shutting down their business because of Twitter’s decision.

Other examples of this API abandonment are common. Startups that provide an API often shut down or get acquired, and Google is notorious for closing down services that people rely on like Google Reader (that allowed people to aggregate all the news services they read into one place) [15]. Since web APIs are still in their infancy, there is still a lot to learn. One of the things API providers should understand is that an API is a promise: once other people are relying on it, it is crucial maintain it and keep it active.

##APIs and Innovation
The good news is that for the most part, APIs encourage innovation and don’t stifle it. Without APIs, communication between apps would be stifled, software developers would continuously be re-writing software that performed the same functionality, and generally innovation would slow. APIs have allowed for more trivial things like sharing photos with friends, but also for the potential to reimagine government. The White House recently released Data.gov [16], which is a set of thousands of APIs that allow the public to access information about government resources ranging from healthcare to finances to agriculture. This has allowed developers to create apps to support their neighborhoods and fellow citizens: from apps to help find polling places to ones that give information on food safety [17], and none of this would have been possible without APIs. As the world moves further and further into the technical revolution, APIs will have an even bigger role powering the apps and websites we use every day.

I don’t post often, but when I do, I want to tell you about it! Get notified when I write stuff about technology, business, and/or life. If you get sick of me, you can unsubscribe anytime. Enter your email address here: http://tinyletter.com/michaelrbock.

References

[1] Application Programming Interface [Online]. Available: http://en.wikipedia.org/wiki/Application_programming_interface

[2] Yelp API [Online]. Available: http://www.yelp.com/developers/documentation

[3] Facebook Developers [Online]. Available: https://developers.facebook.com/

[4] A. Porwal (2013, May 21). Social connect APIs for websites: Simple, Easy & Secure [Online]. Available: https://mp09digital.com/blog/social-connect-apis-for-websites-simple-easy-secure/

[5] Maps API — Google Developers [Online]. Available: https://developers.google.com/maps/

[6] Foursquare API [Online]. Available: https://developer.foursquare.com/

[7] D. Benslimane, “Services Mashups: The New Generation of Web Applications,” IEEE Internet Comput., vol. 12, no. 5, pp. 13–5, Sept. 2009. Available: http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=4620089

[8] List of Wikipedia mobile applications [Online]. Available: http://en.wikipedia.org/wiki/List_of_Wikipedia_mobile_applications

[9] J. McKendrick. (2014, Sept 17). APIs, a programmer’s tool, are opening up the gates to business innovation [Online]. Available: http://www.zdnet.com/apis-a-programmers-tool-are-opening-up-the-gates-to-business- innovation-7000033762/

[10] Programmable Web: API Mashups [Online]. Available: http://www.programmableweb.com/mashups/directory

[11] C. Welch (2014, Jun. 2). Apple HealthKit announced: a hub for all your iOS fitness tracking needs [Online]. Available: http://www.theverge.com/2014/6/2/5772074/apple-healthkit-ios-8-announcement

[12] Ad This [Online]. Available: http://www.magentocommerce.com/magento-connect/addthis.html

[13] J. Musser (2013, Feb. 22). API Business Models [Online]. Available: http:// www.slideshare.net/jmusser/j-musser-apibizmodels2013

[14] M. McHugh (2012, Aug. 17). Translating and talking through Twitter’s new API restrictions [Online]. Available: http://www.digitaltrends.com/social-media/twitters-new-api-restrictions/

[15] A final farewell [Online]. Available: http://googlereader.blogspot.com/2013/07/a- final-farewell.html

[16] APIs [Online]. Available: https://www.data.gov/developers/apis

[17] Applications [Online]. Available: https://www.data.gov/applications