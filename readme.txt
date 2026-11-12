--Readme document for *Daniel Ho Kim*, *danihk15@uci.edu*--
Partner: Hyeonbeen Han, hyeonbeh@uci.edu
1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Communicating with the webserver
- 1/1 Populating information about the user
- 3/3 Populating the search component
- 3/3 Artist page
- 1.5/1.5 Album page
- 0.5/0.5 Track page


2. How long, in hours, did it take you to complete this assignment?
we worked on this project for 6 hours. This is pure working time.


3. What online resources did you consult when completing this assignment? (list specific URLs)
Git Documentation(https://git-scm.com/docs/git-reset): Because I was writing the wrong part, I had to reset and undo my commit in Github. I referred to this website.
Canvas (Slides in Files): I referred to the code that Professor showed us in class.
ChatGPT(https://chatgpt.com/): While doing part 4 and 5, this was required "<!--TODO: use @for to loop over album artists-->" so I asked ChatGPT to get understand how that code work. I also used ChatGPT to help troubleshoot GitHub branch issue.

4. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
I did this project with Hyeonbeen Han, who is also in IN4MATX 133. 
While working on the project, we kept on communicating in person. 

Hyeonbeen Han
My primary responsibilities included implementing the Spotify API service, the About component, the Search component, the Carousel, the Carousel Card, and the Track List.
Daniel primarily implemented the Artist Page, Popularity Thermometer, Album Page, and Track Page.
We collaborated on integrating the components, resolving GitHub branch and backend setup issues, and preparing the final submission.




5. Did you add a bonus feature to your submission? If so, what is it and how should we see it?
No, I don't have Spotify subscribtion.


6. Is there anything special we need to know in order to run your code?
The frontend and backend need to run separately. 
For local testing, we used the dummy Spotify webserver provided with the assignment.

Start the dummy backend:

cd dummy_webserver
npm install
npm start

Start the Angular frontend in another terminal:

cd client
npm install
npx ng serve
