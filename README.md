# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The client "The Gaming Room" wanted to expand their currently popular game "Draw in or Lose it" from android, to be available across multiple platforms, including iOS, Windows, Mac and Linux users, with the potential to also be available to console platforms. This game is based off of a popular 1980's television show "Win, Lose or Draw".
# What did you do particularly well in developing this documentation?
We determined the best fit for the application to be reachable by various platforms and manageable on the server level. The determination to develop a RESTful API hosted on a Linux back end, lends low overhead and cost, while allowing for scalability. The client size was determined to best be delivered via the platform browser, using HTML and JavaScript.
# What about the process of working through a design document did you find helpful when developing the code?
The design document allows for planning portions of the code that will be required near the end of a project early on, reducing the amount of time put into re-writing portions of code later in the development process. This also allowed for planning for the type of information and data processing that would be necessary.
# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would want to revise using a RESTful API over standard HTTPS calls via JavaScript Ajax, and instead utilize websockets, as this can be much more event driven and less impacted by time/refresh intervals, when dealing with a large number of requests.
# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
The user is the primary customer of any software... if the experience is not enjoyable for the user the software will fail... That being said it was important to consider the different platform layouts, rendering engines, as well as ensure a method of data transmission that would be fair and reliable across multiple platforms. Also providing a consistent look and feel for the customer is important.
# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
Researching the intricacies of the various platforms, what constraints each platform has, and which methods would provide the most consistent experience was the most important aspect of design. Being a broad topic, this involved determining which type of connectivity each platform had, what the memory/storage costs for each platform were, determining the subtle differences in the browser's rendering engine and JavaScript engines. On the server side of things, it was important to understand the ability to provide consistent performance at manageable costs, as well as plan for sudden need to scale up. Each of these topics, provide major insight to what utilities and resources will be required or available to shape the software around.
