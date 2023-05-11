# Final Project

## Documentation

### Project Name : Artist Informational Portfolio

#### Objective

My goal for this project was to build an informational artist portfolio website primarily using code. I used HTML, CSS, and Javascript for this project, and I feel like I've done quite adequate work. It was a bit difficult for me to make the whole project interactive, as the site mainly consisted of images and audio files. I wanted to implement video files, since I recently created some music visualizer clips that synced to the beat of the music. Overall, I would say that the project placed the most emphasis on visual design, as I wanted the project to look appealing to the viewer, when they click on the website, see it during the presentation, or decide to view it in my custom repository. The appearance of the whole site looked presentable and clean, which is a prominent feature of the website that I had originally anticipated would execute successfully. I modified an image source code of an existing site to help guide me through the process. It was amazing to see how the changes within the code took into effect as commits were pushed into the repository.

My website is [Reana Kirzten - Artistic Portfolio](https://reanakirzten.github.io/)

[Google Slides Presentation](https://docs.google.com/presentation/d/1VI9iKKGiON5JrqS4Ac8mfW5qqDQsdBs9bmc0g4fDKB8/edit?usp=sharing)

#### Process

* I first utilized the resource provided in the SP2023 repository [HTML5+CSS3 Demo Websites](https://html5up.net/) in order to take the image source code and paste it into my repository titled "reanakirzten/reanakirzten.github.io"

* I changed the title of each page within main the drop-down menu, that you locate within the site on the upper right corner of the screen. The first three pages were initially set to "Generic", "Contact", and "Elements" based on the template I utilized, so I changed the drop down menu title to "About", and changed the names of the three pages to "Bio", "Background", and "Portfolio".

* In the main home page, within the first box, I ensured that I changed the title enclosed in "h2" and "/h2" brackets to "About" and wrote a short description below it, enclosed in "p" "/p".

* For the container below the About summary, I made sure to change the titles in each box to the forms of expertise I have/services I can provide, such as "Productions", "Compositions", "Videography", and "Photography", while also changing the short descriptions below each title as well.

* I then changed some of the properties of the code such as the titles, headers, and subheaders (h2, h3) within both the main HTML file and the CSS files to modify the features of the code.
    * I used the font family, "Gill Sans, sans-serif" to set the intial text to the new font.
    * I switched up the rgb properties within the CSS file to change the colors of the background pages and the fonts within the website.
    * I set the img-src banner to images/purpleneon.jpeg to ensure that the image displayed on the top of the home page was present and didn't alter the file size, since I wanted to make it big on the page, as the presence of the pattern and bold colors would look appealing to the viewers.

* For the two audio files in the Portfolio and Services Page, I added a line of code starting with "audio src" to host the existing mp3 files within an audio folder in my repository.

* The images I used for the rest of the pages were located within the "images" folder in the custom-made repository, and I used them using "img src" with a general code template of "images/(file name)" to implement the images successfully into the website. Before hosting the images, I would usually resize some of the pictures to make sure they didn't look too small or large on the pages.

* I also made sure to implement the Javascript files when I downloaded the site template's Zip file and made sure to add them to my repository, in order to provide the website with a more modern, contemporary appearance and decorative elements.

#### Problems and Debugging

* **Implementing Videos, Audio File not in Public Published Site** : For my website, I wanted to add some videos using the "video", "/video" and host them from a created video files folder using "source src". However, I was having a hard time implementing videos, since I tried adding two video files that I have created videos for, titled "BroadenThisLegacy.mp4" and "Antigravitation.mp4". The reason for this is that a message called "File size exceeds 100 MB" would pop up every time I would try to add them. I went to remove one of the videos from the code, but the same message would appear. Since these weren't working, I decided that the media would be solely emphasized on the audio files.

* **Interactivity** : I wanted to make the site more interactive, but I had a difficult time figuring out how to do so, since the videos wouldn't appear due to large file sizes.

* **"Start Sound" and "Play Sound Until Done"** : I had a difficult time distinguishing the differences between these two blocks at first. I realized that I accidentally implemented a "Play Sound Until Done" Electric Piano note block on my "Keyboard" sprite, when I actually wanted a note to cut off earlier to some leave room for the next note come in and keep a relatively consistent tempo with the electric piano tune. (Sematic Error) I then figured out that "Start Sound" was the correct block that played a certain key at no definite duration, thus providing me with the opportunity to adjust the duration of the note with a "wait (value) seconds" block attached to it.

* **Searching for Different Sound Presets for a Sprite** : Towards the end of my project process, I wanted my Laptop sprite to play sounds other than the default "pop" sound that appeared in the sound block's drop-down menu. I wanted it to play the sound block threads from the "Keyboard" and "Keyboard Drumpads" sprites when I duplicated them into the Laptop sprite, but I wasn't hearing any sound from the Laptop when I first performed a test run on it. I have come to the conclusion that it was because the sound presets under the "Sounds" tab in the top left corner of the Scratch project page only showed the "pop" sound. However, I saw that there was an option to add more sounds and default presets from other sprites by clicking on the speaker with the plus sign button at the bottom left corner of the page, and it directed me to a library with several sounds. I was able to find the Electric Piano and Drum after typing the sound names in the search bar. Once I imported them, I was finally able to hear audio from the Laptop sprite.



_I have not used code from others/elsewhere_