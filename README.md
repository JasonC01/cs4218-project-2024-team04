[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Lq2be5ao)
# Instructions on creating team repository using GitHub Classroom
## Step 1. Ensure that your team formation through Canvas has been confirmed.
Do not proceed to step 2 otherwise!

## Step 2. Visit the assignment link at https://classroom.github.com/a/Lq2be5ao
The first member of the team to access this link will be prompted to accept the assignment that gives your team access to the new repository.
Create a new team by typing 2024-TeamXX , where XX is the Team number as noted in Step 1 above. 
(Note that the naming convention must be followed strictly, e.g. capitalisation, dash, and spacing. 
If your group number is a single digit, i.e 2024-Team1 is fine as well.)

The other members in the team will be able to see an existing team with your team number in the “Join an existing team” section. Click Join.

## Step 3. All of you should be able to see the acceptance page. Click on the assignment link to see the project on GitHub.

# Milestone Submission Instructions
In the repository of your team, tag the submitted commit with a tag name “ms1” (meaning milestone 1). 
1. Create a tag, e.g., git tag -a ms1 -m “Milestone 1”
2. Push the created tag into the repository, e.g., git push origin ms1
3. More details are in: http://git-scm.com/book/en/v2/Git-Basics-Tagging



# Milestone 2 - How to run tests
1. Download our env files from [here]([url](https://drive.google.com/drive/folders/1X1ibo3JVlgANbw4X6V6zR-BPW2oAaF6p?usp=drive_link))
2. Move the 3 env files to the project root
3. Run 'npm install'
   
## Running UI tests
1. Ensure current directory is at project root
3. Run 'npm run ui-test' to initialize tests
4. Run 'npx playwright test --config=playwright.config.cjs'

## Running integration tests
1. Run 'npm run test'
   
# Milestone 2 Contributions
## Integration Tests 
### Kelvin Seow (A0234975R)
- <root>/integration-tests/authIntegration.test.js
  
## UI Tests
