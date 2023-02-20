# Save the Rhinos

Save the Rhinos is a static website designed to encourage the spreading of information over the issue of Rhino endangerment and extinction, which is a pressing issue in the world of ecology and conservation. it provides information about the species and provides its users the opportunity to support the cause through: donation, adoption and affiliation in the animal welfare community. 

![image](https://user-images.githubusercontent.com/104646542/219870446-892b3ffb-5bfc-478b-97fd-caac55b2da15.png)

Visit us here at: https://save-the-rhinos-bubtroniq.vercel.app/

# Table of Contents

[User Experience (UX)](#user-experience-ux)
- [Colour Scheme](#colour-scheme)
- [Typography](#typography)

[User Stories](#user-stories)
- [New Site Users](#new-site-users)
- [Returning Site Users](#returning-site-users)
- [Frequent Site Users](#frequent-site-users)

[Wireframes](#wireframes)

[Features](#features)
- [Existing Features](#existing-features)

[Tools & Technologies Used](#tools--technologies-used)

[Testing](#testing)
- [Code Validation](#code-validation)
- [Functionality Testing](#functionality-testing)
- [Performance Testing](#performance-testing)

[Deployment](#deployment)

[Credits](#credits)
- [Content](#content)
- [Media](#media)

[Acknowledgements](#acknowledgements)

## User Experience (UX)

### Colour Scheme

The main colours are black and white. To grab the user's attention, yellow and red are used on particular elements such as buttons and navigation menu items.

![Save Rhinos Colour Scheme](docs/colour_scheme.png)

We've used CSS `:root` variables to easily update the global colour scheme by changing only one value, instead of everywhere in the CSS file.

```css
:root {
    --main-black-color: #000;
    --main-white-color: #fff;
    --main-white-shade-color: #F7F3F3;
    --main-white-shade2-color: #e4e0e0;
    --accent-gold-color: #F7B21F;
    --accent-gold-shade-color: #C78900;
    --accent-gold-shade2-color: #f0d080;
    --accent-red-color: #e73d3d;
    --accent-red-shade-color: #C51426;
}
```

### Typography

- [Montserrat](https://fonts.google.com/specimen/Montserrat) is the main font used throughout the whole website with Sans Serif as the fallback font in case the font isn't imported into the browser correctly. Montserrat has a highly readable body typeface and a variety of weights and styles.

- [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab) is used for the headings.

- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the social media icons in the footer.

## User Stories

### New Site Users

| ID | Story | Implemented page/section |
| --- | --- | ---|
| [#22](https://github.com/bubtroniq/Chronicles-of-Java/issues/22) | As a First Time Visitor, I want to easily understand the main purpose of the site so that I can quickly decide whether I want to explore it more. | Homepage |
| [#23](https://github.com/bubtroniq/Chronicles-of-Java/issues/23) |As a First Time Visitor, I want to easily navigate the sections so that I can easily find the content. | Navigation |
| [#47](https://github.com/bubtroniq/Chronicles-of-Java/issues/47) | As a First Time Visitor, I want to see the organisation's projects so that I can decide whether I want to be involved. | About page |
| [#48](https://github.com/bubtroniq/Chronicles-of-Java/issues/48) |As a First Time Visitor, I want to check their social media so that I can determine whether they are trustworthy. | Footer |

### Returning Site Users

| ID | Story | Implemented page/section |
| --- | --- | ---|
| [#24](https://github.com/bubtroniq/Chronicles-of-Java/issues/24) | As a returning visitor, I want to find possible ways how to donate so I can easily donate. | Homepage |
| [#25](https://github.com/bubtroniq/Chronicles-of-Java/issues/25) | As a returning visitor, I want to know how the funds are used so that I can donate confidently. | Homepage|

### Frequent Site Users

| ID | Story | Implemented page/section |
| --- | --- | ---|
| [#49](https://github.com/bubtroniq/Chronicles-of-Java/issues/49) | As a donator, I want to know about new activities with the organisation so that I can decide whether I donate more. | Homepage |

## Wireframes

### Mobile Wireframes

![Mobile Wireframe](docs/wireframes/phoneView.png)

### Tablet Wireframes

![Tablet Wireframe](docs/wireframes/ipadView.png)

### Desktop Wireframes

![Wireframe](docs/wireframes/homepage.png)
![Wireframe](docs/wireframes/infopage.png)
![Wireframe](docs/wireframes/involvedpage.png)

## Features

### Existing Features

- **Feature #1**

The logo

![image](https://user-images.githubusercontent.com/104646542/219871762-a462d228-49df-4ebb-901f-34484f039f82.png)

- **Feature #2**

The nav bar. It is fully responsive and has four sections. First, "Get involved", which links to further down the page and repeats the donate button which is spread over the site. It has a title as well as some information on rhino endangerment, with an encouraging messaging to get involved with the protection of their species. secondly, the "Gallery", which has a slideshow depiting pictures of rhinos. It has its own dedicated page which has been coded into the workspace. Thirdly, an "About" page. This also has its own separate page and links to an informational section on who Save the Rhinos are and another section on what they do. This is followed by an embedded link that takes you to a live cam on youtube of rhinos in a protected sanctuary. Lastly on the nav bar, there is the "Donate" page, which links externally to the [_Save the Rhino_ donation page](https://www.savetherhino.org/get-involved/donate), an already exisiting page for "Save the Rhino" with the option to donate to an actual charity and thus adding a real contributive user experience. 

   ![image](https://user-images.githubusercontent.com/104646542/219871639-f9d6e416-57f1-4b47-8f93-f49cf337f09c.png)

- **Feature #3**

Main body of the home page with responsive buttons. This consists of another informational section on rhino endangerment and details the species' statistics over the last two centuries and the critical reduction in their existence. It details the reasons behind this and then has two responsive buttons underneath: "Adopt"- which links to an already existing charity site by WWF- [link](https://support.wwf.org.uk/adopt-a-rhino?utm_source=Google-Generic&utm_medium=PaidSearch-Generic&pc=AVN014003&&&gclid=Cj0KCQiA6LyfBhC3ARIsAG4gkF9rfKmk8KUSL1ptkpAeJwKIzE7-rkFusdw8i76nsELK94NwSwlQB4AaAla6EALw_wcB&gclsrc=aw.ds). It provides the user with an actual oppportinity to adopt a rhino and help the cause, once again adding a real contributive user experience. The other responsive buttons is "Donate" which links again to the same site as in the nav bar. 

![image](https://user-images.githubusercontent.com/104646542/219871833-384fdb32-0a41-48a3-94b4-4aeb93d7d4ee.png)

- **Feature #4**

About page. This is styled as the same main body of the page and has a bigger informational section about the cause.

![image](https://user-images.githubusercontent.com/104646542/219982192-35a81471-5e6e-4824-82c8-5aeda3b8d19f.png)


- **Feature #5**

Charity information. This setion details all that the charity are doing to aid the cause. It includes another encouraging message to stand together and save the species with suport and donations. Then, some info on the outstanding achievements that have already been attained, followed by a responsive "Read more about our impact" button, that takes you externally to the [_Save the Rhino_ our impact page](https://www.savetherhino.org/about-us/our-impact/) so you can read further information on how they are helping. lastly in this section of the page, there are some statistics on: how much money was raised, how kuch land is being patrolled to protect rhinos and how many african canine units were supported in boosting their awareness of rhino endangerment issues.

![image](https://user-images.githubusercontent.com/104646542/219872156-a0b81e9f-2ac1-4987-8a0a-058f170c86c1.png)

- **Feature #6**

"Get involved" section. This is where the button on the nav bar directs to on the main page. It has more information on the cause and once again, a link to the donate button. it also contains a list of projects that they are involved in: protecting rhinos, reducing illegal trade and engaging communities.

![image](https://user-images.githubusercontent.com/104646542/219872281-f8863233-26b4-4fcb-adc4-abb0c3b8d4ea.png)

- **Feature #7**
Video of the day section. In this section is embbeded an iframe displaying youtube videos with rhinos. Everyday a different video is displayed, that being done using JavaScript.
![image](docs/video-of-the-day.jpg)

- **Feature #8**

Footer. This sections has links to social media pages for: Facebook, Twitter, Youtube and instagram. It also contains: a terms and conditions page, privacy policy and copyright image for the hackathon project. 

![image](https://user-images.githubusercontent.com/104646542/219872365-8b73fafb-2f15-4721-b79c-fe15f4fe656f.png)

- **Feature #9**

The "Gallery". This takes you to an external page when clicked on in the nav bar. It contains a gallery of 5 rhino images and also has a drop down menu to the left to take you back to the other pages.

![image](https://user-images.githubusercontent.com/104646542/219872633-2a35b91f-0300-4e24-945e-06f532d293ea.png)

- **Feature #10**

About page is displaying two new sections, who
 we are section and what we do section.Here you can find more detailed info about what our organization is doing at the moment and what is planning for the future.
 ![image](docs/who-we-are.jpg)
 ![image](docs/what-we-do.jpg)

- **Feature #11**

The "Donate" link. This is the last part of the nav bar and takes you externally to the [_Save the Rhino_ donation page](https://www.savetherhino.org/get-involved/donate).

![image](https://user-images.githubusercontent.com/104646542/219872785-38537c8a-7624-4b37-bba9-114bbacb9380.png)


- **Feature #12**

The "Adopt" link. This is part of the main home page and is where the yellow donate button takes you to. It externally links to the [_WWF_ adopt page](https://support.wwf.org.uk/adopt-a-rhino?utm_source=Google-Generic&utm_medium=PaidSearch-Generic&pc=AVN014003&&&gclid=Cj0KCQiA6LyfBhC3ARIsAG4gkF9rfKmk8KUSL1ptkpAeJwKIzE7-rkFusdw8i76nsELK94NwSwlQB4AaAla6EALw_wcB&gclsrc=aw.ds)

![image](https://user-images.githubusercontent.com/104646542/219872833-99c843d8-ff89-42e3-87a3-11e8e45c80b0.png)



## Tools & Technologies Used

[Techsini](https://techsini.com/)
[GitHub](https://github.com/)
[Gitpod](https://www.gitpod.io/)
[Vercel](https://www.vercel.com/)
[YouTube](https://www.youtube.com/)
[W3C Markup Validation Service](https://validator.w3.org/ )
[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
[JSHint](https://jshint.com/)
[Page-templates]https://freefrontend.com/html-css-404-page-templates/
[Camtasia]https://camtasia-studio.en.uptodown.com/windows/download


## Testing

### Code Validation

- HTML Validation

    - No errors or warnings were found when passing through the [W3C Markup Validator](https://validator.w3.org/).

        ![HTML validation](docs/testing/validation-html.png)

- CSS Validation

    - No errors or warnings were found when passing through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).

        ![CSS validation](docs/testing/validation-css.png)

- JS Validation

    - No errors or warnings were found when passing through [JSHint](https://jshint.com/).

    - `app.js`
        ![JS validation](docs/testing/validation-js_app.png)
    - `index-script.js`
        ![JS validation](docs/testing/validation-js_index.png)
    - `script.js`
        ![JS validation](docs/testing/validation-js_script.png)

### Functionality Testing

### Performance Testing

- We have measured the performance, accessibility, best practices and SEO using [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) in Chrome DevTools in incognito mode.

![Lighthouse report](docs/testing/lighthouse.png)

## Deployment

This site was deployed via vercel and can be found live at: https://save-the-rhinos-bubtroniq.vercel.app/ 

### Local Deployment



#### Cloning



#### Forking



### Local VS Deployment



## Credits



### Content

- Save the Rhino
    - [Donate](https://www.savetherhino.org/get-involved/donate)
    - [Our impact](https://www.savetherhino.org/about-us/our-impact/)

- WWF
    - [Adopt a rhino](https://support.wwf.org.uk/adopt-a-rhino?utm_source=Google-Generic&utm_medium=PaidSearch-Generic&pc=AVN014003&&&gclid=Cj0KCQiA6LyfBhC3ARIsAG4gkF9rfKmk8KUSL1ptkpAeJwKIzE7-rkFusdw8i76nsELK94NwSwlQB4AaAla6EALw_wcB&gclsrc=aw.ds)

### Media

## Acknowledgements

#### Anthony_Hacklead
#### Code Institute
#### The hackathon team(#2):

#### Sejung Kwak
#### Killol Sevak
#### Freda Toal
#### Adam Keane
#### Karl Moran
#### Razvan Joitescu
#### Steve Docherty