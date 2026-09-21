1. pushes and pulls to the branch of main is what triggers the workflow to run.
2. Checkout code, validate HTML, check links, and upload artifacts.
3. The checkout code step gets the codes from the repository. It is necessary so that the workflow can see what we wrote in the repository and see if it works.
4. The purpose of the environement configuration is what makes the area where the code is to be seen.
5. Automated deployment improves reliability because then we only have to do one step compared to multiple in order to make sure that the code is put to where it needs to be for the people to see it.
6. If we push code to a different branch then it would not be saved in the main branch. If we then delete the branch it came from then we will no longer be able to put what we had into the main branch where we wanted it to go.