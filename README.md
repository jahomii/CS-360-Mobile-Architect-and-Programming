#CS-360-Mobile-Architect-and-Programming

**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**

My application Mobile2AppInventory was meant to fulfill the user need for a mobile inventory app that allows users to store simple and brief information about items in an inventory that allows users to be notified when an item stock depletes to zero.

**What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**

My application makes use of 3 major UI screens, one dynamic UI component, and one popup box. On the Login screen, you see two lines that can be used to input an email and password, as well as a login and register button. When a user registers, they are brought to the SMS permissions page that prompts them to submit a number to receive SMS notifications when an item stock hits zero. After the SMS page, the main activity loads and users can add, edit, and delete data from the dynamically appearing scrollable database. When the users select edit, a popup box appears with the item information allowing for the user to edit and save. 

Throughout my UI design, I considered how other, similar apps arrange their UI, and how a variety of users may read the data on screen. My designs were successful because they were simple and consistent and did not require the user to go searching for elements. 

**How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?**

I approach the process of developing my app with simplicity and longevity in mind. I make sure each of my elements is clearly labeled and as simplified as I can make them so they're easy to reread and adjust over and over again. I rely a lot on making classes and functions to perform tasks rather than reusing code, that way I can call a method instead of remaking a process. These same strategies can be applied in the future when I work on larger applications to ensure that the Main function is simple and classes can be reworked more easily.

**How did you test to ensure your code was functional? Why is this process important, and what did it reveal?**

I had tested to ensure my code was functional by performing the tasks that users would likely perform, including accidents. This process is important because most users will likely perform many of the same tasks, but some users will make mistakes when going about their processes, and an application must be prepared to handle those mistakes. 

**
Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?**

One instance where I had to innovate to overcome a challenge was in making the database visible. At first, I had the vision of a large table that users could manually edit but it quickly became clear that that is not exactly a widget you can just drop into the main activity. So, I created a dynamic UI that builds and expands depending on how many items are in the database. This way there was no true limit to the database and the UI was responsive to the user's additions. 

**In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

One specific component that I feel I was successful in demonstrating my knowledge skills and experience is the functionality of the MainActivity. I think the responsive UI combined with the popup edit screen shows my ability to create a dynamic and modern application that still is simple in its functionality.
