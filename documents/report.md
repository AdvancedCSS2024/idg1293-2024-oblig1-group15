The oblig did not specify were we should place images and icons used, so a new folder called images was created inside assets for this.

Fabric says H1 should be 34px/2.125rem, but the actual website's log in page H1 uses 1.5rem. We decided to follow Fabric, as one of the goals of the oblig is to show that we can follow the documentation of an existing design system.

The closest color from Fabric was chosen for the few instances were the Finn website used a color not listed in Fabric.

Fabric states that a typeface exclusively owned by Finn should be used. We instead had to find a free typeface that looked similar to the one Finn uses. For this reason our submission uses the Wix Madefor Display typeface from Google Fonts.

We did not have access to the settings of our GitHub repository, so we were unable to deploy the website.

It did not seem possible to make the login page exactly like the Finn.no version using just SASS. The checkbox hack could potentially have been used for the input field buttons, but that is really best done using JavaScript, due to separation of concerns. CSS/SASS is for styles, not behavior.

[The placeholder-shown method used for input labels and fields in common.scss was gotten from Stack Overflow](https://stackoverflow.com/questions/16952526/detect-if-an-input-has-text-in-it-using-css-on-a-page-i-am-visiting-and-do-no)
