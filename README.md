# fbxstyle
Master cards &amp; style guides

Welcome to the email design guideline for Firebox!

### Contents
- Getting started
- Styles used
- Common card sample code (quick access)
- Testing/troubleshooting

### Getting started
If you are starting from scratch, use the <a href="https://github.com/firebox/fbxstyle/blob/master/master-template-blank.html">master-blank-template.html</a>. This has all of the styles, the logo and the footer. If you have an existing template and want to add extra cards that are not included in the builder, download or view the <a href="https://github.com/firebox/fbxstyle/blob/master/master-cards.html">master-cards.html</a> file.

#### Card anatomy
A card is an independent row that represents a display pattern. Basically, it is a section that is designed differently. See below for a image of how a card is split up.

<img src="http://media.firebox.com/i/github/anatomy.png" width="300">

You can see that the card is made up of table rows and columns. When you are editing or visualising the structure of the card, use this as a reference.

#### How to use the cards
As each card is an independent row, you can simply just copy and paste it anywhere between the `<body>` and `</body>` HTML tag. To copy a card, start from the `<!-- [NAME] CARD-->` and copy until the `<!-- END [NAME] CARD-->`. Each card in the <a href="https://github.com/firebox/fbxstyle/blob/master/master-cards.html">master-cards.html</a> file will be named in this format.

## Style the cards
You can style the cards pretty much any way you want. These are colourless and to be used as a template for whatever design you want to achieve.

#### Changing text colours
In the master cards file, text should only be two colours - `#343434` for title text and `#888888` for body text. When setting the `font-color` you should always apply the style to the `<td>` e.g `<td style="font-color: #000000;">` if you are using the master cards then the `font-color` should already be applied and simple to change.

#### Changing background colour
Changing the background colour of a card is super easy. You can change the background colour in two ways, either you want the entire card to be one colour or you want a background colour and a container colour. Look for the `bgcolor=`. See the  example below:

<img src="http://media.firebox.com/i/github/bgcolour.png" width="600">

## Style rules
For the cards please follow the rules set.

#### The 20px rule
In a nutshell the 20px rule is a guide to how much padding everything should have on the email. You will see that each card has a 20px padding inside the card, a 20px padding between cards and text groups have 20px padding in between them. When you add padding, always add `padding-bottom`, padding works downwards.

#### When you can break the 20px rule
The only time you can break the 20px rule is when you need to separate components further apart or you need to group text together. To group text together, you can use a 10px gap and if you want to separate further, use a 40px gap. Please don't use numbers like 42px or 21px, it will stress me out.

## Styleguide
See below for examples on basic styling for the cards. Feel free to change these styles for certain campaigns but please do not have the body text lighter than #888888

##### Title
18px, bold, uppercase, #343434

Example code:
``
style="font-family:'sofia', Helvetica, Arial, sans-serif; font-weight: bold; color: #343434; font-size: 18px; text-transform: uppercase;"
``

##### Paragraph
16px, #888888

Example code:
``
style="font-family:'sofia', Helvetica, Arial, sans-serif; font-weight: normal; color: #888888; font-size: 16px;"
``

## Quick cards
See below for quick access to our most popular cards, simply copy and paste them into your template.

#### Hero card
The main use for this card is to introduce a new or hero product.

```
<!-- HERO SECTION-->
<table border="0" cellpadding="0" cellspacing="0" width="100%">
    <tr>
        <td bgcolor="#F6F6F6" align="center" style="padding: 0px 15px 20px 15px;" class="section-padding">
            <table border="0" cellpadding="0" cellspacing="0" width="600" class="responsive-table"> <!-- LONGER WIDTH THAN 600 FOR OUTLOOK 07,10,11 -->
                <tr>
                    <td>
                        <table cellspacing="0" cellpadding="0" border="0" width="100%">
                          <tr>
          									<td align="center" bgcolor="#f6f6f6" valign="middle">
          											 <a href="http://www.firebox.com/product/7479/Luminoodle" target="_blank">
          												 <img alt="Glow in the Park" title="Glow in the park" src="http://media.firebox.com/i/nl/nl1073/luminoodle.jpg" width="600" border="0" style="display: block;" class="img-max">
          											</a>
          									</td>
                          </tr>
													<tr>
															<td align="center" bgcolor="#FFFFFF" valign="middle" width="600" class="wrapper" style="padding: 15px">

															<table cellspacing="0" cellpadding="0" style="width: 100%;" class="responsive-table" width="300">  <!-- STYLE WIDTH FOR CHROME BROWSER -->

																	 <tr cellspacing="0" cellpadding="0">

																			<td cellspacing="0" cellpadding="0" colspan="4"  style="font-family: Arial, sans-serif; color: #343434; font-size: 18px; font-weight: bold; text-align: center; padding: 0px 15px 15px 15px;">
																				 <a href="http://www.firebox.com/product/7479/Luminoodle" target="_blank" style="color: #343434; text-decoration: none;">LUMINOODLE</a>
																			</td>
																	</tr>
																	<tr>

																			<td cellspacing="0" cellpadding="0" colspan="4"  style="text-align: center; font-family: 'Arial', sans-serif; color: #999999 !important; font-size: 14px; line-height: 20px; font-weight: normal; padding: 0px 15px 15px 15px;">
																			A versatile string of LEDs producing 180 lumens (or should that be ramens?) of light. Powered by a powerful 4400mAh USB rechargeable battery pack and stored neatly inside a nylon carry bag that doubles up as a lantern. Clever, eh?
																			</td>
																	</tr>


																	 <tr cellspacing="0" cellpadding="0">
																			<td cellspacing="0" cellpadding="0" colspan="4"  style="font-family: Arial, sans-serif; color: #999999; font-size: 18px; line-height: 25.92px; font-weight: bold; text-align: center; padding: 0px 15px 15px 15px;">
																					<strong>&pound;29.99</strong>
																		 </td>
																	</tr>

																	<tr cellspacing="0" cellpadding="0">
																			<td cellspacing="0" cellpadding="0" style="width: auto;">&nbsp;</td>
																			<td colspan="2" style="text-align: center; background-color: #000000 !important; border-top-left-radius: 2px; border-top-right-radius: 2px; border-bottom-left-radius: 2px; border-bottom-right-radius: 2px; max-width: 175px !important;" width="50%" height="37" bgcolor="#000000">
																					<a href="http://www.firebox.com/product/7479/Luminoodle" target="blank" style="font-family: 'Arial', sans-serif; display: inline-block; background-color: #000000 !important; font-weight: normal; color: #fff; border-top-left-radius: 2px; border-top-right-radius: 2px; border-bottom-left-radius: 2px; border-bottom-right-radius: 2px; text-decoration: none; margin: 0;">BUY NOW</a>
																				</td>
																			<td cellspacing="0" cellpadding="0" style="width: auto;">&nbsp;</td>
																	</tr>

															</table>
															</td>
													</tr>
                        </table>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
<!-- END HERO SECTION-->
```

#### Image or slice card
The main purpose of this page is to promote your imagery.

```
<!-- IMAGE/SLICE CARD -->
<table border="0" cellpadding="0" cellspacing="0" width="100%">
    <tr>
        <td bgcolor="#f6f6f6" align="center" style="padding: 0px 15px 0px 15px;" class="slice-padding">
            <table border="0" cellpadding="0" cellspacing="0" width="600" class="responsive-table">
                <tr>
									<td align="center" bgcolor="#FFFFFF" valign="middle">
											<a href="http://www.dot.com?itc=FB_ITC&nl_id=NL_ID" target="_blank">
													<img src="http://media.firebox.com/i/nl/nl1073/top102.jpg" width="600" style="display: block; width: 600px;" alt="FB_ALT" title="FB_TITLE" border="0" class="img-max">
											</a>
									</td>
                </tr>
            </table>
        </td>
    </tr>
</table>
```

## Buttons
```
<tr cellspacing="0" cellpadding="0">
  <!--[if mso]>
      <td style="text-align: center;" class="btn" width="250" height="37" align="center" bgcolor="#343434">
  <![endif]-->
  <!--[if !mso]><!-- -->
    <td style="text-align: center;" class="btn" width="250" height="37" align="center">
  <!--<![endif]-->
       <a href="https://www.firebox.com/admin/customerreviews?itc=944&utm_source=email&utm_medium=welcome&utm_campaign=welcome_2" target="blank" style="font-family:'sofia', Helvetica, Arial, sans-serif; display: inline-block; padding: 10px 20px; border-radius: 2px; background-color: #343434 !important; font-weight: bold; color: #fff; line-height: 1; text-decoration: none; margin: 0; text-transform: uppercase;">
         View more reviews</a>
     </td>
   </tr>
```

How to test
Litmus

Testing
- On responsive the box doesn't fit 100%
