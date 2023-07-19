# The-lady-gardener & how i built a website for my wife's business.




## The website 'Tracey the Gardengal', the idea, the discussion and the wireframing.

For my first milestone project I decided that what I really wanted was to design and build a
website for a genuine business. Fortunately my wife , Tracey, has over the past three years
built up a small gardening business through a combination of Facebook leads and word of mouth.
The one thing she doesn't have is a dedicated website, something that she can point potential 
customers at, a shop window if you will, that will give people an understanding of her business 
ethos and just as importantly a feel for who she is as a person and a gardener.

The basic design and layout of the website was discussed over a period of 2-3 days and some 
basic wireframe diagrams were hand drawn by myself. These are included here for reference 
purposes. There was no need for dedicated software such as Balsamiq or my own preferred design
software, Figma, as it was easier for us to sit together in our lounge and for me to sketch 
the ideas on a piece of A4 paper. It was during these initial consultations that the name of the 
business was finalised as Tracey really liked the fact that a lady gardener is known as either 
a Gardenerette or a Gardengal.


[WIREFRAME JPEG HERE]

## Website construction, testing and deployment.

In order to code the website I used a combination of VS Code and Stackblitz IDE's. The main 
code was written, tested and debugged in VS Code as I have found this IDE to be one of the most
fully featured environments currently available. Stackblitz was used to build and test small 
portions of the code before moving the code over to VS Code. The reason for this is that Stackblitz
has a useful 'party trick' in that the preview browser displays the code in real time meaning you 
can see how the code looks and behaves instantly. (nb. I have since discovered that you can now do 
this in VS Code by installing the 'live preview' extension from Microsoft). By adopting a 
reductionist approach to the code build this allowed me to debug in 'bitesize' chunks and
thus reduce the risk of any major issues getting into the build as it was constructed

The testing of the site as a whole was completed using a combination of the desktop browsers Chrome
v114.0.5.5735.198, Firefox v114.0.2 and Edge v114.0.1823.67 on my Win 11 Pro desktop PC, mobile Safari
on my Wife's iPhone 11 and mobile Chrome on my Android Nothing Phone(1). I also made extensive use of
the devtools built into Chrome desktop browser.

To give the site great responsive behaviour across phone, tablet, laptop and desktop screens I took 
the decision to use the CSS library Bootstrap as there seemed little point in 'reinventing the wheel'
and building this from scratch. A couple of appropriate fonts, Caveat and Roboto were imported from
Google Fonts and the Facebook and Instagram icons were imported from Font Awesome V4.7. The colour 
scheme was picked using Adobe Colour Wheel and based around the main colour purple, my wife's
favourite colour. All the images used are genuine photos shot on my wife's iPhone 11 as my wife felt
that photos from her workplaces would give the site a more authentic feel.

Deployemnt of the site is via Github pages with a regular commit/push history available as these were 
always undertaken at key stages throughout the development period. As the site uses only HTML & CSS 
there was no need to add a git ignore file.

## The 3-page design and what each page does and why.

My wife wanted a simple straightforward site design and it was agreed that a 3-page design would meet 
this brief by presenting all relevant information without being unwieldy or difficult to navigate. The
header/footer design used across the site gives a nice splash of colour with a nice flourish being the 
graded colour moving from purple to yellow diagionally across these sections but with the colours 
reversed in the footer so they run from yellow to purple. The green used has had it's opacity reduced 
to make it much more pastel in look. Another flourish is the gallery that is presented as a series of 
black and white photos that turn to colour when hovered over really drawing your eye to the selected 
picture. Information about the selected plant/flower is presented via the use of <details> html. Again Bootstrap
enabled this feature albeit customised to better suit the look of the site. The third page is a simple 
contact me section with email and phone options. A nice touch with the email is the use of mailto: to 
provide a easy way to begin an email message. There is also the option to click on the Facebook/Instagram 
icons ever present in the footer to be taken to my wife's social media accounts.

## known issues with project.

1/  On low resolution displays ie. either an x-axis resolution less than 375px or a y-axis resolution less
than 600px there are issues with text spilling over onto either the header and/or footer and the navbar 
spilling out of the header. The decision has been taken to ignore these issues. The site is responsive 
and it's behaviour is good on all modern screen sizes tested. The low resolutions are only present on
much older devices and I feel that these devices only represent a tiny minority of devices currently 
being used. Even current budget phones today have screen resolutions of 720p as a minimum meaning that 
the site displays well on the vast majority of phones that are currently in use.

2/  There is an issue with embedded Google maps and accessibility as it is not readable by current
screen readers. this is a known issue and a Google search highlights this. I still felt that it was 
a good idea to include the embedded map but equally important to highlight this issue. One that 
hopefully Google can address in the not too distant future.

3/  During the deployemnt of the build it has also become apparent that Gitpages doesn't always 
update correctly when using a custom domain name. Hence the need to revert to the standard address
for the site on occasion throughout the build and deployment. Once the build has been finalised
then the site will use the custom domain 'traceygardengal.com' as this is a better and more
professional address for my wife's website and definitely much preferred when giving the website
address to potential clients.

## software/websites used for this build

[Bootstrap v5.3 - CSS library](https://getbootstrap.com/)

[Compress images For website](https://compressnow.com/)

[Custom domain for website](https://domains.google.com/)


# Tracey the Gardengal

My wife has, over the past three years or so, built a successful garden business having decided to quit her safe but boring office based job of ten years plus. She generates her business through word of mouth with a small part coming from Facebook, it's probably a 90/10 split in favour of word of mouth. She has also just started on Instagram but what is really needed is something that she can get her existing clients to give as a taster for what she does. Something for potential new clients to have a look at before they speak to her or she contacts them. There's a nice bit of synchronicity here with my desire to build a site for a genuine business.

Tracey the Gardengal's website took shape from this simple idea. Together we discussed the format, basic layout and exactly what my wife wanted the site to do. Wireframing was done by hand on a sheet of A4 as it was just easier for us and given that we are husband and wife a lot more comfy that way sitting on our sofa. I have included an image of the hand drawn wireframes for reference purposes. It was also very important that the site works just as well on a mobile device as laptop/desktop as more and more people even in the age demographic that my wife predominantly deals with are just using a mobile device to access the internet.

![Responsive Mockup](https://ui.dev/amiresponsive?url=https://www.traceygardengal.com)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __The landing page image__

  - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __Club Ethos Section__

  - The club ethos section will allow the user to see the benefits of joining the Love Running meetups, as well as the benefits of running overall. 
  - This user will see the value of signing up for the Love Running meetups. This should encourage the user to consider running as their form of exercise. 

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Meetup Times section__

  - This section will allow the user to see exactly when the meetups will happen, where they will be located and how long the run will be in kilometers. 
  - This section will be updated as these times change to keep the user up to date. 

![Meetup Times](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __Gallery__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __The Sign Up Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 