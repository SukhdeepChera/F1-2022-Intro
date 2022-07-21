# F1-2022-Season-Primer-Website
Final project for Coursera Web-Design-For-Everybody specialization

This is a full website built from scratch using all the things learned from previous courses in the specialization.
The website is not hosted online, so to view the website, download each of the 4 html files, and the folders, "css"
"js", and "images".

Alternatively, I have provided a folder, titled "website-images" with some images of the website if 
you would like to see a basic understanding of how the website looks and works.


  The website created serves as a primer for the 2022 Formula 1 season with 4 seperate pages. Some of the information
presented is not up to date as this website was created prior to the start of the season, before these things
changed. Some of these changes include:

    1. Nikita Mazepin is no longer racing in F1 and was replaced with Kevin Magnussen
    2. Some of the drivers pictures are not the standard pictures that they take with their teams because they
       had yet to officially join their teams.
    3. The images of each teams cars were early  versions of their 2022 cars and could have substantially changed
       over the course of the season
    4. Certian images used for the track/location were old or in progress images because the tracks were still 
       under construction


  Each of the pages have a common header area (the area in red) that has the title of the page as
well as a navigation menu to each of the other pages, and a button in the top right hand of the header
that toggles light mode. At the bottom of each page there is a footer section that has links to the F1
2022 season Wikipedia page as well as the F1 official website. The body of the pages also have built in
margin so that the content has a border around them.


Specific Details About Pages:

    1. First Page: "F1-2022-Season-Home.html"
             The main content of this page has one picture of an F1 car as well as 2 different text sections
          describing the sport and the upcoming season. This first picture shows the website in its largest screen
          size. As the screen size changes, the font sizes of the text on the right as well as the width dimension of
          the picture change a few times until the pages layout changes where the picture is displayed the full
          width of the screen and the text goes underneath the picture.

    2. Second Page: "Constructors.html"
             The main content of this second page is pictures of each of the teams’ cars on the left side as well as
          descriptions of each of the teams on the right. Just like the previous page, as the screen size changes,
          font sizes and image sizes changes through both percentage-based sizes but also media query breakpoints.
          When the screen size gets small enough, the layout changes so that the images take up the entire width
          of the page and the text then takes up the entire width below the image.
          
    3. Third Page: "Drivers.html"
             The third page is similar, showing pictures of each of the drivers with descriptions of each of the drivers. On this page, the image and the text 
          alternate sides for each of the drivers. Again as the screen size changes, font sizes and image sizes changes through both percentage-based sizes but also
          media query breakpoints. When the screen size gets small enough, the page layout changes so that the pictures take up the entire width. The text also takes
          the entire  width underneath the picture.  
             
    4. Fourth Page: "Grand-Prix.html"
              The last page is similar, showing pictures of each of the race track locations as well as the actual track the drivers will race with
           descriptions of each of the races. On this page, the images are on both sides of the text. Again, as the screen size changes, font sizes and image sizes
           changes through both percentagebased sizes but also media query breakpoints. There is also a google calendar at the bottom of the page. When the screen 
           size gets small enough, the images stack on top of the text just like the previous pages.
           
        
Other Features:
    
    
    1. Lightbox Plugin:
          The first enhancement I made to the website was to make add a lightbox plugin to the first page of the
       website. The lightbox plugin was the same as the one that the professor used in the video about lightbox
       plugins. I did make a couple adjustments to the code that change the length of the fade in duration as well as
       preventing scrolling down the page while the looking at the picture in the lightbox mode. (Honestly this was kind
       of pointless as it doesn't really make the picture easier to see but I did want to know how to use it)
       
    2. Calendar:
         The second enhancement was adding embedding the google calendar on the very last page at the
       bottom. I didn’t make any changes in the html, but I did adjust the width as well as the centering of the
       calendar.
       
    3. Light/Dark mode button:
         The third enhancement incorporates a button to the top right corner that toggles a light mode of the
       website. This works for all of the pages and has an opaqueness value of 0.5 until it is hovered over when
       it becomes solid colored. The button can toggle back and forth between dark and light mode.
       
    4. Simplified Team Names:
         The third enhancement is similar to the previous one that creates a button but only on the 2nd page, the
       page detailing the teams in F1. The button changes the h2 heading at the beginning of each section for
       each team and simplifies the team names to their simpler names instead of their full-length names.
       
    5. Nav Menu:
         The navigation menu as well as the footer links both change size as the screen size changes. The
       navigation menu in particular also shifts from 2 to a row to 4 to a row as the screen size increases.
    
       
    
