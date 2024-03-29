---
layout: case
order_number: 1
name: reciplay
title: Reciplay
description: Empowering users new to technology
tagline: "Empowering users new to technology&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"
backLink: /cases/nycbest
solution_top: true
nextPage:
  title: About
  link: /about
banner:
  deliverable: Responsive website<br>Mobile app
  roles:
    - Concept
    - Research
    - Visuals
    - Interaction
  duration: Feb - Mar 2023
  tool: Sketch
overview:
  problem: "*What should I cook today?* &nbsp;The age-old question. Countless cookbook sites and apps have been created to address this dilemma in the digital age, **but do they really cater to every user?**"
  examples:
    - image: example1.png
      rounded: true
      small: true
  list: true
  after:
    - Many existing cookbook apps are not only cluttered and inefficient, but they also rely on patterns familiar to users with digital literacy, like how to navigate from screen to screen, what’s tappable and what’s not.
    - For users who are new to technology, however, knowing what icons mean or how to even begin are significant barriers to using these apps.
  solution:
    title: A tailored solution
    description: 
      - paragraph: With these barriers in mind, I  I sought to design a cross-platform experience that inspires and empowers new technology users to enjoy the process of cooking and trying new recipes.
      - paragraph: The solution covers all parts of the cooking process, with features like **URL import** and **a cooking mode**. For this project, I focused on recipe saving and viewing for the main user flow.
research:
  description: 
      - >
        To learn more about the user context of those new to technology, I consulted Google’s resources on the <a href="https://nextbillionusers.google/" target="_blank">Next Billion Users</a> and <a href="https://digitalconfidence.design/" target="_blank">Designing for Digital Confidence</a>.
         - Users with low digital confidence can quickly feel lost within an app and often turn to friends or family for help.
         - They need relevant options and time to build their confidence and overcome the fear of doing something ‘wrong.’
      - Through my interviews with five individuals, ages 60-80, I learned that most would be open to learning a new cookbook tool if it was free and took the mental work out of the cooking process.
      - "I created two personas based on the users I interviewed: the physical cookbook user and the app user."
  personas:
    - title: The Cookbook User
      age: 68
      job: Retired
      image: portrait1.png
      description:
        - Leo is a recently retired hairstylist living in Hoboken. Now that they are retired, they’ve been trying new recipes from a cookbook. They usually write a list of the ingredients needed for a few recipes and buy them all in one trip.
        - They’d be open to learning how to use a cookbook app if it did all the tedious work for them, like calculating ingredient amounts and creating grocery lists.
    - title: The App User
      age: 75
      job: Retired
      image: portrait2.png
      description:
        - Gina is a retired accountant living in Troy with her husband. She loves finding new recipes on Facebook and saving them to collections. She uses Amazon Alexa voice commands to add items to the shopping list and set timers while cooking.
        - It takes some time–and help from her husband–to learn new digital skills so she’d be reluctant to try a new app, unless she was confident that she could use it on her own.
  challenges:
    description: "Based on the user interviews, I found the following improvement opportunities:"
    list:
        - Users want a cookbook tool that takes care of the **non-cooking tasks** for them.
        - Users want to be **guided through each feature** every time they use the app.
  competitive_analysis:
    summary: 
        - I then selected **three direct competitors** among the highest rated cookbook apps on the App Store, along with **one indirect competitor** that offers meal kits.
        - I used the <a href="https://digitalconfidence.design/tools/design-principle-cards" target="_blank">Design Principle Cards</a> from <a href="https://digitalconfidence.design/" target="_blank">Designing for Digital Confidence</a> to check whether each app accounted for users who are new to technology.
    image: competitive_analysis.jpeg
    analysis: 
        - While most of the apps featured straightforward navigation, none fully addressed the needs of users new to technology in their discovery and onboarding flows. I identified features like **progress indicators, tips within the interface, text and voice input options** to include in my own designs that would address these needs.
  insight: Users new to technology need an experience with **timely guidance** and **multiple modes of interaction**.
ideation:
  summary: I drafted different homepage iterations by drawing on the <a href="https://digitalconfidence.design/tools/inspiration-tool" target="_blank">Inspiration Tool</a> from <a href="https://digitalconfidence.design/" target="_blank">Designing for Digital Confidence</a> to challenge my perspective.
  after: 
    - description: Next, I created five paper wireframes from the mobile app homepage sketches. For the revised homepage, I included voice search, two ways to add a new recipe, and a bottom navigation bar.
      image: ideation1.png
    - description: I repeated the Crazy Eights exercise for the responsive site designs to consider how site users may have different needs than the mobile app users.
      image: ideation2.png
    - image: ideation3.png
sitemap:
  - summary: Users with low digital confidence can quickly feel lost and not know where they are within an app or site, so I **simplified the content structure and made it consistent across platforms**.
    image: sitemap1.png
wireframes:
  - summary: New technology users need time to build their digital confidence, so I sectioned the import recipe process into manageable chunks, with the recipe information pre-populated from the URL.
    image: wireframe1.png
  - summary: I incorporated “Back” and “Next” buttons on each screen of the import flow instead of relying on swiping and other navigational patterns more suited for users familiar with technology.
  - image: wireframe2.png
    caption: Responsive mobile site wireframe
  - summary: I began drafting the responsive site wireframes, keeping some aspects, like the recipe list layout, consistent with the mobile app. I also included some features based on the ideation exercises that would be specific to the responsive site use case, such as bulk recipe import.
    image: wireframe3.png
    caption: Responsive desktop site wireframe
testing:
  notes:
    - I conducted a moderated usability study with five participants to evaluate the low-fidelity prototype and discover what specific difficulties users who are new to technology encounter going through the main user flow.
    - Three of the five participants were users new to technology, while the other two were users familiar with technology but new to cooking apps.
  image: test.gif
  tests:
    - Add a new online recipe to your cookbook
    - Complete the import process and save the recipe.
    - View the recipe.
solution:
  examples:
    - title: Guidance
      before: Users were confused by jargon like “URL” and “Cooking Mode” and suggested alternatives like “link” and “Start Cooking” that they would be more familiar with. Some users were also confused by how to input information, like copying and pasting a link and editing an ingredient.
      images:
        - row:
          - image: solution1_1.png
            caption: First lo-fi iteration
          - image: solution1_2.png
            caption: Final design - ‘Import’ screen
          - image: solution1_3.png
            caption: Final design - ‘Link’ info screen
      after:
          - In addition to changing jargon to more accessible language, I added tips within the interface and access to help via a call or chat for in-the-moment guidance. Users can also click on the info icon for a visual and textual description for each question of the import process.
    - title: Navigation
      before: After reviewing the usability test feedback, I realized that my designs relied on users finding features via the UI. The participants of the usability test were able to enter the user flow due to specific prompts, but they may not have been able to navigate the app’s features otherwise.
      images:
        - row: 
          - image: solution2_1.png
            caption: First lo-fi iteration
          - image: solution2_2.png
            caption: Second mockup
          - image: solution2_3.png
            caption: Final design
        - row:
          - image: solution2_4.png
            caption: First mockup - responsive site (tablet)
          - image: solution2_5.png
            caption: Final design - responsive site (tablet)
        - row:
          - image: solution2_6.png
            caption: First mockup - responsive site (desktop)
        - row:
          - image: solution2_7.png
            caption: Final design - responsive site (desktop)
      after: 
          - To simplify the cognitive load of navigation and orient the user, I created a homepage with tappable discovery interfaces and text and voice search options to provide users with multiple modes of discovery and interaction. I used this format for both the mobile app and the responsive site for a consistent cross-platform experience.
final_designs:
  designs:
    - details:
      - detail: Task 1
        info: Select an action from the homepage.
      - detail: Feature
        info: Voice search, call/chat assistance
      - detail: Rationale
        info: Users can request a feature through voice commands, suggestions, or search history instead of navigating to it. When in need of assistance, users can consult the support page on each screen, for a list of FAQs and call/chat options.
      image: design1.gif
      rounded: true
    - details:
      - detail: Task 2
        info: Import new online recipe with URL.
      - detail: Feature
        info: Textual response cues, jargon breakdown
      - detail: Rationale
        info: Users are guided through the import process with example responses and an info icon to see simple definitions for confusing terms. The import process is shortened into manageable sections, with the recipe information already pre-populated.
      image: design2.gif
      rounded: true
    - details:
      - detail: Task 3
        info: View the saved recipe.
      - detail: Feature
        info: Contextual onboarding, action visualization
      - detail: Rationale
        info: Users are proactively introduced to the “Start Cooking” feature in context. The cooking mode screen then shows users how to rotate their phone before trying it themselves.
      image: design3.gif
      rounded: true
takeaways:
      summary: I took the initiative to learn Sketch for this final portfolio project for the Google UX Design certificate program. Jumping into the design process with a tool not covered in the courses pushed me to learn the skills more intimately through trial-and-error. Designing for a user group with very different needs and contexts than my own challenged my preconceived notions about how navigation, discovery, and onboarding ‘should’ look.
      lessons:
        - lesson: Consistency
          learning: I learned how invaluable consistency is when creating a cross-platform experience, particularly for users new to technology. When considering my users’ needs, I realized that I needed to rework the responsive site mockups to make the features and visuals consistent with the mobile app.
        - lesson: Accessibility
          learning: I learned that there is always more work to be done to make a truly accessible solution that serves my primary user group. If I had more time and a larger pool of participants for usability testing, I would add a settings page to customize screen contrast and text size.
      next_steps:
        - Evaluate the success of the product by measuring time on task, task success rate, and user error rate
        - Conduct follow-up usability testing on the responsive website to determine any barriers that users new to technology face in the main user flow
        - Ideate on new features like incorporating timestamped portions of a video tutorial into the cooking mode, ingredient look-up, and translation options
---