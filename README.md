# DUAW

## About
\
Welcome to DUAW! DUAW stands for visit, get together and communicate in Bisaya language and is also an abbreviation for the different tracks offered by TechLabs: 
* **D**ata Science
* **U**X Design
* **A**rtificial Intelligence, and 
* **W**eb Development! 

When we started our graduation project, we knew that there was already a space for graduation projects to get documented (Github) and a final presentation of graduation projects per semester uploaded on Youtube. But that wasn't really effective since projects were not well presented visually, and it was really hard for the outside world to discover them. 

By interviewing members of the TechLabs Berlin leadership team, we found that indeed the graduation projects "fizzle out" after the final submission and similarly students that created them lose contact with each other. This defined our mission: Create a platform where graduation projects can be showcased in a well structured and visualized manner, so students can proudly present the skills they gained and others can learn about them easier.

At the same time, we targeted DUAW also around strengthening the TechLabs community, by allowing project members to provide their contact details (e.g. their Linkedin), alumni and third parties to upvote projects and contact project teams for suggestions, feedback or collaboration requests. Additionally, potential future TechLabs students and partners could easier view graduation projects and get to see the great work that TechLabs does.

On the technical side, DUAW can be understood as a wrapper for GitHub repos. Project teams have to add a few files into the Github repository - as explained on the DUAW (How it works page) - and afterwards notify the DUAW team to upload their project. The data is then fetched via the GitHub API and transformed into a new DUAW page for their project.

## UX links

## Running the project on localhost

After clonning the repository, and having the complete project files saved in a folder on your computer, open the project folder with your desired editor.

To run the frontend part of the project:


To run the backend part of the project:
- To install all the backend dependencies: `npm install`
- run `npm`

To update the recommendations for display on the website:
- The following python packages are needed: `XXXXX`
- execute `recomender-system.ipynb` (in `Jupyter Notebook`)
- update the content of the `recomendations.json` file:  https://github.com/TechLabs-Berlin/wt21-duaw/blob/main/recomendations.json
- the last step will require a pull request and merging by a member of the DUAW team

## Team members

- UX | David Dillmann
- UX | Celine Onwubiko
- UX | Constantine Dranganas
- WD | Javad Raisi
- DS | Constanze Cavalier

## Mentor
- Bernardo Sunderhus

## Duaw founder
- Constantine Dranganas

## Tech Stack
- Git & GitHub
- Rest API
- Node.js and Express
- Python3
- Python libraries: pandas, numpy, matplotlib, 
- Jupyter Notebook
