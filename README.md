<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Career integrator AI

Final project for the Building AI course

## Summary

Career Integrator is an AI-based career planning assistant for international professionals entering Nordic's labour market. It analyzes professional profiles and comparable career journeys to suggest realistic next steps, alternative career paths, and skills to develop.

## Background

Experienced professionals relocating to a new country often struggle to translate their skills and qualifications into local job opportunities. Language barriers, unfamiliar hiring practices, and limited professional networks add further challenges. Inspired by my own relocation to Sweden and the experiences of other international professionals, I wanted to help skilled people understand the local job market and find realistic career paths that build on their previous experience.

Existing tools offer fragmented information and rarely provide clear, personalised career paths based on individual experience and local labour-market conditions.

- **Unclear career paths:** People don't know which career steps have worked for others with similar experience.
- **Overlooked skills:** Job searches often miss useful skills gained in other roles or countries.
- **Uncertain choices:** It's hard to know which skills to develop and how much time and money to invest.
- **Scattered information:** Job opportunities, market trends and training options are spread across different platforms.
- **Unclear qualifications:** Professionals may have the right skills but struggle to prove them to Swedish employers.
- **Language barriers:** Nordic languages requirements vary by profession, and language courses may not provide enough skills for work.

## How is it used?

A user visits Career Integrator to plan their career after moving to new region. 
Example of task: “I want to find a job in my profession.”

The process includes:

1. **Create a profile:** The user shares their education, work experience, skills, interests, psychological portrait based on approved methods ( like Holland's RIASEC Model), language level and career goals.
2. **Explore the job market:** AI analyses job vacancies, required skills and profiles of people already working in similar roles.
3. **Find similar career stories:** AI identifies how people with similar backgrounds found jobs and developed their careers in Sweden.
4. **Compare outcomes:** The system shows common career paths and employment results, including how long finding a job took, when reliable data are available.
5. **Identify skill gaps:** AI highlights missing skills, language requirements and qualifications that may improve job opportunities.
6. **Suggest career options:** The system recommends different career paths and compares their potential benefits, time and learning costs.
7. **Choose a path:** The user selects a preferred option and receives a personalised career plan.

The AI provides recommendations based on available evidence, but the final decision always belongs to the user.

<img src="Career%20Journey%20to%20Success.png" width="600" alt="Career Integrator - Career Path">


## Potential Data sources and AI methods

Main challenge: Finding reliable data about different career paths, including people who are still looking for work.

| Source      | Description |
| ----------- | ----------- |
| User information      |  Education, work experience, skills, languages and career goals|
| Psychological portrait | Online based free tests like Holland's RIASEC Model |
| Job market data | Vacancies, job requirements and market trends from Arbetsförmedlingen and Statistics Sweden (SCB) |
| State support programs | open support programs that illustrate labor market demand (such as Vuxenutbildning) |
| Career histories | Real career paths from LinkedIn and other sources, where access is permitted |
| Professional profiles | Skills and qualifications of people already working in similar positions. LinkedIn |
| User feedback (future) | Job search experiences, career changes and employment results |

AI methods that could be used

- **NLP / LLM:** Analyse career stories and identify skills, experience and career steps.
- **Semantic similarity:** Find matching and transferable skills across different jobs and industries.
- **Nearest neighbours:** Find people with similar education, experience, language skills and backgrounds.
- **Statistical analysis:** Identify common career paths and employment outcomes.
- **Skill-gap analysis:** Compare user skills with job requirements and suggest areas for improvement.
- **Career recommendations:** Suggest career options based on job opportunities, required skills, learning time and costs.
- **Explainable AI:** Show why each career path is recommended.
  
## Challenges

The main challenge is limited data - finding reliable career histories, including people who are still looking for work. Online profiles often show only successful careers and don't include periods of unemployment. And there are some more:

- **Privacy:** Personal information must be protected and follow GDPR rules.
- **Uncertain results:** Past career stories cannot guarantee future success.
- **AI accuracy:** The system must test which skills and qualifications really matter for different jobs.
- **Fairness:** AI should avoid discrimination based on age, gender or background.
- **Time and costs:** Training prices and learning time may vary.
- **AI limitations:** The tool cannot guarantee employment or replace a career advisor.

## What next?

1. **Prototype:** Build a simple Python/kNN model using synthetic career histories to compare similar profiles, career outcomes and skill gaps.
2. **Real-world validation:** Find legally accessible Swedish labour-market and career-path data; test accuracy, fairness and usefulness with users and career advisers.
3. **Personal career companion:** Add progress tracking, updated job-market insights, and suggestions for learning and career-plan adjustments.
4. **Scale up:** Explore cooperation with Arbetsförmedlingen and adult education providers, then expand to other user groups.

Further work requires data access, Python/ML and evaluation skills, and privacy-aware product design.

## Acknowledgments
Sources and projects that contributed to the development of this topic.

1. A personal project focused on career guidance for teenagers.
2. A professional career guidance platform: [Magellano](https://magellano.giuntipsy.com/uk/).
3. A US government career development resource: [O*NET OnLine](https://www.onetonline.org/).
