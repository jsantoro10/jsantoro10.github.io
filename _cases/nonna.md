---
layout: case
name: nonna
title: Nonna's Restaurant
tagline: Online ordering experience for a local restaurant
button: Mobile App
backLink: /#work
nextPage:
  title: NYC's Best
  link: /cases/nycbest
banner:
  deliverable: Dedicated mobile app
  roles:
    - Concept
    - Research
    - Visuals
    - Interaction
  duration: Sept - Dec 2022
  tool: Figma
overview:
  problem: Ordering food online through an app like DoorDash or Uber Eats has become second nature for many of us. It’s quick, convenient, and simple–but **have you ever encountered an issue tracking an order through these third-party delivery apps?**
  examples:
    - description: In some cases, restaurants handle the food delivery themselves so you don’t know when to expect your order, you’ll only be given a time frame of when it *should* arrive.
      image: problem1.png
      rounded: true
    - description:  In other cases, there may be no couriers in the area to pick up your order from the restaurant.
      image: problem2.png
      rounded: true
  solution:
    title: Why not eliminate the middleman?
    description:
      - paragraph: For a growing restaurant chain with an established customer base, developing your own dedicated mobile app allows you to increase your profit margin, control the customer experience, and own customer insights.
      - paragraph: My goal for this project was to design a mobile app for an Italian restaurant with this kind of profile. Enter Nonna’s Restaurant, an Italian restaurant with three locations in New York City.
      - paragraph: “We’d like to provide our customers with a **quick way to easily order pickup/delivery in the midst of their busy schedules.**”
        quote: true
      - paragraph: In addition to pickup/delivery options and live order tracking, I wanted to ensure that the app included other features that could compete with existing food delivery apps, like **loyalty discounts** and **single sign-on**.
research:
  description: 
    - To understand the users I was designing for and their needs, I conducted qualitative research through **interviews**, **storyboarding**, **user journey mapping**, and a **competitive analysis**.
    - Through the interviews, I learned that users often turn to food delivery apps because **their busy schedules make it difficult to prepare meals at home**. More specifically, the time they otherwise would’ve spent cooking or grocery shopping is taken by their obligations or hobbies.
    - "The app was created with two user groups in mind: **new college graduates** and **multitasking parents** who don’t have time to meal prep."
  personas:
    - title: The New Grad
      age: 24
      job: Software Engineer
      image: portrait1.png
      description:
        - Araya recently started a new career as a software engineer at a startup after finishing coding bootcamp. They use the time after work to learn new skills so they usually order food for dinner instead of cooking.
        - They get frustrated by the lack of information involved in the pickup process with apps like Seamless. They often arrive at the expected order completion time only to wait longer than expected.
    - title: The Multitasking Parent
      age: 45
      job: Nurse
      image: portrait2.png
      description:
        - Horace is a nurse at a major hospital in the city. He recently had a health scare and has committed to cutting red meat out of his diet. His schedule can be unpredictable so he gets food from restaurants near the hospital.
        - He prefers to order from the restaurant’s site but is often forced to choose another restaurant when there are no options to add notes to a menu item or the order itself.
  challenges:
    description: "After mapping out each step of these users’ journey, I discovered the following key challenges that weren’t addressed by third-party food delivery apps like Seamless and ChowNow:"
    list:
      - "Users want the **option to add notes to a menu item** or their overall order."
      - "Users want a **reliable pickup experience** with accurate status updates and an easy handoff."
  competitive_analysis:
    summary: 
      - Now that I had an understanding of our target users’ experience with third-party delivery apps, I wanted to analyze the **ordering experience of restaurants with in-house delivery apps**.
      - Using the App Store, I selected **two direct competitors** among the highest rated ‘Italian restaurant’ apps, along with **one indirect competitor** from the highest rated ‘restaurant’ apps. I looked at aspects like features, accessibility, user flow, and navigation, as well as App Store user reviews.
    competitors:
      - competitor1.png
      - competitor2.png
      - competitor3.png
    analysis: My analysis validated the challenges previously noted, in addition to revealing a **user preference for single sign-on**. I was surprised to find that many of the user reviews for the competitors’ apps noted a broken ordering flow. Unsurprisingly, users stopped using the app altogether once it lost value to them.
  insight: Our users value efficiency, reliability, and customization.
ideation:
  summary: Once I had a clear idea of the key challenges–and, in turn, the key improvement opportunities–I began sketching out different iterations of the homepage using the **Crazy Eights exercise**.
  examples: 
    - description: My initial sketches focused on **shortcuts to key user goals** on the homepage for an efficient ordering flow.
      image: ideation_before.png
      wide: true
    - description: For the refined version, I prioritized a **quick and easy ordering process** with  ‘Dine In’ and ‘Take Out’ CTAs, as well as offers, popular dishes, and favorites.
      image: ideation_after.png
wireframes:
  - summary: My first iteration included a banner with the user’s reward points balance, customization options on the menu item screen, and order status tracking.
    image: wireframe1.png
  - summary: I designed the second iteration to include my initial idea of a sign-up screen with single sign-on options and added a ‘Refresh status’ button on the order summary screen for the first round of usability testing.
    image: wireframe2.png
testing:
  notes:
    - I conducted **two rounds of unmoderated usability studies** with five participants–first to evaluate the **low-fidelity prototype**, and then to test the **high-fidelity prototype**.
    - Three of the five participants were new or recent college graduates who use food delivery apps often, while two were retired and were familiar with, but not frequent users of food delivery apps.
  image: test.gif
  tests:
    - Sign up to create new account.
    - Select menu item and add to cart.
    - Complete checkout for pickup order.
    - Track progress of order. Return to home once order is complete.
solution:
  images: 
    - image: design.png
      caption: Final designs
  examples:
    - title: Intuitive Navigation
      before: Users noted that navigating the homepage wasn’t intuitive, so I eliminated the CTA buttons and considered different layouts to make the ordering flow as straightforward as possible.
      images:
        - image: solution_1_1.png
          caption: Second lo-fi iteration
        - image: solution_1_2.png
          caption: First mockup
        - image: solution_1_3.png
          caption: Third mockup
      after: Instead of listing the full menu on the homepage, I opted for multiple access points from the homepage–through search, ‘See all’ CTA, and top categories. During the second usability study, users easily navigated through the homepage, with most directly adding to their cart from the ‘Favorites’ quick-add cards.
    - title: Order History
      before: Users had difficulty finding the checkout page during the first usability study, as the designs featured both a cart icon in the top right corner and an ‘Orders’ tab on the bottom navigation bar. To avoid confusion, I combined them into one by replacing the original icon for the ‘Orders’ tab with the cart icon. I also added visual cues for the filled cart icon and the ‘View Cart’ button to provide consistency for all clickable elements.
      images:
        - image: solution_2_1.png
          caption: First lo-fi iteration
        - image: solution_2_2.png
          caption: Final design - ‘Cart’ screen
        - image: solution_2_3.png
          caption: Final design - ‘Orders’ screen
      after: Following the second round of testing, I designed the ‘Orders’ screen, which I hadn’t included in the main user flow. Users wanted easy access to current and past orders so I created two tabs–’Cart’ and ‘Orders.’ The order history page displays a ‘Reorder’ button next to a completed order and a ‘Track’ button next to an active order.
final_designs:
  - details: 
    - detail: Task 1
      info: Sign up to create a new account
    - detail: Feature
      info: Single sign-on, 2-factor authentication
    - detail: Rationale
      info: "My competitive analysis revealed a user preference for single sign-on, so I provided single-sign on options and two-factor authentication for a quicker login/signup process."
    image: design1.gif
  - details:
    - detail: Task 2
      info: Select menu item and add to cart
    - detail: Feature
      info: ‘Quick-add’ cards, customization options
    - detail: Rationale
      info: The interviews highlighted users’ need for efficiency and customization options, so I featured shortcuts to order favorites and popular items from the homepage, as well as a ‘Special Instructions’ box on the item screen for any notes to the kitchen.
    image: design2.gif
  - details:
    - detail: Task 3
      info: Complete checkout for pickup order
    - detail: Feature
      info: Completion estimates, loyalty discounts
    - detail: Rationale
      info: Users wanted the ordering process to be smooth and reliable, so I included completion estimates for each order option. I also included a pop-up to display applicable loyalty discounts at checkout to encourage customer retention.
    image: design3.gif
  - details:
    - detail: Task 4
      info: Track order progress. Return home once completed.
    - detail: Feature
      info: Live order tracking, key info in order summary
    - detail: Rationale
      info: Users wanted to time their pickup to their schedule and have an easy handoff at the restaurant, so I included a live status bar along with key order information (customer name, order number, items) on the ‘Order Summary’ screen.
    image: design4.gif
takeaways:
  summary: This was my first portfolio project in the Google UX Design certificate program, as well as my first experience designing with Figma. Throughout Courses 2-5, I began practicing and implementing the principles I was learning about. Watching my designs come to life and receiving user feedback was an extremely rewarding and insightful process. I also learned the hard way that documentation and organization are critical to the design process after I jumped into editing initial iterations, eager to address user concerns.
  lessons:
    - lesson: Navigation
      learning: I learned that prioritizing the user means understanding the existing navigational patterns and information architecture that they are familiar with.
    - lesson: Accessibility
      learning: I learned that designing for people who use assistive technologies improves the user experience for all users through icons, bottom navigation bars, and an accessible color palette.
    - lesson: Labels
      learning: I learned that all button labels and CTAs should use language that is straightforward and understandable for users regardless of their familiarity with similar food ordering apps.
  next_steps:
    - Conduct a third usability study to evaluate whether the pain points users experienced have been effectively addressed
    - Conduct more user research to determine any new areas of need
---