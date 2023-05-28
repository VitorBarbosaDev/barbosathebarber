
 Barbosa The Barber - TESTING
 
![Multi_Display_Example](assets/images/readmeimages/readme_mutipledisplaysphoto.png)

The site was build to be used a singular place where my brother guilherme who is a barber could promote his business and have all the information in one place in order to hopefully be able to aquire new customers 


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
| I want to find out who Barbosa the Barber is. | An "About" page is linked in the header. There is a section about Guilherme. | :--- |
| I want to be able to navigate the site easily to find information. | The navigation links at the top of the page allow the user to go to the section they want. | :--- |
| I want to be able to find their social media profiles so I can see what their most recent cuts look like. | Social media links are at the bottom of the site. | :--- |
|`Returning Visitors`|
|  |  |  |
| I want to see if any new photos have been added to the gallery. | They can click on the gallery link and view all the photos there. | :--- |
| I want to book another haircut. | They can click on the contact page. On that page, there is a link to Instagram where they can direct message, or a submission form that is locationed at the bottom of the contact page. | :--- |
| I want to find social media links. | Social media links are in the footer on each page. | :--- |
|`Frequent Visitor Goals` |
|  |  |  |
| I want to see what time the barber opens and the location. | There is a timesheet on the contact page so they can see the time there, along with a map to the location of the barber. |  |


### Full Testing

👩🏻‍💻 View an example of a completed full testing section [here](https://github.com/kera-cudmore/TheQuizArms/blob/main/TESTING.md#Full-Testing)

Full testing can be tedious, so it is great to try and break this part up into smaller chunks and do a bit at a time. Full testing is when you go through the site and test every single thing that can be tested. So for example you would test that all links in the navbar correctly redirect the user to where there are supposed to go. A table is the perfect way to display this information.

## BUGS

### Known Bugs

There are no bugs that I know of.

### Solved Bugs

👩🏻‍💻View an example of a completed bugs section [here](https://github.com/kera-cudmore/BookWorm/blob/main/TESTING.md#BUGS)

This is where all solved bugs go once squashed. List what the bug was, and how you managed to fix it. You can also include images/videos here if you wanted.
