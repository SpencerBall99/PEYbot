# PEYbot
*A project for NewHacks2020 built by:*
**Spencer Ball, Atom Arce, and Shyam Menon**

## Inspiration
As busy 3rd year engineering students in the midst of the PEY application process we were searching for an efficient method of applying to PEY jobs. With hundreds of jobs on the portal at any given time, many application opportunities are missed each day when the portal is updated. Hence, we came up with the idea of automating this application process with a bot which we have creatively named PEYbot.

## What it does
PEYbot logs into UofTs ECC portal and applies to all jobs that fit the search filters specified by the user. To ensure these applications are effective, a custom cover letter is generated and uploaded for each position and a unique application package is created. Applications which require navigation to external websites are ignored by PEYbot but their respective IDs are kept in a list which allows the user to apply to these missed opportunities manually.

## How we built it
We relied heavily on the browser automation package Selenium which gave us the tools we needed to navigate the website via a Python script. Additionally, we used the package _ questionary _ which allowed us to provide nicely formatted prompts to the user. We also took advantage of the document editing packages docx and docx2pdf in order to create and upload custom pdfs.

## Challenges we ran into
None of us had ever worked with html or browser automation before so it was a steep learning curve at first. Once we had gotten the hang of Selenium we still ran into challenges when figuring out ways to extract and utilize pieces of the website. Figuring out how to extract the Job IDs and how to select the correct cover letter were specifically challenging tasks.

## Accomplishments that we're proud of
We are proud of creating a fully functioning project within 24 hours of learning the skills necessary to build it.

## What we learned
We learned much about browser automation and data scraping through working on this project.

## What's next for PEYbot
We would like to implement more search filtering options, a better user interface (potentially a website), and a more robust cover letter editing method which customizes the letters to a higher degree. With these upgrades, PEYbot would be an extremely useful tool for many students in similar situations as us.
