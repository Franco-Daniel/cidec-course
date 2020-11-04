# CIDEC Course

> ## This is a simple github repo in order to practice the basics of git and github.

## STEPS

1. Clone the repo.  
   `$ git clone https://github.com/Franco-Daniel/cidec-course.git`

2. Create branch.  
   `$ git branch [MY_NAME]`

3. Copy and paste the card element within the index.html page and replace the replace holders.

   ```html
   <!-- COPY FROM HERE -->
   <div class="col-md-4">
     <div class="card">
       <img class="card-img-top" />
       <div class="card-body">
         <h5 class="card-title">[YOUR NAME]</h5>
         <p class="card-text">[SOMETHING ABOUT YOU]</p>
         <a href="[LINK TO SOMETHING AWESOME]" class="btn btn-outline-info" target="_blank">Check this out!</a>
       </div>
     </div>
   </div>
   <!-- COPY UNTIL HERE -->
   ```

4. Test your changes on your local env.

   > Just open the index.html in a web browser.

5. Commit the changes to the remote repo.  
   `$ git add [YOUR FILE | FILES]`  
   `$ git commit -m "[YOUR MESSAGE]"`  
   `$ git push -u origin main`
