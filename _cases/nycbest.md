---
layout: case
order_number: 3
name: nycbest
title: NYC's Best
description: Redefining the pet adoption process
tagline: "Redefining the pet adoption process&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"
button: Responsive Web App
backLink: /cases/nonna
nextPage:
  title: Reciplay
  link: /cases/reciplay
banner:
  deliverable: Responsive website
  roles:
    - Concept
    - Research
    - Visuals
    - Interaction
  duration: Dec - Feb 2023
  tool: Adobe XD
overview:
  problem: "Finding our new furry best friend and family member is one of the biggest decisions we make in our lives, yet existing pet adoption sites often fail to reflect that reality. Whether you’re experienced or a first-time pet parent, you likely have your own, unique criteria that you’re looking for. So, **why is it so difficult to browse pet adoption sites?**"
  examples:
    - image: example1.png
      caption: Layout of existing pet adoption site
      rounded: true
  list: true
  solution:
    title: Redesigning the adoption flow
    description:
      - paragraph: My pain points with cluttered, overwhelming pet adoption sites led me to to design a responsive website for a local pet adoption organization. Let’s call it NYC’s Best, a no-kill animal shelter with three locations in New York City. They are dedicated to rescuing, rehabilitating, and finding forever homes for homeless and abandoned cats, dogs, and rabbits.
      - paragraph: “We’d like to help our patrons through the pet-finding process by **providing search options that mirror their own criteria.**”
        quote: true
      - paragraph: To stand out in the market, I aimed to design a user-friendly, responsive website that features **clear navigation** and **an efficient search and adoption process**. Above all, I wanted it to be a positive experience that reflects the *excitement* of starting a new chapter in your life.
research:
  description:
    - I began with secondary research on what criteria potential adopters use to search for a new pet. I learned that the criteria used varies between cat adopters and dog adopters. **Personality and behavior ranked highest for cat adopters**, while **dog adopters prioritized physical characteristics**, such as breed.
    - Of the eight individuals I interviewed, I found that **meeting the pet in person was the ultimate deciding factor**, even for those who had already had their heart set on that specific pet prior to coming to the shelter.
    - "I created two personas based on these findings: **the dog adopter** and **cat adopter**."
  personas:
    - title: The Dog Adopter
      age: 28
      job: Dental Hygienist
      image: portrait1.png
      description:
        - Niamh is a dental hygienist at a clinic in Detroit. She’s finally reached a place in her life where she feels more settled, with a stable job and relationship. She’s always wanted to adopt a dog but wanted to wait until she felt ready.
        - Now she’s committed to finding a dog and has a few breeds in mind but the searching process has frustrated her due to unfilterable listings and unclear adoption processes.
    - title: The Cat Adopter
      age: 21
      job: College Senior
      image: portrait2.png
      description:
        - Winston is a senior in college living in Seattle. He’s interested in adopting a cat as a first-time pet parent.
        - He’s not sure what characteristics to base his search on with the limited filters and vague personality descriptions on existing sites. He’d rather save time by going to the shelters themselves if it weren’t for unclear adoption processes.
  challenges:
    description: "I reframed the insights from the research as improvement opportunities for the NYC’s Best site:"
    list:
        - "Users want **descriptive filters** that reflect their own criteria."
        - "Users want a **simple adoption process** that saves them time."
  competitive_analysis:
    summary:
        - After gaining an understanding of the user needs and context, I wanted to evaluate how existing animal shelters approached solving these user problems.
        - I selected **two direct competitors** among local animal shelters, along with **two indirect competitors** that offer services for pet owners.
    competitors:
        - competitor1.png
        - competitor2.png
        - competitor3.png
        - competitor4.png
    analysis: 
        - I rated each on aspects like desktop website experience, features, user flow, navigation, brand identity, and descriptiveness. **App or mobile website experience, accessibility, and user flow each received at least two ‘Needs work’ ratings**. Half of the competitors’ sites weren’t optimized for mobile or assistive technologies, preventing key information from being accessible at all. In addition, important information like adoptable cats or service availability was difficult to find on the site itself, involving multiple clicks and scrolling, or hidden until registration.
  insight: "**Users need a fully responsive, assistive-technology friendly site with easy access to key information.**"
ideation:
  summary: Using **How Might We questions**, I brainstormed different approaches to rethinking the pet adoption flow.
  title: "How might we..."
  tables: 
    - title: Amp up the good?
      image: ideation_figure1.png
      list: 
        - Quiz to be matched with pets
        - Pet spotlights for those at shelter longest
        - Online scheduling to meet
        - Dating-app-like pet profiles
    - title: Change the status quo?
      image: ideation_figure2.png
      list: 
        - 1-2-3 step adoption process
        - Choose filters on homepage that matter most to you
        - Randomize results/profiles
        - Foster for a night
    - title: Break the POV into pieces?
      image: ideation_figure3.png
      list: 
        - Digestible pet profiles (map w/ shelter location)
        - Standardized profile sections
        - Share profile with shelter to be matched
        - Processing status on pet profile
  after:
    - description: "I then sketched out eight of these ideas using the **Crazy Eights exercise** to visualize how they would work:"
    - image: ideation_after1.png
      description: Next, I sketched out four different iterations of the homepage, with a focus on avoiding a text-heavy screen for a quicker browsing experience. I also added some of my ideas from the above exercises, like **pet profile spotlights** and a **1-2-3 step adoption process**.
    - image: ideation_after2.png
      description: For the refined version (on the right), I prioritized a **quick and easy way to search pet profiles** using filters like location and pet type to help users save time.
sitemap:
  - summary: "**Difficulty with website navigation** was a primary pain point for users, so I aimed to make the information architecture **simple and intuitive**. I created the sitemap with the common structure used by existing animal shelters in mind."
    image: sitemap.png
wireframes:
  - summary: The first iteration of wireframes included features generated during the ideation exercises–**a search bar, 3-step breakdown of the adoption process, pet spotlights**. I included multiple ways to enter the adoption flow on the homepage through search, pet categories, and the top navigation bar.
    image: wireframe.png
  - image: wireframe1.png
  - summary: "For the second iteration, I switched up the layout to make each section more **visually engaging, digestible, and concise**. I prioritized keeping pet spotlights above the fold because they feature the top criteria for both cat and dog adopters: personality and physical characteristics. I also got rid of the profile carousels categorized by personality in favor of displaying all profiles, supplemented by descriptive filters, to serve the needs of both cat and dog adopters."
    image: wireframe2.png
testing:
  notes:
    - I conducted an **unmoderated usability study** with five participants to evaluate the low-fidelity prototype and **discover what specific challenges users face in the navigation and pet adoption process**.
    - Three of the five participants were current cat or dog parents, while the remaining two didn’t have pets but had previously considered the possibility of adopting.
  image: test.gif
  linear: true
  tests:
    - View adoptable pet profiles.
    - Select a cat profile.
    - Apply to adopt the cat.
    - Schedule an appointment to meet them.
solution:
  images: 
    - image: design.png
      shadow: true
    - image: design2.png
      shadow: true
    - image: design3.png
      full: true
  examples:
    - title: User Flow
      before: The usability study uncovered some aspects of the user flow that weren’t as intuitive as I had imagined. Firstly, the low-fidelity prototype featured an overlay previewing the profile for quick browsing, but users expressed confusion about not being directly taken to the profile from the listings page. Secondly, users were confused about whether to apply to adopt or schedule the meet-and-greet first from the pet profile page.
      images:
        - row:
          - image: solution1_1.png
            caption: First lo-fi iteration
        - row:
          - image: solution1_2.png
            caption: First hi-fi iteration
        - row:
          - image: solution1_3.png
            caption: Final design - 3-step adoption breakdown on homepage
        - row:
          - image: solution1_4.png
            caption: Final design - Pet profile
      after: For the final designs, I reworked the 3-step adoption process to make the user flow more straightforward. Since users would’ve liked to meet the pet before investing time in the adoption application, I added a feature I had thought of during the ideation stage–a quiz that matches you with pets that fit your criteria. Users can then schedule a meet-and-greet with any or all of the matches and fill out an adoption application in person or on the site.
    - title: Adoption Application
      before: The overall feedback about the adoption application was that it was too long and involved too much scrolling. Users pointed out that there should be a way to select whether certain sections were applicable or not because it lengthened the application considerably.
      images:
        - row:
          - image: solution2_1.png
            caption: First lo-fi iteration
        - row:
          - image: solution2_2.png
            caption: Third hi-fi iteration
        - row:
          - image: solution2_3.png
            caption: Final design - Adoption application
      after: To address these pain points, I modeled the adoption application after the pet matching quiz, capping it at ten questions. I kept only the essential open-response questions and added 2-5 response options for all other questions to make the filling out process more efficient and engaging. I also moved some of the questions from the adoption application to the pet matching quiz to account for contextual information needed to match users with the right pets. The user profile would then save this information, eliminating the need to ask the same questions twice.
final_designs:
  sidebar: true
  designs:
    - details:
      - detail: Task 1
        info: Take quiz to be matched with pets
      - detail: Feature
        info: 1-2-3 step adoption adoption process, pet matching quiz
      - detail: Rationale
        info: Both the user research and usability study revealed a need for a simple, straightforward user flow. From the homepage, users are directed to take a 10-question quiz that gauges their criteria and matches them with pets.
      image: design1.gif
      rounded: true
      column: true
    - details:
      - detail: Task 2
        info: View profile(s) and schedule meet-and-greet
      - detail: Feature
        info: Dating app-style profiles, online meet-and-greet scheduling
      - detail: Rationale
        info: Once users have created an account to view their matches, their information is saved and they can schedule a meet-and-greet in under two minutes. My user research also highlighted a preference for information that reflects their own criteria so each pet profile includes descriptive tags and Hinge-style prompts.
      image: design2.gif
      rounded: true
      column: true
    - details:
      - detail: Task 3
        info: Apply to adopt a pet
      - detail: Feature
        info: 10-question adoption application
      - detail: Rationale
        info: The usability study uncovered a need to rework the adoption process and redesign the application to decrease drop-off. After meeting their matches, users can then decide to apply to adopt either in-person or online. The adoption application mirrors the format of the pet matching quiz, with a few response options and minimal scrolling.
      image: design3.gif
      rounded: true
      column: true
takeaways:
    summary: This was my second portfolio project in the Google UX Design certificate program, as well as my first experience designing with Adobe XD. Designing for bigger screen sizes for the first time felt very daunting initially, but I learned to appreciate the blank real estate and the value of white space.
    lessons:
      - lesson: Research
        learning: I learned the importance of backing my designs with data from my research and the usability study. I felt a bit stuck when I first designed the application flow so the feedback from the usability study was essential in informing my approach for the next iteration of designs.
      - lesson: Design Sprint
        learning: I learned that defining what is and isn’t within the project scope is an essential aspect of designing under time constraints. Unlike the first portfolio project for the Google UX Design course, multiple steps of the design process were outlined in a week’s work. This structure gave me some experience tackling weekly design sprints.
    next_steps:
      - Conduct a third usability study to evaluate whether the pain points users experienced have been effectively addressed
      - Conduct more user research to determine any new areas of need, such as customer reviews and pickup/delivery feedback
---