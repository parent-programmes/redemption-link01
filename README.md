Grow Well SG – Token of Appreciation Page: Update Guide     ||
=============================================================

Prerequisite 101: How to Upload Images to GitHub

      All images used on this page must be uploaded to the GitHub repository before you can use them. Follow these steps every time you need to add a new image:
      
      Go to your GitHub repository in the browser
      Navigate to the same folder where your HTML file is saved
      Click "Add file" → "Upload files"
      Drag and drop your image file onto the upload area, or click "choose your files" to select it from your computer
      Make sure the filename is simple with no spaces, for example book-cover.png or got10minutes-logo.png
      Scroll down and click the green "Commit changes" button
      Your image is now in the repository and ready to be used
      Your folder structure should look like this after uploading:
      
      text
      
      your-repo/
      ├── index.html
      ├── got10minutes-logo.png
      ├── book-cover.png
      └── any-other-images.png

===================================================================================================================================================================================

Step 1: Changing the Book Cover Image
      Prepare your new book cover image file (JPG, PNG or WebP recommended)
      Upload it to the GitHub repository following Prerequisite 101, for example name it book-cover.png
      In the HTML file, find the <img class="book-cover" tag:
      html
      
      <img
        class="book-cover"
        alt="No screen use during meal times and before bed e-book cover"
        src="book-cover.png"
      >
      Replace the src value with your new image filename
      Update the alt text to briefly describe the new image




==============================================================================================================================================================================
Step 2: Changing the Book Description Text

      In the HTML file, find the following section:
      html
      
      <h2>
        A short story to read together
      </h2>
      
      <p class="story-copy">
        Here's a short story you can read with your child
        to start a conversation about healthier screen habits
        during mealtimes and before bed.
      </p>
      Replace the text inside <h2> to change the heading
      Replace the text inside <p class="story-copy"> to change the description paragraph
      Do not remove the <h2>, </h2>, <p class="story-copy"> or </p> tags, only change the text between them

  
=======================================================================================================================================================================

Step 3: Changing the Download Link for the E-Book

      The download button and the book cover image are both linked to the e-book URL. You must update both.
      
      In the HTML file, find the book cover link:
      html
      
      <a
        class="book-link"
        href="https://go.gov.sg/e-book"
      Replace https://go.gov.sg/e-book with your new URL
      
      Then find the download button link:
      
      html
      
      <a
        class="download-button"
        href="https://go.gov.sg/e-book"
      Replace https://go.gov.sg/e-book here as well with the same new URL

=================================================================================================================================================================================

Step 4: Changing the Parent Hub Link

      In the HTML file, find the following section:
      html
      
      <a
        href="https://go.gov.sg/grow-well-sg-main-page"
        target="_blank"
        rel="noopener noreferrer"
      >
        Parent Hub.
      </a>
      Replace https://go.gov.sg/grow-well-sg-main-page with the new URL
      Do not remove target="_blank" or rel="noopener noreferrer" as these are important for security and user experience

================================================================================================================================================================================

Step 5: Changing the Introductory Text
      In the HTML file, find the following paragraph:
      html
      
      <p class="discover-copy">
        Enjoy this e-book with your child and have more bonding moments together.
        For more 10-minutes activities ideas, please visit us at
        <a href="https://go.gov.sg/grow-well-sg-main-page">Parent Hub.</a>
      </p>
      Replace the text as needed
      Keep the <a href="...">Parent Hub.</a> part intact if you still want the Parent Hub link to appear
      Do not remove the <p class="discover-copy"> or </p> tags

=====================================================================================================================================================================================

Step 6: Changing the Got 10 Minutes Logo
      Upload your new logo to the GitHub repository following Prerequisite 101
      In the HTML file, find the following:
      html
      
      <img
        class="got10-logo"
        alt="Got 10 Minutes"
        src="got10minutes-logo.png"
      >
      Replace the src value with your new logo filename
      Update the alt text to describe the new logo if needed
