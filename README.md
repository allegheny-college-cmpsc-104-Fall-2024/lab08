
# Lab 08 - JAMstack - Gatsby

## Timeline
<table>
  <thead>
      <td style="text-align:left;">Assigned</td>
      <td style="text-align:left;">Monday 4 November 2024</td>
  </thead>
  <tfoot>
      <td style="text-align:left; color: red;">Deadline</td>
      <td style="text-align:left;">Friday 15 November 2024</td>
  </tfoot>
</table>

![Lab 8 Assignment](https://github.com/allegheny-college-cmpsc-104-Fall-2024/lab08/blob/main/graphics/gatsby.png)

## Project Goals
- Learn the basics of JAMstack architecture using Gatsby.
- Gain hands-on experience with Gatsby, a static site generator.
- Understand how to create and manage a blog using Markdown.
- Learn to deploy a Gatsby site on Netlify.

## Tools
- A computer
- Internet connection
- A GitHub account

## Learning Outcomes
These assignment learning outcomes contribute to the following course learning outcomes described in the course syllabus:

1. Describe and explain processes such as software installation or design for a variety of technical and non-technical audiences ranging from inexperienced to expert.
2. Use professional-grade integrated development environments (IDEs), command-line tools, and version control systems to compose, edit, and deploy well-structured, web-ready documents and industry-standard documentation tools.
3. Build automated publishing pipelines to format, check, and ensure both the uniformity and quality of digital documents.
4. Identify and apply appropriate conventions of a variety of technical communities, tools, and computer languages to produce industry-consistent diagrams, summaries, and descriptions of technical topics or processes.

## Instructions

### Part 1: Create a New Gatsby Site "gatsby-blog"
1. Create a new site:
    -  Create a new site with the name "gatsby-blog".
    - Please try to create your own style blog. However, if you'd like to start with a classic template, you can try:
    `gatsby new gatsby-blog https://github.com/gatsbyjs/gatsby-starter-blog`

### Part 2: Customiz the Gatsby Site.
- Create Blog Posts:
    - Create at least **three** blog posts using Markdown. 
    - Feel free to select your topics as long as they match your needs.
    - Please include your `.md` files under the `gatsby-blog/content/blog` directory.

### Part 3: Deploy the Blog Using Netlify. 
- Deploy Your Site:
    - Deploy the blog using Netlify.
    - Delete the `TODO` marker here, and replace it with the URL of the site you created in Netlify.

### _Notes_: 
- Naming: Make sure the site you created is named exactly "gatsby-blog".
- Content: Include at least three blog posts written in Markdown.

## Resources
- Gatsby Documentation: https://www.gatsbyjs.com/docs/
- Markdown Guide: https://www.markdownguide.org/
- Netlify Documentation: https://docs.netlify.com/

## Deliverables
Please submit your work by pushing it to your GitHub Classroom repository.
- You will modify the README.md file to include the URL of your deployed site on Netlify.
- Ensure your Gatsby site is fully functional and deployed on Netlify with the required customizations and blog posts.

## Project Assessment
- **Completion of Part 1 (30%)**: Successfully setting up the Gatsby site with the correct structure and creating the required blog posts will contribute 30% towards the assessment.
- **Customization and Deployment (30%)**: Proper customization of the Gatsby site and successful deployment to Netlify, including the correct site naming and configuration, will contribute 30%.
- **Content Quality (30%)**: The quality of the blog posts in terms of content relevance, grammar, style, and adherence to Markdown formatting will contribute 30%.
- **Achieve GatorGrader Compliance (10%)**: Successfully meets the criteria set by GatorGrader.

## Gator Grade
### GatorGrade Checks for Immediate Feedback

To provide immediate feedback on your submissions, we're utilizing GatorGrade. Upon submission, if there's a thick red X, it indicates missing components. This X will turn into a green check mark once your submission is complete. For details on what's missing, click on the red X.

To meet the lab assignment's baseline writing and commit requirements, you can use the department's `GatorGrade` tool. Ensure Python3 is installed on your computer (check with `python --version`). If Python is not installed, please follow these guides:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [Setting Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Installing `GatorGrade`:

- [Install](https://pipx.pypa.io/stable/) [pipx](https://pipx.pypa.io/stable/) if you haven't already (`pip install pipx`).
- Install `GatorGrade` using pipx (`pipx install gatorgrade`).
- Running `GatorGrade`:
 `gatorgrade --config config/gatorgrade.yml`

Good luck!
