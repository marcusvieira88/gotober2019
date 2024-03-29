[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# gotober2019
Repository used to store the links and notes that I got in the GOTO Berlin 2019 conference [GOTO YOUTUBE](https://www.youtube.com/channel/UCs_tLP3AiwYKwdUHpltJPuA).

### REST beyond the Obvious - API Design for ever Evolving Systems

- API versioning is a hard process, because that, the importance to invest in decouple systems, in the API case, decouple the Front from Backend.
- Use HATEOAS to achieve this decoupling (business logic and validation)
- [Presentation](https://www.youtube.com/watch?v=mQkf85S9UoQ)

### “Good Enough” Architecture

- Some examples of good and bad architectures.
- Many small microservices/functions can not be a good idea when the company grows.
- When you have autonomous teams(technology independent) creating microservices you need to set some rules to avoid integration issues.  
- [Podcast](https://www.case-podcast.org/4-software-architecture/transcript)

### Moving Fast At Scale

- Organization Culture 
- [Theory X vs Theory Y](https://en.wikipedia.org/wiki/Theory_X_and_Theory_Y)
- [Psychological Safety](https://www.infoq.com/articles/psychological-safety-models-experiences/?itm_source=articles_about_Psychological-Safety&itm_medium=link&itm_campaign=Psychological-Safety) 
- [Lean](https://en.wikipedia.org/wiki/Lean_software_development)
- [Presentation](https://www.youtube.com/watch?v=t-sIaw4kHqI) 

### Amazing Code Reviews: Creating a Superhero Collective

- Keep PRs small - 200/300 lines
- Share drafts early
- Focus on the work, not the person
- Offer actionable feedback
- Pick the right people
- Send draft PRs to get feedback early.
- [Use Stacked PRs](https://graysonkoonce.com/stacked-pull-requests-keeping-github-diffs-small/)
- [KISS principle](https://www.interaction-design.org/literature/article/kiss-keep-it-simple-stupid-a-design-principle)

### Serverless 2.0: Get started with the PLONK Stack

- [Serverless in 60 seconds](https://skillsmatter.com/skillscasts/10813-faas-and-furious-0-to-serverless-in-60-seconds-anywhere)
- [Presentation](https://blog.alexellis.io/getting-started-with-the-plonk-stack-and-serverless/)

### Composing Bach Chorales Using Deep Learning

- [Presentation](https://www.youtube.com/watch?v=yu3DZuxxV7c)

### 3 Common Pitfalls in Microservice Integration and How to Avoid Them

- Fail Fast
- Circle Breaker [Histrix](https://github.com/Netflix/Hystrix) and [Resilience4j](https://github.com/resilience4j/resilience4j)
- Microservice Stateful Retry (State Machine or workflow)
- [Akka Saga Pattern](https://blog.knoldus.com/microservices-and-the-saga-pattern/)
- [Article](https://www.infoworld.com/article/3254777/3-common-pitfalls-of-microservices-integrationand-how-to-avoid-them.html)
- [Presentation_(https://www.youtube.com/watch?v=JugjRg0-pnE)

### Designing APIs for 150 Million Orders

- [DDD](https://en.wikipedia.org/wiki/Domain-driven_design)
- [EventStorms](https://techbeacon.com/devops/introduction-event-storming-easy-way-achieve-domain-driven-design)
- [Design System](https://www.learnstorybook.com/design-systems-for-developers/)
- [CloudEvents - Standardize messages](https://cloudevents.io/)
- [CloudEvents Demos](https://github.com/cloudevents/spec/blob/master/community/demos.md)
- [BFF](https://samnewman.io/patterns/architectural/bff/)

### Monolith Decomposition Patterns

- [SAFE](https://www.scaledagileframework.com/)
- [CAP Theory](https://dzone.com/articles/cap-theorem)
- [Slides Presentation](files/monolith_decompositon_patterns.pdf)    

### Get Ready to Rock with Sonic Pi - The Live Coding Music Synth for Everyone

- [Presentation](https://www.youtube.com/watch?v=OLLwG_SN8oo)

### Building Better Products Faster: DevUx is the New DevOps

- [Zeplin app for mockups](https://zeplin.io/)
- Frontend needs to folow Styleguide for:
    - Buttons / Inputs 
    - Colors 
    - Fonts
    - Regular Flow (User Flow)
    - Dashboard Layout (How the components are distribuited in the page)
    - Common Components
    - Centralize Style guide variables e.g. [styleint](https://github.com/stylelint/stylelint)
- [Figma Design](https://www.figma.com/)
- [LeanUX](https://www.oreilly.com/radar/what-is-lean-ux/)
- [Five Dysfunctions of a Team](https://en.wikipedia.org/wiki/The_Five_Dysfunctions_of_a_Team)
- [Presentation](https://www.youtube.com/watch?v=P21O_6OqpR0&feature=youtu.be&t=27052)

### Interaction Protocols: It's All About Good Manners

- Use regular expressions to document APIs
- [Falsifiability](https://en.wikipedia.org/wiki/Falsifiability)
- APIs should work with binary enconde (less processing to decode)
- [Presentation](https://www.youtube.com/watch?v=A5ovSBt0-C0)

### Crucial Career Conversations

- [Psychological_safety](https://en.wikipedia.org/wiki/Psychological_safety)
- Make it safe to fail
- Remove items from the sprint to give time to developers time to lear something new.
- [Lead Dev youtube channel](https://www.youtube.com/channel/UCmM3eCpmWKLJj2PDW_jdGkg)
- [Presentation](https://www.youtube.com/watch?v=DTAXQNJLskk)

### Building Resilient Frontend Architecture

- Decoupling > [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) 
- Contraints for more resilient frontend architecture:
    - Source code dependencies must point inward
    - Be conservative about code reuse
    - Enforce your boundaries
- [Presentation](https://www.youtube.com/watch?v=HudXYWLBTHw)
