# Plastic Free Ocean

The Plastic Free Ocean project is a community that is concerned about the plastic pollution in beaches in Den Haag, Netherlands. The beaches of Scheveninger are highly visited by tourists from all over The Netherlands and other neighbor countries. Along the coast there are a large number of beach bars and food kiosks where, especially during the summer. So keeping the beach clean is good not only for the environment, but also to keep the beauty and a nice place for the tourist.The project was made just to gather people interested in keeping the beach clean and also to do our part in trying to lower our impact on Earth.

# Deployment

The website was deployed to GitHub web pages. Link: [Plastic Free Ocean](https://dabronzo.github.io/plastic_ocean/index.html)

# User Experience

## Strategy

The main goal of the project is to inspire more people to join the project, making the **Plastic Free Ocean** grown to have more impact on the local community. The website displays pictures and information to highlight the plastic pollution problem also bring solutions that can be reachable to everyone.

## Scope

The website is developed to have a very simple and intuitive interface, allowing either first time users and regular users to navigate and get information about the project and its activities. Consist of three pages, **Home** as the landing page where is displayed some info about the project, activities calendar and contact info. **Plastic and Pollution** is an info gallery page made to highlight the problem with the plastic in the ocean and inspire people to take small actions to mitigate it. A **Sign Up** where the user can sign up and participate in the project and also allows the organization of the project in keeping a database for the members.

## Structure

To keep the project consistent and intuitive the navigation bar remains the same through the pages. Hover animations on the links where the provide a more intuitive behaviour and visual feedback to the user.

## Skeleton

Due to its own nature the project has a few and simple features, consisting in pictures, animations, text information and a sign up form. The navbar and the footer are consistent and repeat along the pages.

Below is a wireframe model of the project made with **Balsamic Wireframes** 
The final project turned out to be a bit different.

![balsamic wireframe](/docs/plastic-ocean-wireframe-small.png)

## Surface

Simple colours based on tons of blue and white were used in the design giving a good contrast to headers, paragraphs and links. The navigation bar links on the page where the user currently is remaining with a different background so intuitive reminding where the user is. The texts have some spacing between the letters to make easier reading

# Responsive

The website is designed to be totally responsive and work in tablets and smartphones.
Bellow is the responsive visualization:

![Am I responsive ScreenShot](/docs/responsive.png)

# Features
## 1 Navigation Bar
- Featured the three links for the other parts of the site, "Home" and "Plastic and Tourism", sections of the main site and the "Sign Up" that brings the user to the form page.
- When the links are hoovered the background and the color of the text changes to give the user more a clear idea about which link is being hoovered.
- Is fully responsive, the logo and the menu links change places and the layout fit in smaller screens. Also, when the user is the "Sign Up" page the link gets with a different color showing which page is currently on.

![Navegation bar screenshot](/docs/navbar-final.png)

## 2 The Landing Image
- Include the photographic of a turtle that has a blueish gradient that gets more opaque by the bottom of the picture and an overlay text with a catching phrase.
- The overlay text has an animation where the sentences appear in different timings.

![Landing Picture](/docs/landingpic.png)

## 3 About Us
- In this section the user will find some information about the project, the activities and the meetings and also the party. This should encourage the user to attend to the events and socialize.
- Is also responsive, in smaller screens the two paragraphs and picture will adjust to optimize the visualization.

![About Us screenShot](/docs/aboutus.png)

## 4 Activities
- Here the layout shows three "cards", each one holds information about when, where and which kind of activities hosted by the project.
- The responsive behavior for smaller screen will show the cards in a vertical orientation to make the content more visible to the users.

![Activities cards](/docs/activities.png)

## 5 Contact
- This section brings some simple contact information of the organization project such as email, address and phone number.

![Contact info](/docs/contact.png)

## 6 Footer

- To encourage the user to follow the project in other social media the future brings the three links (Instagram, Facebook and twitter), each link open in a blank tab in order to bring a better user experience.

![footer with the social media links](/docs/footer.png)

## 7 The Sign Up Page

- This page allows the user to sign up to be part of the **Plastic Free Ocean** by filling the fields. This will provide the owner of the site to have the right information to send news and events to members of the project.
- The design have a big picture of people holding hands at the beach to inspire a sense of union and teamwork. The form appear after a few seconds with an animation. Has an opaque background to give a good contrast with body page picture.
- The fields of name and email are mandatory, the check box give to the user choose to participate of the meetings or just the clean up events.
The Footer and the Header keeps the same style and colours of the main page, with links for the user navigation.

![sign-up page](/docs/sign-up-final.png)

## 8 The Plastic and Tourism Page

 - This page brings to the user some information about the plastic pollution related to tourism activities. Pictures and information are displayed to show how serious and relevant is the subject, but also to inspire the user to take small but relevant actions to mitigate this problem.

![plastic and tourism page](/docs/plastic-tourism-final.png)

# Testing

- Hereby will be explained the all the testing that was done to ensure that all the features in the website works properly and deliver what is expected.

## HTML and CSS
### The HTML, tested with no errors. 
- Link to the tests:
- [W3C validator index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdabronzo.github.io%2Fplastic_ocean%2Findex.html)
- [W3C validator infogallery.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdabronzo.github.io%2Fplastic_ocean%2Finfogallery.html)
- [W3C validator form.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdabronzo.github.io%2Fplastic_ocean%2Fform.html)
### The CSS was tested with no errors. 
- Link to [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdabronzo.github.io%2Fplastic_ocean%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Lighthouse
- Others parameters were tested with the Google's developers tool **Lighthouse**, the results are in the picture bellow.

![Lighthouse result](/docs/lighthouse-results.png)

# Know Bugs

- During all the tests and development of this project one bug was noted and couldn't be fixed.
When the page is loaded for the first time the background pictures are taking a bit longer to load, this cause a fast and weird looking stage where the animation effect is not so appealing. This might be due to the size of the pictures or the way that is being loaded in the server. I've tried to use the smallest size possible (to not be pixelated) and the time of loading was reduced but still visible.
However this effect only happens one time, when the page is loaded for the first time, once the page data is in cache the loading time is almost zero and the bug doesn't happen. 

# Credits

## Content
 - **Information Content** The numbers in the **Plastic and Tourism** where taken from the organization **One Planet Network** Link: [Oneplanetnetwork Website](https://www.oneplanetnetwork.org/programmes/sustainable-tourism/global-tourism-plastics-initiative/tourisms-plastic-pollution-problem)
 
 - **Design Inspirational** The website of the organization **Ocean Clean Up** was the inspirational model that I used to create this project, Link: [Ocean Clean Up Website](https://theoceancleanup.com/?utm_source=google_cpc&utm_medium=ad_grant&utm_campaign=branded&gclid=Cj0KCQiAkZKNBhDiARIsAPsk0WjQJN4JU_kkAtzpFVFDjB5irjVHj5LMTuRBJ8IkCrHT-flXobVXpOkaArD_EALw_wcB)

 - **External Repository:** The dockerfile was provided by the **Code Institute** as part of the Full Stack software Developer course.

 - **Design Inspiration:** The section **Activities** on this project was inspired by the website **Love Running**.

 - **Animation Tutorial:** The animations in this website was done following this tutorial of the YouTube Channel **Divinector**, Link: [Tutorial on Youtube](https://www.youtube.com/watch?v=bPbnX9_K1y4)

 - **Glass Effect** The "glass" effect on the sign-up page is taken from the **Online Tutorials** YouTube channel, Link: [Glass effect tutorial](https://www.youtube.com/watch?v=1u8qTcFeQzk)

 ## Media

 - All the pictures in this project were taken from [Pexels website](https://www.pexels.com/)

## Special Thanks

 - To **Brian O'Hare** My mentor, for all the attention and dedication, giving me good insights about the project.

 - To the **Slack Community** Where all those amazing people, always there with solutions and advices.






