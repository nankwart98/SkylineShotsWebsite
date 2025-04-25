# SkylineShotsWebsite

My first take on Skyline Shots, my drone content page.

I started off the initial coding projects in Code Pen due to me working away from home, the iniitial draft consisted of mainly the html, wherein i added the main header for the page, followed by all the subheadings and the call to actions.

As i decided to base this page of my own personal content and brand, i used my brand name, slogan and my own images and ensured to change the font family on the page to bree serif.

I created the navigation links under the headers and ensured to create more navigation links at the bottom of the page above the footer.

In CSS i tried including my logo on the page but it continuosly ended up completely blowing up covering the entire page so i stopped pursuing this endeavour, instead settling on making my header font big and presentable, as well as adding opacity to the background colour of the header.

I tried using the media min width to make the page more mobile friendly as the header was too big in mobile view but i struggled with this.

I have now succesfully added my own media into a folder and managed to add it to the website

I then changed the header font colour to orange as it aligns with my brands logo

I tried adding the social media icons on to my page by using the following source _// <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> _// and this element <i class="fa fa-twitter"></i>
<i class="fa fa-twitter" style="font-size:24px"></i>

attempted adding my logo for further branding but was unable to, used the following css code, .logo {
position: absolute;
top: 0;
left: 0;
max-width: 1%;
max-height: 1%;
z-index: 1000;
border-radius: 30px;
}
and sourced the image to my html by adding it to my media files

I then tried using the following syntax to make my website more mobile friendly but to no avail:

@media (min-width: 320px) {
.container-text {
font-size: 30%;
}
header {
display: flex;
align-items: flex-start;
}
}
.footer-container {
font-size: 3%;
display: flex;
align-items: flex-start;
}
