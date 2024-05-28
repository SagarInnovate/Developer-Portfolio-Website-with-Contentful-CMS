# Developer Portfolio Website with Contentful CMS

A modern portfolio website designed for developers, featuring a beautiful and animated UI/UX. This project uses HTML, CSS, and JavaScript for the frontend and Contentful as a headless CMS for managing project information.

## Introduction

This portfolio project is ideal for software developers to showcase their work. The project information is stored in Contentful and fetched dynamically using JavaScript. The website features a sleek design with animations and a user-friendly interface.

## Features

- Modern and responsive design
- Animated UI/UX
- Dynamic content fetching from Contentful
- Easy to customize and extend

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Contentful (Headless CMS)

## Installation Requirements

To set up and run this project, you need the following:

- A web browser
- Contentful account
- Contentful API keys

## Installation Steps

1. **Clone the repository**
   ```sh
   git clone https://github.com/SagarInnovate/Developer-Portfolio-Website-with-Contentful-CMS.git
   
   cd Developer-Portfolio-Website-with-Contentful-CMS
   
2. **Set up Contentful**

- Go to [Contentful](https://www.contentful.com/) and sign up for an account.
- Create a new space.
- Define the content model for your projects according to your requirements and data you want to show in your website (e.g., Project Name, Description, Image, Link).

3. **Configure Contentful API keys**

- Go to your Contentful space settings and obtain the Space ID and Content Delivery API - access token.

Inside of  index.html, contact/index.html, project/project.html, project/index.html files. add your Contentful configuration at the bottom inside in script tag:
    
```bash
const spaceId = '';
const accessToken = '';
```

- do any changes in javascript if you want

4. **Run the website**

- Open index.html in your web browser to see the portfolio website.


## Usage Instructions

- **Adding new projects:**
    - Log in to your Contentful account.
    - Go to your space and add new entries for your projects.
    - The frontend will automatically fetch and display the new projects.
    

## Screenshots
Add screenshots here showing different parts of your application.

## Demo Video
Watch a full demo of the Portfolio Website on YouTube.

## Contribution Guidelines
We welcome contributions from the community. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a new Pull Request.

## Conclusion
This Developer Portfolio Website provides a modern and elegant way to showcase your projects. By leveraging Contentful as a headless CMS, you can easily manage and update your content without touching the codebase.

## Contact
For any questions or suggestions, please feel free to reach out:

- Email: sagarinnovate@gmail.com
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/sagarinnovate/)
- GitHub:  [GitHub Profile](https://github.com/sagarinnovate)
- Website: [Visit Now ](https://sagarinnovate.growmediax.com/)
- Live Preview : [ Click Here ](https://sagarinnovate.onrender.com/)
- 
Thank you for checking out the Developer Portfolio Website! We hope it helps you create a stunning portfolio to showcase your work.
