---
layout: case
name: nycbest
title: NYC's Best
tagline: Accessible and straightforward pet adoption site
button: Responsive Web App
description:
  - NYC’s Best is an animal shelter with three locations in New York City. They are dedicated to rescuing, rehabilitating, and finding forever homes for homeless and abandoned cats, dogs, and rabbits.
  - We aimed to provide its patrons with a quick way to **easily find and adopt a pet**.
backLink: /cases/nonna
nextPage:
  title: About
  link: /about
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
  problem: "Finding our new furry best friend and family member is one of the biggest decisions we make in our lives, yet available pet adoption sites often fail to reflect that reality. Whether you’re experienced or a first-time pet parent, you likely have your own, unique criteria that you’re looking for. Yet, **why is it so difficult to browse pet adoption sites?**"
  examples:
    - description: It often takes multiple clicks, each opening a new tab, to even reach the list of adoptable pets. Aside from the amount of clicks needed, the information is also cluttered and overwhelming to skim.
      image: example1.png
      caption: Layout of existing pet adoption site
      rounded: true
    - description: These sites often only cater to a specific user context– those using a computer–and fail to consider the needs of those accessing from a phone or tablet.
      image: example2.png
  list: true
  solution:
    title: Redesigning the adoption flow
    description:
      - paragraph: These pain points led me to to design a responsive website for a local pet adoption organization. Let’s call it NYC’s Best, a no-kill animal shelter with three locations in New York City. They are dedicated to rescuing, rehabilitating, and finding forever homes for homeless and abandoned cats, dogs, and rabbits.
      - paragraph: To stand out in the market, I aimed to design a user-friendly, responsive website that features **clear navigation** and **an efficient search and adoption process**. Above all, I wanted it to be a positive experience that reflects the excitement of starting a new chapter in your life.
      - paragraph: “We’d like to help our patrons through the pet-finding process by **providing search options that mirror their own criteria.**”
        quote: true
research:
  description:
    - I began with secondary research on what criteria potential adopters use to search for a new pet. I learned that the criteria used varies between cat adopters and dog adopters. **Personality and behavior ranked highest for cat adopters**, while **dog adopters prioritized physical characteristics**, such as breed.
    - Of the eight individuals I interviewed, I found that **meeting the pet in person was the ultimate deciding factor**, even for those who had already had their heart set on that specific pet prior to coming to the shelter.
    - "I created two personas based on these findings: **the dog adopter** and **cat adopter**."
  personas:
    - title: The Dog Adopter
      age: 28
      job: Dental hygienist
      image: portrait1.png
      description:
        - Niamh is a dental hygienist at a clinic in Detroit. She’s finally reached a place in her life where she feels more settled, with a stable job and relationship. She’s always wanted to adopt a dog but wanted to wait until she felt ready.
        - Now she’s committed to finding a dog and has a few breeds in mind but the searching process has frustrated her due to unfilterable listings and unclear adoption processes.
    - title: The Cat Adopter
      age: 21
      job: College Senior
      image: portrait2.png
      description:
        - Winston is a senior in college living in Seattle. He didn’t grow up with pets but he’s interested in adopting a cat because he’s heard that cats are better for first-time pet parents.
        - He doesn’t know where to start so he’s looked at multiple animal shelter sites but decided to just go to a shelter in person after seeing the limited filters, vague personality descriptions, and complex adoption processes.
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
    analysis: I rated each on aspects like desktop website experience, features, user flow, navigation, brand identity, and descriptiveness. **App or mobile website experience, accessibility, and user flow each received at least two ‘Needs work’ ratings**. Half of the competitors’ sites weren’t optimized for mobile or assistive technologies, preventing key information from being accessible at all. In addition, important information like adoptable cats or service availability was difficult to find on the site itself, involving multiple clicks and scrolling, or hidden until registration.
  insight: Users need a fully responsive, assistive-technology friendly site with easy access to key information.
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
        - 1-2-3 steps adoption process
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
  summary: "**Difficulty with website navigation** was a primary pain point for users, so I aimed to make the information architecture **simple and intuitive**. I created the sitemap with the common structure used by existing animal shelters in mind."
wireframes:
  - summary: The first iteration of wireframes included features generated during the ideation exercises–**a search bar, 3-step breakdown of the adoption process, pet spotlights**. I included multiple ways to enter the adoption flow on the homepage through search, pet categories, and the top navigation bar.
    image: wireframe.png
  - image: wireframe1.png
  - summary: "For the second iteration, I switched up the layout to make each section more visually engaging, digestible, and concise. I prioritized keeping pet spotlights above the fold because they feature the top criteria for both cat and dog adopters: personality and physical characteristics. I also got rid of the profile carousels categorized by personality in favor of displaying all profiles, supplemented by descriptive filters, to serve the needs of both cat and dog adopters."
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
  examples:
    - title: User Flow
      before: The usability study uncovered some aspects of the user flow that weren’t as intuitive as I had imagined. Firstly, the low-fidelity prototype featured an overlay previewing the profile for quick browsing, but users expressed confusion about not being directly taken to the profile from the listings page. Secondly, users were confused about whether to fill out the adoption application or schedule the Meet-and-Greet first.
      images:
        - image: solution1.png
          caption: Final design
      after: To address these user needs, I eliminated the unnecessary elements to make the user flow more streamlined and straightforward. I reordered the adoption process based on feedback that users would like to meet the pet before investing time in the adoption application. I then highlighted the two actions that a user may want to take at the top of the profile, and featured hyperlinks under the adoption process breakdown as well.
    - title: Adoption Application
      before: The overall feedback about the adoption application was that it was too long and involved too much scrolling. Users pointed out that there should be a way to select whether certain sections were applicable or not because it lengthened the application considerably.
      images:
        - image: solution2.gif
          caption: Final design
      after: In addition to adding conditional questions that either skip or unfurl additional questions, I considered how to make the application more engaging. After cutting out the non-essential questions, I played with the color scheme and size of the response boxes to make the overall application more digestible and skimmable. For my final designs, I also added a progress bar with textual and visual cues to discourage drop-off.
prototype:
  image: prototype.gif
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