<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Career integrator AI

Final project for the Building AI course

## Summary

Career Integrator is an AI-based career planning assistant for international professionals entering Sweden's labour market. It analyzes professional profiles and comparable career journeys to suggest realistic next steps, alternative career paths, and skills to develop.

## Background

Experienced professionals relocating to a new country often struggle to translate their skills and qualifications into local job opportunities. Language barriers, unfamiliar hiring practices, and limited professional networks add further challenges.

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

1. **Create a profile:** The user shares their education, work experience, skills, interests, language level and career goals.
2. **Explore the job market:** AI analyses job vacancies, required skills and profiles of people already working in similar roles.
3. **Find similar career stories:** AI identifies how people with similar backgrounds found jobs and developed their careers in Sweden.
4. **Compare outcomes:** The system shows common career paths and employment results, including how long finding a job took, when reliable data are available.
5. **Identify skill gaps:** AI highlights missing skills, language requirements and qualifications that may improve job opportunities.
6. **Suggest career options:** The system recommends different career paths and compares their potential benefits, time and learning costs.
7. **Choose a path:** The user selects a preferred option and receives a personalised career plan.

The AI provides recommendations based on available evidence, but the final decision always belongs to the user.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
