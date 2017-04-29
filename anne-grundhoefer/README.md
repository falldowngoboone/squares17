# Design Systems: Enterprise UX Evolution
Anne Grundhoefer

Design systems create a shared vocabulary by creating categories, rules for use, consistency
Where there is no standard, you get inconsistency ([Allstate website](https://www.allstate.com))
Good example - [Dropbox website](https://www.dropbox.com/home)

## A Design System will provide value if your products…
* Need to look and behave similarly
* Implement similar UI components
* Duplicate low-level functionality
* Must be white-labeled or themed
* Are built on different tech stacks
* Suffer from visual regression bugs

## Benefits of a Design System
* Provide a single source of truth for building UIs
* Save time and money
* Increase consistency
* Decrease maintenance
* UX teams focus on the experience; dev teams on implementation

## Design systems are the new standard
* Salesforce
* U.S. Web Design Standards
* IBM
* Duolingo - smaller company
* Intuit Harmony
* Shopify

## Designs systems are not Bootstrap. WHY NOT?
* Those are rapid prototyping tools, not design systems
* Their components do not consider your unique context
* Not detailed enough
* You take power away from your developers
* You are beholden to their time and community (Bootstrap 3 was deprecated before Bootstrap 4 came out)

## Part of a Design System

### Foundations and Principles
* Guiding design principles
* Accessibility targets
* Animations
* Scaling
* Grids

### Brand Identity
* Fonts
* Colors
* Meaning
* Visual Language
* White Labeling
* Logo/Market related

### Editorial Guidelines
* Voice and Tone
* Word List
* Capitalization and Punctuation

### Pattern LIbrary
* UI Components
* Page Templates
* Reference Files (.psd, .ai, .sketch)

### Code
* Coding Standards
* Supported Browsers and Devices
* Versioning
* Pattern Implementation

> A design system isn’t a project. It is a product, serving products. 
> - Nathan Curtis

## Building a pattern library
1. Identify components with a checklist ([Nathan Curtis checklist](https://medium.com/eightshapes-llc/picking-parts-products-people-a06721e81742))
2. Cut-up components from various interfaces - cut out various types of UI from printouts of the client’s current site (the job is to curate what you already have
3. Lay a solid foundation for your components - start with smallest first, agree on naming
4. Design components from scratch - identify smallest pieces and start there; write down why you are making certain design decisions
5. Work closely with your team - schedule weekly reviews with stakeholders and developers; establish who maintains the style guide going forward

## Things to Consider
* Your software’s context - take into account the software you have today
* Your users - who are you designing for?
* Device support - modern, legacy web browsers native
* Responsive - what are your breakpoints/media?
* Accessibility - do you need Section 508 and WCAG 2.0 compliance ([wave.webaim.org](http://wave.webaim.org), [hexnaw.com](https://hexnaw.com))
* White-Label - does your experience need to be easily themed or rebranded
* Designing for all states
    * Nothing - the component exists but hasn't started
    * Loading - waiting for the component to render
    * None - the component has initialized, but it's empty
    * One - you have some data
    * Some - the ideal state for this component
    * Too Many - too many results/characters/etc.
    * Incorrect/Correct - success/error
    * Done - correct input has been received
    * Active/Hover/Focus - elements can be interacted with

## Building an implementation
* Enable faster and more consistent design and development
* Build self-contained components
* Deliver obvious value - provide useful assets and comprehensive documentation of how and when to use each component in the system

A Design System is not a design framework and should not be coupled to one.

### Do not
* Create a prescriptive application template
* Build on or for one particular framework

### Do
* Focus on building long-lasting vanilla HTML/CSS/JS
* Keep your components "dumb"
* Consider all your systems

Your output should be small, configurable, and well-documented components.

## Roll it out
* Make your Design system easy to consume and update
* Have a central repository
* Publish multiple ways
* Update frequently
* Make it collaborative
* Ensure reliability