
 Barbosa The Barber - TESTING
 
![Multi_Display_Example](assets/images/readmeimages/readme_mutipledisplaysphoto.png)

The site was built to serve as a singular place where my brother, Guilherme, who is a barber, could promote his business. By consolidating all the information in one place, we hope to attract new customers.


Live Site : https://vitorbarbosadev.github.io/barbosathebarber/

---

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
  * [WAVE](#wave)

* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

* [BUGS](#bugs)
  * [Known Bugs](#known-bugs)
  * [Solved Bugs](#solved-bugs)

---

## AUTOMATED TESTING

The Automated Testing includes all the testing that is carried out by a program, like W3C HTML validation.

###  W3C Validator
W3C was used to validate all pages and also the css.

#### Results for Index.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/71a6e6f1-6940-47a0-84ea-7b3775e23cd4)
#### Results for About.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/bedabb85-560b-47d0-8df7-60c34f7ea6dd)
#### Results for Sevices.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/3746ebd9-0bb9-40cf-93ff-faa5d50b2fe6)
#### Results for Gallery.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/785b8371-52aa-47e7-9974-0c71b9d079c4)
#### Results for Contact.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/4aaef14f-9ad1-4e7d-822d-f3cdb2c49900)


#### **CSS Validation**

![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/71ad0561-8c46-4cd0-acd2-3642e8b88963)


### Lighthouse
Lighthouse was used to on all pages below are the results
#### Desktop Testing

#### Results for Index.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/409eb545-28ac-4801-939f-0340e321b7f6)
#### Results for About.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/e4279f4a-a93c-4008-af7e-81801ee4ccfb)
#### Results for Sevices.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/f6152ac7-f451-4678-b788-3666d64f5438)
#### Results for Gallery.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/d7470fbc-74c8-4131-9388-86b80ec1b660)
#### Results for Contact.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/3236ce22-14dc-4d12-9b20-81f637b0e295)

From my understanding the reason why this page is slow is because of the maps and time it takes to load.

#### Mobile Testing

#### Results for Index.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/fb50fd04-abbf-4b1a-8029-40ad57d0f6a9)
#### Results for About.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/3e16af80-abe8-449e-9997-95cabe18e3d9)
#### Results for Sevices.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/92744831-8d23-4948-af1c-2cb72e840717)
#### Results for Gallery.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/78362ffc-7271-445d-b4bc-856d6238ad77)
#### Results for Contact.html
![image](https://github.com/VitorBarbosaDev/barbosathebarber/assets/46977318/c12aa3d5-fcb0-441e-a3d8-475bd48598b5)


### WAVE
Wave was used to test the accessibility of each page 

#### Results for Index.html
- [Wave for Index](assets/images/testingimages/wave-index.png)

#### Results for About.html
- [Wave for About](assets/images/testingimages/wave-about.png)

#### Results for Services.html
- [Wave for Services](assets/images/testingimages/wave-services.png)

#### Results for Gallery.html
- [Wave for Gallery](assets/images/testingimages/wave-gallery.png)

#### Results for Contact.html
- [Wave for Contact](assets/images/testingimages/wave-contact.png)

The Contact page had a contrast error related to the styling on the button. 
You can view the error in this image: [Wave Contact Page Contrast Error](assets/images/testingimages/wave-contact-error.png).

Upon reviewing the results, I noticed that the contrast error occurred due to the white and gold color combination. Although it deviates from the recommended contrast standards, I personally find it visually appealing and believe it complements the overall style of the page. It's worth noting that all the other buttons feature a black background, white text, and a gold border.

Considering these factors, I have decided to maintain the current appearance of the button on the Contact page. However, I acknowledge the importance of being more attentive to color combinations in the future to ensure better accessibility and compliance with standards.

## MANUAL TESTING

### Testing User Stories


| Goals | How are they achieved? | Image |
| :--- | :--- | :--- |
| `First Time Visitors` |
|  |  |  |
| I want to find out who Barbosa the Barber is. | An "About" page is linked in the header. There is a section about Guilherme. | [About Section](assets/images/testingimages/testing-manual-testing-about-section.png) |
| I want to be able to navigate the site easily to find information. | The navigation links at the top of the page allow the user to go to the section they want. | [Nav Bar](assets/images/testingimages/testing-manual-testing-navbar.png) |
| I want to be able to find their social media profiles so I can see what their most recent cuts look like. | Social media links are at the bottom of the site. | [Footer](assets/images/testingimages/testing-manual-testing-footer.png) |
|`Returning Visitors`|
|  |  |  |
| I want to see if any new photos have been added to the gallery. | They can click on the gallery link and view any new photos there. | [Gallery Page](assets/images/testingimages/testing-manual-testing-gallery.png) |
| I want to book another haircut. | They can click on the contact page. On that page, there is a link to Instagram where they can direct message, or a submission form that is locationed at the bottom of the contact page. | [Contact Page](assets/images/testingimages/testing-manual-testing-contact.png) |
| I want to find social media links. | Social media links are in the footer on each page. | [Footer](assets/images/testingimages/testing-manual-testing-footer.png) |
|`Frequent Visitor Goals` |
|  |  |  |
| I want to see what time the barber opens and the location. | There is a timesheet on the contact page so they can see the time there, along with a map to the location of the barber. | [Contact Page](assets/images/testingimages/testing-manual-testing-contact.png)  |


### Full Testing

Full testing was performed on the following devices:

* Computer:
  * 1440p Monitor
  * 1080p Monitor
* Laptop:
  * Macbook Pro 2022 14 inch screen
* Mobile Devices:
  * Pocophone F3.
  * Samsung Galaxy S20 Ultra .

Each device tested the site using the following browsers:

* Google Chrome
* Safari
* Firefox


| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| `Navbar` |
|  |  |  |  |  |
| Logo | When clicked, the user will be redirected to the home page. | Clicked Logo | Redirected to the home page. | Pass |
| Home Page Link | When clicked, the user will be redirected to the home page.| Clicked link | Redirected to the home page. | Pass |
| About Link | When clicked, the user will be redirected to the About page. | Clicked link | Redirected to the About page. | Pass |
| Services Link | When clicked, the user will be redirected to the Services page. | Clicked link | Redirected to the Services page. | Pass |
| Gallery Link | When clicked, the user will be redirected to the Gallery page. | Clicked link | Redirected to the Gallery page. | Pass |
| Contact Link | When clicked, the user will be redirected to the Contact page. | Clicked link | Redirected to the Contact page. | Pass |
| `Footer` |
|  |  |  |  |  |
| Tiktok Button | When clicked, the user will be redirected to Guilherme's Tiktok page in a new tab. | Clicked button | Redirected to Guilherme's Tiktok page. | Pass |
| Instagram Button |  When clicked, the user will be redirected to Guilherme's Instagram page in a new tab. | Clicked button | Redirected to Guilherme's Instagram page. | Pass |
| `Home Page` |
|   |   |   |   |
| Book Right Now | When clicked, the user will be redirected to the contact page. | Clicked link  | Redirected to the contact page. | Pass |
| Review Photos are responsive | When hovered over, the picture grows larger. | Hovered over photo  | Image got larger and overlayed properly. | Pass |
| Tiktok Section loads and plays video | When videos are hovered over, they start playing and once clicked, they open. | Hovered over and clicked | On click, was redirected to Tiktok page and on hover, allowed me to view the Tiktok clips. | Pass |
| `About Page` |
|   |   |   |   |  |
| Page layout Properly | The image goes to the left and text on right. | Loaded page | The image displays on the left and text on the right. | Pass |
| `Services Page` |
|   |   |   |   |  |
| Page layout Properly | Table loaded in center. | Loaded page | Table loaded in center. | Pass |
| `Gallery Page` |
|   |   |   |   |  |
| Load Images and lay them out in a column of three | Load Images and lay them out in a column of three. | Loaded page | Pages load and the images format into a column of three. | Pass |
| `Contact Page` |
| Page layout Properly | There should be a section on the left with "contact me on Instagram" section then on the right there is a map location and time. Below, a form should load.  | Loaded page | The Instagram section is located to the left and the map and time are located to the right. Below, the "book your cut" form appears. | Pass |
| Instagram Button |  When clicked, the user will be redirected to Guilherme's Instagram page in a new tab. | Clicked button | Redirected to Guilherme's Instagram page.

| Pass |
| Form Validation | User should be unable to submit if first name, last name, email address, and a day isn't selected. | Didn't fill in each individual element then clicked on Book button. | Form submission gets rejected until all the required elements are filled in. | Pass |
| Form Submission | User should be able to submit form and be redirected to the success page. | Clicked on Book button. | Form submits and user gets redirected to success page. | Pass |
| `Success Page` |
|   |   |   |   |   |
| Home page link | Redirects the user to the home page. | Clicked link | Redirected to home page. | Pass |

 - - -


## BUGS

### Known Bugs

As far as I'm aware, there are currently no known bugs.


### Solved Bugs

| No | Bug | How I resolved the issue |
| :--- | :--- | :--- |
| 1 | The photo in the "Why Cut With Me" section had a lot of space on the right. | To fix this, I added a container on top of the image which allowed me to crop the right side of the image to look how I wanted it to. |
| 2 | The format of the "About" page kept breaking between 752 - 500px. | In order to fix this, I needed to add additional media queries and adjusted the format for these resolutions. |
| 3 | The format of the "Contact" page kept breaking between 1550px - 1200px. | In order to fix this, I needed to add additional media queries and adjusted the format for these resolutions. |
| 4 | The header was causing certain pages to have a horizontal scroll. | In order to fix this, I needed to remove the padding that was present as this, combined with width:100%, was causing errors as the header would take up a bit more room than what it should. I also added a margin:0 auto; to then center the logo in the middle of the page. |

