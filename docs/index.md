#Build user centred products for the Data Platform
##How to use this guide
By using this guide, you can ensure that the user of your product sees a familiar and easy-to-use user-interface, and will find it similar to other products they use at work.

It’s important to ensure that all products can be used as intended and that end-users understand the interface and can get the outcome they need easily. This guide contains clear and consistent guidelines on core design elements, including colour palettes, typography, and layout structures.

In the final version you will also find screengrabs of templates to be used in Workshop - with annotations to explain which Workshop widgets to use.

##Top five things to consider
###1. Core colours

- <p class="inline-container">NHS Blue<span class="colour-rect" style="--colour: #005EB8; --txt_clr: white">#005EB8</span> Use this for logos, straps</p>

- <p class="inline-container">White<span class="colour-rect" style="--colour: #FFFFFF; --txt_clr: black">#FFFFFF</span> Use this for labels on buttons, NHS logo, headings on NHS blue</p>

Users think that when colour is used it is trying to convey information, so make sure the use of colour is intentional and consistent. Don't use colour just for decoration: 

- see the section on Guidance on use of colour - to ensure consistent experience for users across all products 
- a proportion of users cannot differentiate different colours. To communicate with people who cannot see well or distinguish colours, you may need to: 
    - ensure that the contrast between colours is high enough using a colour tool
    - word things differently
    - use more than one visual cue, for example, text and an icon as well as colour

###2.	Type sizes  
- the Workshop tool uses type sizes Small, Medium and Large. We believe that the “small” size is unreadable for many users.
- if specifying text in points or pixels, the optimal default font size for maximum readability for most users is 19px on large screens and 16px on small screens. Font size should not be smaller than size 10px.

###3.	Accessibility
- In the UK, almost 1 in 5 people have a disability of some kind. Many more have temporary or situational disabilities, like an illness or injury. When you're working on NHS internal services, think about how people with different needs might use what you're making.  
- set up automated accessibility testing and fix issues you identify
- use the NHS <a href="https://nhsdigital.github.io/accessibility-checklist/">accessibility checklist</a> to carry out an initial Web Content Accessibility Guidelines (WCAG) evaluation
 
###4.	Headings  
- make headings meaningful, let readers know where they are and what they are looking at 
- use “Sentence Case” for headings  
- make proper use of the Semantic page structure used in Workshop to make it readable by screen-readers

###5.	Links 
- make links meaningful, do not say “click here”. Provide context where it will take the user
- when a link will open a new tab for the user, add the words “opens in new tab” (or window) to the line

##Guidance on use of colour 
Users find colours indicative of meaning, therefore, we need to use colour intentionally and consistently. Don't use colour just for decoration.

- **Accessibility:** make sure that what the colour is "saying" is available in other ways. To communicate with people who cannot see well or distinguish colours, you may need to:
    - word things differently 
    - use more than one visual cue, for example, text and an icon as well as colour
    - ensure that the contrast between colours is high enough using a testing tool 
        - <a href="https://webaim.org/resources/contrastchecker/">WebAIM's colour contrast checker</a> (opens in a new window)
        - <a href="https://colororacle.org/">Color Oracle</a> (free colour-blindness simulator) (opens in a new window)
        - <a href="https://silktide.com/>Silktide</a> (opens in a new window)
 

### Core colours 
	
- <p class="inline-container">NHS Blue<span class="colour-rect" style="--colour: #005EB8; --txt_clr: white">#005EB8</span> Use this for logos, straps</p>   
- <p class="inline-container">White<span class="colour-rect" style="--colour: #FFFFFF; --txt_clr: black">#FFFFFF</span></p>

### Buttons  
		
- <p class="inline-container">Button colour<span class="colour-rect" style="--colour: #007F3B; --txt_clr: white">#007F3B</span></p>
<p>A primary button is for the user’s main action on a page. There may not be a main action and in that case use the secondary or tertiary buttons</p>
- <p class="inline-container">Secondary button colour<span class="colour-rect" style="--colour: #4C6272; --txt_clr: white">#4C6272</span></p> 
<p>Use a secondary button on pages that have more than 1 action or when users aren't noticing standard link text.</p> 
- <p class="inline-container">Button labels <span class="colour-rect" style="--colour: #FFFFFF; --txt_clr: black">#FFFFFF</span></p>

### NHS blue-grey background

- <p class="inline-container">Page background<span class="colour-rect" style="--colour: #F0F4F5; --txt_clr: black">#F0F4F5</span></p>

### Error state  

- <p class="inline-container">Error state colour<span class="colour-rect" style="--colour: #D5281B; --txt_clr: white">#D5281B</span></p>
<!-- 
### RAG colours (Red Amber Green)
	
- <p class="inline-container">Red colour<span class="colour-rect" style="--colour: #DA291C; --txt_clr: white">#DA291C</span></p> 	
- <p class="inline-container">Amber colour<span class="colour-rect" style="--colour: #ED8B00; --txt_clr: white">#ED8B00</span></p> 
- <p class="inline-container">Green colour<span class="colour-rect" style="--colour: #006747; --txt_clr: white">#006747</span></p>
!-->

### Link colours 
- <p class="inline-container">Link colour<span class="colour-rect" style="--colour: #005EB8; --txt_clr: white">#005EB8</span></p> 	
- <p class="inline-container">Hover link colour<span class="colour-rect" style="--colour: #7C2855; --txt_clr: white">#7C2855</span></p> 
- <p class="inline-container">Visited link colour<span class="colour-rect" style="--colour: #330072; --txt_clr: white">#330072</span></p> 
- <p class="inline-container">Active link colour<span class="colour-rect" style="--colour: #002F5C; --txt_clr: white">#002F5C</span></p>     

### Border 
	
- <p class="inline-container">Border colour<span class="colour-rect" style="--colour: #D8DDE0; --txt_clr: white">#D8DDE0</span></p>    
- <p class="inline-container">Form border colour<span class="colour-rect" style="--colour: #4C6272; --txt_clr: white">#4C6272</span></p>  

## Written Content
 
Use plain language. Research has shown that most people prefer to read plain English, and that the more specialist a person's knowledge is, the greater their preference. 

Our content is factual, neutral and unambiguous. We do not use metaphors - we say what we mean.

- spell out abbreviations and acronyms when first used
- don’t use jargon, rather than saying ‘free text’ say ‘notes’
- use short sentences - up to 20 words, and short paragraphs - up to 3 sentences
- write descriptive headings and subheadings 
- do not assume our audience will be familiar with the topic 

### When to use Capital letters
- use “Sentence case” for headings (capital letter at the start of the sentence only, except for proper nouns e.g. names, company names)
- use “Title case” for the names of organisations, training programmes, schemes, and specialties (Capital letters for each word in a title)

### Tone of voice
- use the active voice - "Book an operating theatre" rather than "an operating theatre can be booked" 
- there’s usually no need to say "please" or "please note"
- there’s usually no need to say thank you
- say "sorry" if something serious has gone wrong - for example, the service has stopped working completely

## Numbers, dates and time
- we use numerals for numbers (including 1 and 2)
- for numbers over 999, use a comma for clarity (for example, 1,000)
- always start with zero for values less than 1 (for example: 0.75 not .75)
- ensure negative values are indicated by a minus sign (for example: -65)
- we spell out "one" when it means "a" or to avoid repeating a word

### Dates 
- always use UK format for dates, do not use American format
- use this format for dates: 6 August 2018
- if you need to include the day of the week, use this format: Wednesday 6 August 2018
- short dates should be formatted DD-Mmm-YYYY: 6-Aug-2018 

### Time 
- check what time format the users and Trust use, but it's likely to be 24 hour clock
- "6 hours 30 minutes", not "6.5hrs" 

### Other numbers
- when showing the age of a patient it is important to be accurate and express the age in years and months not decimals

### Typography
- do not use italics or underlining (except for links, which are underlined by default). Use bold sparingly.  
- do not use bold to emphasise text, instead use front-loaded sentences, headers, or bullet points 

## Links and buttons 
- when placing links in body text, hyperlink the title of the content only 
- do not hyperlink the verb, the preceding article (the, a, our and so on) or the punctuation after the anchor text 
- make your link descriptive and clear. Tell users where the link will take them 
- do not hyperlink headings or subheadings 
- use meaningful links, do not say “click here” 
- if a link opens in a new screen, say “opens in a new window”
- do not use "raw" or "naked" URLs. These will be read out in full by screen readers
- links should open in the same window, unless 
    - You are providing help information, and you don’t want to take the user away from the process they are in 
    - The user is on a login screen when you don’t want to take them away from the login process. In these situations, “opens in a new window” needs to be included in the link text. 

## Tool Tips
- the tooltip must be usable with both keyboards and screen readers
- where possible, ensure that the tool tip does not obscure what the user is focused on

## Images 
### Informative images
- do not use text in images 
- provide alt-text when images convey meaning or information.
- keep alt-text to around 125 characters or 2 sentences 
- if there's important information that you cannot fit in 125 characters (for example, you're describing a complex chart), include this information in the alt-text or consider linking to more information for screen reader users. 

### Decorative images 
- avoid them in data products unless they convey useful information
- if an image is decorative, give it a null text alternative like this: (alt="") 

### Product tiles and other large buttons
- if there is a need to add an image to a large button or "tile", ensure that it is a copyright free image that is meaningful to users, and not a screengrab of a product page

## Data Visualisations 
- every chart or other visualization must have a title. This benefits all users, and particularly those using a screen-reader. [type size medium]
- keep axis titles as short as possible [type size medium]
- category names on a chart axis or in a legend should be clear and concise [type size medium]
- for data from two or more time periods, put the older values before the newer values
- always include some written explanation for the chart and an accompanying table for those who cannot use the data visualisation
- include a source so that a user can track back to the original data

### Chart colours 
We recommend to stick to no more than 6 different variables (colours or tints) on a graph or other chart type, otherwise your visualisation will be confusing. If you need to plot more than 6 variables, you should consider alternative ways to visualise this information.

Use the colours listed below, which have been tested for accessibility, in this order:

- <p class="inline-container">Dark Blue<span class="colour-rect" style="--colour: #12436D; --txt_clr: white">#12436D</span></p> 	
- <p class="inline-container">Turquoise<span class="colour-rect" style="--colour: #28A197; --txt_clr: white">#28A197</span></p> 
- <p class="inline-container">Dark Pink<span class="colour-rect" style="--colour: #801650; --txt_clr: white">#801650</span></p>
- <p class="inline-container">Orange<span class="colour-rect" style="--colour: #F46A25; --txt_clr: white">#F46A25</span></p> 	
- <p class="inline-container">Dark Grey<span class="colour-rect" style="--colour: #3D3D3D; --txt_clr: white">#3D3D3D</span></p> 
- <p class="inline-container">Light Purple<span class="colour-rect" style="--colour: #A285D1; --txt_clr: white">#A285D1</span></p> 

### Gridlines 
- most chart types should have gridlines on at least one axis 
- all numeric axes, except for those showing time or bands of values, should have gridlines 
- time axes should have tick marks, but not gridlines 
- axes showing discrete categories should not have tick marks or gridlines 
- the line at the zero point on your axis should have more emphasis than standard gridlines 
- gridlines should be at sensible, round-number, intervals 
- gridlines should always be labelled with the value they represent 

## Templates and Widgets
In future versions of this guide, there will be guidance here on use of widgets and templates in Workshop, and where possible, direct links to the templates. We will also include annotated images of available templates to make them easier to work with. 

The templates, widgets and code will be accessed in Foundry as usual

## Further information
#### Accessibility
- <a href="https://www.w3.org/mission/accessibility/">W3C accessibility pages</a>

- <a href="https://service-manual.nhs.uk/accessibility">NHS Design guide accessibility pages</a>

#### Data visualisation
- <a href="https://analysisfunction.civilservice.gov.uk/policy-store/data-visualisation-colours-in-charts/">ONS and Civil Service research based data visualisation guidance</a>

#### Content design
- <a href="https://service-manual.nhs.uk/content">NHS Content Design guide</a>
