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
reductionist approach to the code build thsi allowed me to debug the code in 'bitesize' chunks and
this reduced the risk of any major issues getting into the code as I constructed the site.

The testing of the site as a whole was completed using a combination of the desktop browsers Chrome
v114.0.5.5735.198, Firefox v114.0.2 and Edge v114.0.1823.67 on my Win 11 Pro desktop PC, mobile Safari
on my Wife's iPhone 11 and mobile Chrome on my Android Nothing Phone(1). I also made extensive use of
the devtools built into Chrome desktop browser.

To give the site great responsive behaviour across phone, tablet, laptop and desktop screens I took 
the decision to use the CSS library Bootstrap as there seemed little point in 'reinventing the wheel'
and building this from scratch. A couple of appropriate fonts, Caveat and Roboto were imported from
Google Fonts and the Facebook and Instagram icons were imported from Font Awesome V4.7. The colour 
scheme was picked using Adobe Colour Wheel and based around the main colour purple, my wife's
favourite colour. All the images used are genuine photos shot on my Nothing Phone(1) as my wife felt
that photos from her workplaces would give the site a more authentic feel.

Deployemnt of the site is via Github pages with a regular commit/push history available as these were 
always undertaken at key stages throughout the development period.

## The 3-page design and what each page does and why.

My wife wanted a simple straightforward site design and it was agreed that a 3-page design would meet 
this brief by presenting all relevant information without being unwieldy or difficult to navigate. The
header/footer design used across the site gives a nice splash of colour with a nice flourish being the 
graded colour moving from purple to yellow diagionally across these sections but with the colours 
reversed in the footer so they run from yellow to purple. The green used has had it's opacity reduced 
to make it much more pastel in look. Another flourish is the gallery that is presented as a series of 
black and white photos that turn to colour when hovered over really drawing your eye to the selected 
picture. Information about the selected plant/flower is presented via the use of modals. Again Bootstrap
enabled this feature albeit customised to better suit the look of the site. The third page is a simple 
contact me section with email and phone options. A nice touch with the email is the use of mailto: to 
provide a easy way to begin an email message. There is also the option to click on the Facebook/Instagram 
icons ever present in the footer to be taken to my wife's social media accounts.
