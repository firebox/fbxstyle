# fbxstyle
Master cards &amp; style guides

Welcome to the email design guideline for Firebox!

##Contents
- Getting started
- Styles used
- Common card sample code (quick access)

###Getting started
If you are starting from scratch, use the <a href="https://github.com/firebox/fbxstyle/blob/master/master-template-blank.html">master-blank-template.html</a>. This has all of the styles, the logo and the footer. If you have an existing template and want to add extra cards that are not included in the builder, download or view the <a href="https://github.com/firebox/fbxstyle/blob/master/master-cards.html">master-cards.html</a> file.

###How to use the cards
Each card can be used independently from one another as there is no parent container or wrapper.
To copy a card, start from the `<!-- [NAME] CARD-->` and copy until the `<!-- END [NAME] CARD-->`

##Quick cards
See below for quick access to our most popular cards, simply copy and paste them into your template.

####Hero card
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
<!-- END HERO SECTION-->```

####Hero card
The main use for this card is to introduce a new or hero product.


```
<!-- IMAGE CARD -->
<table border="0" cellpadding="0" cellspacing="0" width="100%">
    <tr>
        <td bgcolor="#f6f6f6" align="center" style="padding: 0px 15px 0px 15px;" class="slice-padding">
            <table border="0" cellpadding="0" cellspacing="0" width="600" class="responsive-table">
                <tr>
									<td align="center" bgcolor="#FFFFFF" valign="middle">
											<a href="https://www.firebox.com/chart" target="_blank">
													<img src="http://media.firebox.com/i/nl/nl1073/top102.jpg" width="600" style="display: block; width: 600px;" alt="Top 10 Products during March" title="Top 10 Products during March" border="0" class="img-max">
											</a>
									</td>
                </tr>
            </table>
        </td>
    </tr>
</table>
```

```
<table border="0" cellpadding="0" cellspacing="0" width="100%">
    <tr>
        <td bgcolor="#F6F6F6" style="padding: 0px 15px 0px 15px;" class="smaller-padding">
            <div align="center">
                <table border="0" cellpadding="0" cellspacing="0" width="600" class="wrapper">
                    <tr>
                      <td background="https://i.imgur.com/YJOX1PC.png" bgcolor="#7bceeb" width="120" height="92" valign="top">
                      <!--[if gte mso 9]>
                      <v:rect xmlns:v="urn:schemas-microsoft-com:vml" fill="true" stroke="false" style="width:120px;height:92px;">
                        <v:fill type="tile" src="https://i.imgur.com/YJOX1PC.png" color="#7bceeb" />
                        <v:textbox inset="0,0,0,0">
                      <![endif]-->
                      <div>
                        Hello guys
                      </div>
                      <!--[if gte mso 9]>
                      </v:textbox>
                      </v:rect>
                      <![endif]-->
                      </td>
                    </tr>
                </table>
            </div>
        </td>
    </tr>
</table>
```


##Email styles
I have made some amendments to the colours of the emails due to the brightness not rendering well on older monitors

Heading
#343434

Paragraph and sub copy
#888888

When adding text styles and fonts to an email you need a few parameters to get started.
Code


When I view a card on mobile it has a gap
slice and section padding


Buttons
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
