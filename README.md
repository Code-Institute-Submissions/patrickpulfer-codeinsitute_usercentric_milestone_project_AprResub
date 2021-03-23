Website for PaddyOS - Submission to my first project at [Code Insitute](https://codeinstitute.net)

---

<br><br>
<img src="https://img.shields.io/github/last-commit/patrickpulfer/codeinsitute_usercentric_milestone_project?style=for-the-badge">
<img src="https://img.shields.io/github/repo-size/patrickpulfer/codeinsitute_usercentric_milestone_project?style=for-the-badge">
<img src="https://img.shields.io/github/languages/count/patrickpulfer/codeinsitute_usercentric_milestone_project?style=for-the-badge">

<a href="">
    <img src="assets/images/logo_paddy.png" alt="PaddyOS logo" title="PaddyOS" align="right" height="45" />
</a>

Note: PaddyOS is a fictional computer operating system. The aim of this project is to promote this software to the end user.

# Official Website for PaddyOS

Official Website for PaddyOS

## What is PaddyOS?

PaddyOS is a robust and reliable operating system based on Linux for everyone, featuring:

- No-nonsense and easy to learn UI with everything right where you need it. We don't use "bloatware" or other nuisance.
- PaddyOS is free to install, as we beleive that everyone should have access to a reliable system without cost. The computer is yours, why should you pay extra or be tracked by adds?

## UX

In this section, I will explain the adoption of the Five Planes of UX design.

### Strategy and Initial Stage of my Project

A medium was sought to promote a new operating system created by a pioneering group of Irish developers. This medium must be available 24/7 to potential customers around the globe.

I have concluded that the easiest way to share software is via the Internet. Therefore I have researched several websites of other popular operating systems, including:

- Windows 10 (https://www.microsoft.com/en-ie/windows/get-windows-10)
- Ubuntu (https://ubuntu.com/)
- Manjaro (https://manjaro.org/)
- Linux Mint (https://linuxmint.com/)

### Scope of this Project

- The simplest form of promoting PaddyOS on the web is a static website which requires HTML + CSS as core technologies
- Website must be available 24/7, so decision has been made to deploy to Github and Gitpages (see Deployment section for more details)
- Three sections are required, so I have chosen the following:
  - Introduction (showcasing the "What is" and "Why")
  - Download (access to download PaddyOS)
  - Contact Form (ability to contact us or send feedback)

### Structure

As visitors to website may or not be proficient in computer driving, decision was made to organize the website as a single site where user can scroll trough sections.

I have decided to include the Main Menu for users to quickly navigate trough the website.

### Skeleton

To be adhere to the structure outlined above, the overall website should be divided into three sections as shown below:

<img src="documentation/wireframes/wireframe1.png">

To avoid a lenghty readme file, please visit [Wireframing Project PaddyOS Website](documentation/wireframes.md) for further study into the skeleton of the website.

### Surface Design

To emphasize the origin of the project, decision was made to include a color scheme based on the green color as below:

- Main Color: <span style="color:#F3F0F1;background-color:#5C7D61;">#5C7D61</span>
- Main ("white") background/font: <span style="color:#5C7D61;background-color:#F3F0F1;">#F3F0F1</span>
- Dark Shades: <span style="color:#F3F0F1;background-color:#122D23;">#122D23</span>
- Slightly lighter accent from main color: <span style="color:#F3F0F1;background-color:#8DB49E;">#8DB49E</span>
- Slightly darker accent from main color: <span style="color:#F3F0F1;background-color:#7B9E8C;">#7B9E8C</span>

Note that fonts and main "white" background is not exacly white but an easier to the eyes color #F3F0F1.

Logo: Every product/brand should have a logo, so I have created a simple logo based on color #27cc9d which would showcase a balanced shape and chaos in form of lines:
<br> <img src="./img/logo_paddy.png" alt="PaddyOS logo" title="PaddyOS" height="60" />

## Features

- Introduction Screen
  - First section presented to a user with the minimalistic approach and buttons to the most important sections.
- "What is" / Features page
  - Section for the end user to get an "at glance" overview of the software and its capabilities.
- Download
  - Download section allows the user download the software for installation.
- Contact Us form

  - Easy to use medium to contact developers for any queries or feedback.

- Website is mobile-friendly and optimized for right handed use (menu is on the right side)
- Website is compatible with Dark Mode (you can test with https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)
- Website is also optimized for faster loading thanks to the Lazy Loading API (https://web.dev/browser-level-image-lazy-loading/)

### Ideas / Future Features

- Forum: An online place where users can interact with developers or other users
- FAQ: Most commonly asked questions & answers in a searchable format
- Newsletter or RSS

## Technologies used

### Tools Utilized during development of the website:

- A desktop PC with Linux [Pop!\_OS](https://pop.system76.com/) operating system installed
- [Visual Studio Code](https://code.visualstudio.com/) for manipulating .html .css and .md files
- [GIMP](https://www.gimp.org/) or GNU Image Manipulation Program to manipulate images utilized in this project (example paste picture inside Laptop screen)
- [WireframeSketcher](https://wireframesketcher.com/) to sketch visual aspect of website prior to development
- [Github](https://github.com/) for version control, backup & deployment to Gitpages
- The following browsers for compatibility & testing purposes (see Testing section for further details):
  - [Chromium](https://www.chromium.org/)
  - [Firefox](https://www.mozilla.org/en-US/firefox/new/)
  - [Microsoft Edge](https://www.microsoftedgeinsider.com/en-us/)
  - [Mobile Google Chrome](https://play.google.com/store/apps/details?id=com.android.chrome)

### Technologies/Tools incorporated into the website:

- [HTML5](https://www.w3.org/)
  - Project based **HTML5** for compatibility reasons, as all major browsers support it
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
  - Cascading Style Sheets or **(CSS)** standard is also supported by all major browsers for styling the website
- [Bootstrap](https://getbootstrap.com/)
  - Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development
- [JQuery](https://jquery.com)
  - The project uses **JQuery** to simplify DOM manipulation.
- [Font Awesome](https://fontawesome.com/)
  - Icons utilized in this project are fetched from **Font Awesome**

## Testing

As a developer, I understand that user feedback is very important, especially during testing phase.

Therefore I have tested the website myself but also asked two different end users to test the website.

Tools used:

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
- Browsers:
  - [Chromium](https://www.chromium.org/)
  - [Firefox](https://www.mozilla.org/en-US/firefox/new/)
  - [Microsoft Edge](https://www.microsoftedgeinsider.com/en-us/)
  - [Mobile Google Chrome](https://play.google.com/store/apps/details?id=com.android.chrome)

### Test 1 - Browser Compability

1. Load the [Website hosted at GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html) on all browsers mentioned above and look for inconsistencies

_Passing Criteria_: Website renders correctly on any popular browser

### Test 2 - Device Compatibility

1. Load the [Website hosted at GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html) on Chrome's DevTools, click the "Toogle Device toolbar" button and select different devices sizes to observe the breakpoints. Website should be legible on any size used.
2. Load the [Website hosted at GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html) on Google Chrome at a Mobile Device and observe if text is legible and pictures do load

_Passing Criteria_: Website renders correctly on mobile / laptop

### Test 3 - Errors at parsing HTML level

1. Load the [Website hosted at GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html) on Chrome's DevTools, click on "Console" and verify if any error messages do appear

_Passing Criteria_: Website does not produce any error message

### Test 4 - Errors at anchoring level

1. Load the [Website hosted at GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html) on any browser
2. Click on any link found in the website, particulary
   - Navigation Bar
   - Starter Section
   - Download Section (You may ignore the button "Download" at the bottom of the page of not doing anything)

_Passing Criteria_: All links work as expected except the last "Download" button (not yet implemented)

### Test 5 - Errors at form level

1. Load the [Website hosted at GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html) on any browser
2. Scroll until you find the button to register yourself "Developer Edition"
3. Submit the form while empty and observe validation
4. Repeat step 3 but add a field each time
5. Close the modal and perform same test on Contact Us form

_Passing Criteria_: AForm validation should prevent you to submit if one of the fields are missing

### Report

- Two end users + myself reported no issues during testing

## Deployment

### Current Deployment

The website is currently available at:

- [GitPages](https://patrickpulfer.github.io/codeinsitute_usercentric_milestone_project/index.html)
- [GitHack](https://raw.githack.com/patrickpulfer/codeinsitute_usercentric_milestone_project/main/index.html)

I have used the following method to deploy this website at GitPages but may also use this workflow to deploy any websites at GitPages:

1. Navigate to your GitHub Project
2. On the top of your project files, there is a menu bar. Click on "Settings"
3. In your settings view, scroll down until the section "GitHub Pages"
4. Here you can chose the Source (preferentially main branch) and Save to deploy
5. Note the URL at "Your site is published at XXXXXX". This will be the URL to share

### Further Deployment

You may deploy this website on your local machine for testing purposes.

On **_Linux_**, you can easilly do this on your terminal if you have git installed:

```
cd <to your prefered folder>
git clone https://github.com/patrickpulfer/codeinsitute_usercentric_milestone_project.git

```

To run, simply double click the index.html file in the target folder or run the following command:

```
xdg-open ./codeinsitute_usercentric_milestone_project/index.html
```

Downloading the source code as Zip file from GitHub is also a valid method for **_Linux_** and **_Windows_**. On the project page, look for the Code button with arrow down as shown below:

<img src="./img/github_zip.png">

Note: You will have the extract the contents of your .zip file with your OS's decompression tool. [7zip](https://www.7-zip.org/download.html) is a good alternative.

Once unzipped, look for the index.html file and double click it.

## Credits

### Content

- The text under "Based on Linux" in the "What is PaddyOS" section is copied from [What is Linux article](https://www.linux.com/what-is-linux/). Citation on the paragraph has been marked with link to the same source.

### Media

- The background picture of the first section was fetched from https://unsplash.com/photos/9q3I8XhesQI
- The Macbook picture was sourced from https://www.hiclipart.com/free-transparent-background-png-clipart-msazr and manipulated with GIMP to copy/paste a screenshot of my desktop
- Pictures in Features section are screenshots taken from my own desktop

### Acknowledgements

- I'm a big fan of Linux and open source collaboration. My inspiration came from the great work on desktop Linux by project like Ubuntu (https://ubuntu.com/), Manjaro (https://manjaro.org/) and Debian (https://linuxmint.com/)
