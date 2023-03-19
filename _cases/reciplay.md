layout: case
name: reciplay
title: Reciplay
tagline: Cookbook tool to empower users who are new to technology
description: 
  - For the final project in the Google UX Design Professional Certificate program, I created a cookbook tool for users who are new to technology.
  - My client, Reciplay, is dedicated to creating a cookbook tool that inspires and empowers its users to enjoy the process of cooking and trying new recipes.
backLink: /cases/nycbest
nextPage:
  title: Nonna's
  link: /cases/nonna
overview:
  deliverable: Dedicated mobile app<br>Responsive website
  roles:
    - Concept
    - Research
    - Visuals
    - Interaction
  duration: Feb - Mar 2023
  tool: Sketch
  problem: Available cookbook apps and sites have cluttered designs that aren’t intuitive for users who are new to technology to navigate.
  solution:
    tag: Design a cross-platform experience (i.e. mobile app and responsive website) that will provide users who are new to technology with an easy way to save and consult recipes, in addition to empowering them to explore new recipes.
research:
  description: To understand the users I was designing for and their needs, I conducted qualitative research through a **competitive audit**, **empathy maps**, **interviews**, and **personas**.
  questions:
    - Who are our users?
    - What are their goals?
    - In what context are they experiencing the app?
  target:
    description: "The primary user group is users who are new to technology. To learn more about these users’ context, I consulted Google’s resources on the ‘Next Billion Users’ and the ‘Designing for Digital Confidence’ site. This research revealed that digital fluency was not the only factor affecting the accessibility and usability of available cookbook apps. Other factors included device sharing and textual and numerical literacy.
    <br><br>Due to the time constraints for this project and my limited access to a diverse group of users who are new to technology, I focused on English-speaking users based in the United States who did not grow up with computers or mobile phones."
  personas:
    - name: Baker
      age: 68
      job: Retired
      image: portrait1.png
      needs:
        - Quick + easy way to enter  recipes on their phone
        - Accessible text color and size options
        - Consolidated grocery list from multiple recipes
    - name: Betsy
      age: 75
      job: Retired
      image: portrait2.png
      needs:
        - Step-by-step view to consult while cooking
        - List of ingredients needed for each step
        - Easy way to save online recipes
  challenges:
    - Not assistive technology accessible
    - No descriptive filters
    - Poor information architecture
  opportunities:
    - Optimize for assistive technologies
    - Provide descriptive filters
    - Clear information architecture
  competitive_analysis:
    summary: Next, I selected three direct competitors from the highest rated cookbook apps on the App Store, along with one indirect competitor that offers meal kits.
    competitors:
      - competitor1.png
      - competitor2.png
      - competitor3.png
      - competitor4.png
ideation:
  summary: Using the **Crazy Eights exercise**, I sketched out different iterations of the homepage with these user pain points and improvement opportunities in mind.
  diagram:
    image: ideation.png 
sitemap:
  summary: I created two different sitemaps for the responsive website. The first sitemap is targeted towards prospective users that don’t yet have an account. Each page will focus on demos and explanations of each feature. The second sitemap is for current users who have logged into their account. They can take the same actions that they would on the mobile app.
wireframes:
  summary: For the digital mobile app wireframes, I designed each step of the import process as a separate screen instead of relying on swiping and other navigational patterns more suited for users familiar with technology.
  images:
    - wireframe.png
    - wireframe2.png
    - wireframe3.png
testing:
  notes:
    - I conducted a usability study to evaluate what specific difficulties users who are new to technology encounter when they try to complete the core tasks using the low-fidelity prototype for the mobile app.
    - The findings from this usability study revealed that the initial import process relied too heavily on textual cues that weren’t familiar to users who weren’t familiar with online cookbook apps.
  study_type: Moderated
  location: United States
  participants: 2 participants
  length: 20-30 minutes
  image: test.gif
  tests:
    - Add a new online recipe to your cookbook.
    - Complete the import process and save the recipe.
    - View the recipe.
  insights:
    - Users want to see guiding text and understand the ‘URL Import’ and ‘Cooking Mode’ CTAs regardless of their familiarity with  online cookbooks.
    - Users want to see the parsed (unit/ingredient/note) format on the ‘Review Ingredients’ page only after clicking on the ingredient to edit it.
final_designs:
  - title: Introductory Screens
    summary: A confusing or vague onboarding flow is often a source of drop-off for users who are new to technology. To address this, I added three opening screens before the login page that introduce users to the features of the app with a visual and explanation.
    image: design1.png
  - title: Visual and Textual Clues
    summary: I added small popups using non-technical language to provide guidance for users who may be confused about CTAs like ‘Recipe Import’ and ‘Start Cooking.’
    image: design2.png
  - title: Guiding questions for import process
    summary: I crafted questions using open, friendly language to guide users through what information has been imported from the online recipe. While existing recipe apps often immediately import the online recipe without asking you to edit it, I noticed that page to add an original recipe is often entirely different from the editing process and provides little instructions. Consistency is essential in designing for users who are new to technology so I wanted to keep this format the same for both user flows for adding a new recipe.
    image: design3.png
  - title: Cooking Mode
    summary: I included a cooking mode that presents each step of the recipe, including which ingredients are needed and sentences separated visually for easier legibility. The cooking mode also features only three buttons to move backwards, forwards, or exit the flow because users new to technology prefer linear navigation (forward and back).
    image: design4.png
takeaways:
  summary: This was my final portfolio project in the Google UX Design certificate program so I took the initiative to design it in Sketch. Jumping into the design process with a tool not covered in the courses pushed me to learn the skills more intimately through trial-and-error. I applied all the skills I had gained throughout the courses and realized I still had so much more to learn
  lessons:
    - lesson: User Context
      learning: I learned how important research on the user context is in determining the design layout, navigation, and features. My initial designs relied on common visual and navigational patterns that are not familiar to those with low digital confidence, which was revealed through the usability test.
    - lesson: Accessibility
      learning: I realized that there is always more work to be done to make a truly accessible solution that serves my primary user group. If I had more time and a larger pool of participants for usability testing, I would add a settings page to customize screen contrast and text size.
    - lesson: Consistency
      learning: I learned how invaluable consistency is when creating a cross-platform experience, particularly for users new to technology. When considering my users’ needs, I realized that I needed to rework the responsive site mockups to make the features and visuals consistent with the mobile app.
  next_steps:
    - Conduct follow-up usability testing on the responsive website.
    - Ideate on new features like incorporating timestamped portions of a video tutorial into the cooking mode.
