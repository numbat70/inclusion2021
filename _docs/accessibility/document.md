---
title: Creating documents
category: Accessibility
order: 5
---

## Quick access
- [PDF are not recommended](#pdf-are-not-recommended)
- [Tips to make your documents accessible](#tips-to-make-your-documents-accessible)
  - [Language and content ](#language-and-content)
  - [Headings and structure](#headings-and-structure)
  - [Colours and contrast](#colours-and-contrast)
  - [Alternative (alt) text](#alternative-alt-text)
  - [Links](#links)
  - [Checking a Word document for accessibility](#checking-a-word-document-for-accessibility)
  - [Checking a PDF for accessibility](#checking-a-pdf-for-accessibility)
  - [Using tables](#using-tables)
  - [Graphs and charts](#graphs-and-charts)
  - [Making complex documents accessible](#making-complex-documents-accessible)
  - [Simplifying a complex document](#simplifying-a-complex-document)
- [Easy Read version](#easy-read-version)
- [Large print](#large-print)
- [Try a screen reader for yourself](#try-a-screen-reader-for-yourself) 
- [Media files](#media-files)
- [Further reading](#further-reading)

<hr class="big">

## Summary of the main recommendations:

<blockquote class="info">
  <ul>
    <li>avoid using PDF when sharing a text document</li>
    <li>use simple language and avoid jargon</li>
    <li>explain acronyms the first time you use them</li>
    <li>avoid writing in block capitals</li>
    <li>align your text on the left</li>
    <li>people might not see colours, make sure your document still make sense without them</li>
    <li>the colour of your text should be contrasted enough against the background colour</li>
    <li>structure the document logically and use properly marked headings</li>
    <li>add alt text to your pictures and diagrams</li>
    <li>make sure your video is captioned correctly</li>
    <li>provide a transcript for your media files where possible</li>
    <li>use automatic checkers from Word and Adobe</li>
  </ul>
</blockquote>

<hr class="big">

## PDF are not recommended

We generally recommend avoiding publishing PDFs and other documents online wherever possible. It’s usually more effective and accessible to repurpose the same content into a HTML webpage.  

**The problems with PDF**
- They do not change size to fit the browser
- They’re not designed for reading on screens
- It’s harder to track their use
- They cause difficulties for navigation and orientation
- They can be hard for some users to access
- They’re less likely to be kept up to date
- They’re hard to reuse

Source: <a href="https://gds.blog.gov.uk/2018/07/16/why-gov-uk-content-should-be-published-in-html-and-not-pdf" target="_blank">Why GOV.UK content should be published in HTML and not PDF</a>

However, there may be situations where we can’t avoid publishing a document online or sharing it directly with a customer – for example, when sending funding applicants an offer letter or contract. We also regularly share documents with colleagues to share information or collaborate. It’s important that all our documents are accessible, whether they're being shared internally or externally.  

> Whenever you prepare a document, you should assume that some people reading it might:  
> - Not see colours or not see them well   
> - Need to magnify the document  
> - Be using a screen reader   
> - Have low literacy or speak English as a second language 
> - Find it difficult to read or understand large amounts of text  

<a href="#" class="button">Back to top</a>

<hr class="big">

## Tips to make your documents accessible  

### Language and content 

**Write in clear, simple English with no jargon**. Make sure you explain any acronyms or technical terms you use for those who might not be familiar with them – for example, customers, colleagues outside your team, or new starts. There are tools to check the level of readability of your text like <a href="http://www.hemingwayapp.com" target="_blank">the Hemingway App</a>

**Avoid writing in block capitals**. These are harder to read for people with low vision or dyslexia and might be read letter by letter when soemone use a screen reader.

**Make sure your content is left aligned**. Avoid justifying your text as this can cause irregular spacing which can be confusing for some users.  


<hr class="small">

### Headings and structure 

Structure the document logically and use headings to break it into meaningful sections. Your headings should be simple and descriptive – avoid ‘clever’ headings and puns.  

Headings should also be properly marked as headings – don’t just use large or bold font to signify a heading. This helps screen readers navigate the document. In Microsoft Word, heading styling can be found in ‘Styles’ under the ‘Home’ tab.   

The Microsoft Word toolbar, showing the functionality to mark text as Heading 1, Heading 2 and Heading 3 

![screenshot of the part of the menu where you can create headings](/inclusion/accessibility/files/heading-word.PNG)

<hr class="small">

### Colours and contrast 

Avoid using colour alone to signify meaning.  

Make sure the text colour you’re using has a high contrast with the background of the document. Tools such as <a href="https://accessible-colors.com/" target="_blank">'Accessible colors'</a> can help you check.  

Read more about using colours and contrast [Link not ready - but will redirect to the Scottish Enterprise Design System Guidance for this]  

<hr class="small">

### Alternative (alt) text 

If you’re using images in your document that contain important meaning, information or text, make sure you add alt text. This is basically a short written description of the image. This means users who can’t see the image won’t miss out on important information.  

You don’t need to add alt text to decorative images.  

Read more about writing alt text [will redirect to the Scottish Enterprise Design System Guidance for this - not ready yet]  
A <a href="https://axesslab.com/alt-texts" target="_blank">good link to understand more about alt text</a> and how to do a good one. And <a href="https://webaim.org/techniques/alttext" target="_blank">a longer guidance</a>.
A <a href="https://thoughtbot.com/blog/alt-vs-figcaption" target="_blank">blog post when you are unsure between a caption and an alt text</a>


<hr class="small">

### Links 

Make sure you add links as a hyperlink to text within your document. This ‘anchor text’ should give the link context to help the user understand where it’s going – never use ‘click here’.  

#### Example
>
>**Do this**: You’ll find more information about this in our <a href="https://www.scottish-enterprise.com/learning-zone/business-guides" target="_blank">business guides section</a>.  
>
>**Instead of**: You’ll find more information about this here: <a href="https://www.scottish-enterprise.com/learning-zone/business-guides" target="_blank">https://www.scottish-enterprise.com/learning-zone/business-guides</a>
>
>**And instead of**: To find out more, <a href="https://www.scottish-enterprise.com/learning-zone/business-guides" target="_blank">click here</a>.  
>

<hr class="small">

### Checking a Word document for accessibility   

Microsoft Word has a built-in accessibility checker. In the toolbar, you will find the Check Accessibility functionality highlighted in red in the picture below.
- Go to the **Review** tab
- Select **‘Check accessibility’**
- A panel will open on the right of your document
- - This will highlight errors such as missing alt text or low contrast text and help you fix them

![screenshot of the part of the menu where you can find the check accessiblity menu](/inclusion/accessibility/files/access-check-word.png)

Good article about word document: <a href="https://www.abrightclearweb.com/accessible-word-document-checklist" target="_blank">An Accessible Word Document Checklist</a>


<hr class="small">

### Checking a PDF for accessibility  

If you’re using Adobe Reader, go to Edit -> Accessibility -> Quick check. This will flag up any issues. To fix them, you need to edit the original document in Word or Adobe Acrobat Pro.   

> You can also ask the digital team to help.

<hr class="small">

### Using tables 

If you’re using tables, try to keep them simple and avoid merged or split cells.  

<hr class="small">
 
### Graphs and charts 

If you’re sharing graphs and charts, try to provide a written version of the same information as well. This could be in a table or as written descriptions.  
<a href="https://mn.gov/mnit/media/blog/?id=38-436349" target="_blank">Key Considerations for Flowchart Accessibility</a> - Note that this link will ask you to confirm you're not a robot before going to the correct page


<hr class="small">

### Making complex documents accessible  

It’s likely that you’ll sometimes need to create more complex documents than a Word document or PDF. As much as possible, follow the same accessibility guidelines – use simple language, mark headings properly, use good colour contrast and add alt text.  

<hr class="small">
 
### Simplifying a complex document  

We all process and understand information in different ways, and it’s fine to use whatever tools you need to help you work best – for some people this might be visual tools like a flowchart or an online whiteboard tool. However, if you need to share some of this information, consider whether you can simplify it into a more accessible version to share instead of or alongside the visual information.  

A simple flowchart could be written out in steps. An organisation chart can be broken down using bullets and sub bullets. All the notes and comments left in an interactive space could be summarised in a word document or simple table.  

<a href="#" class="button">Back to top</a>

<hr class="big">

## Easy read version

The easy read format was created to help people with learning disabilities understand information easily.

Easy read is often also preferred by readers without learning disabilities, as it gives the essential information on a topic without a lot of background information. It can be especially helpful for people who are not fluent in English. (Source: <a href="https://www.gov.uk/government/publications/inclusive-communication/accessible-communication-formats#easy-read-and-makaton" target="_blank">GOV.UK - Accessible communication formats</a>)

<hr class="small">

### Resources:
- <a href="http://www.saifscotland.org.uk/information-and-advice/brief-guide-easy-read-documents/brief-guide-easy-read-top-tips/#sthash.P6BlvNot.HPTHxyK3.dpbs" target="_blank">A Brief Guide to Easy Read: Top Tips</a> from SAIF (Scottish Accessible Information Forum)
- <a href="https://accessibility.blog.gov.uk/2019/10/11/how-dwp-used-the-easy-read-format-to-make-its-content-more-accessible" target="_blank">GOVUK Blog post: How DWP used the easy read format to make its content more accessible</a>

#### Examples of Easy read format:
- <a href="https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/944658/introduction-to-universal-credit-easy-read-guide.pdf" target="_blank">Introduction to Universal Credit</a> - PDF
- <a href="https://www.gov.uk/government/publications/easy-read-get-help-at-work-if-youre-disabled-or-have-a-health-condition-access-to-work/get-help-from-access-to-work-easy-read" target="_blank">Get help from Access to Work: easy read</a> by the DWP
- <a href="https://www.lead.org.uk/online-safety-booklet-easy-read" target="_blank">Online Safety Booklet- Easy Read</a> by Lead Scotland

<a href="#" class="button">Back to top</a>

<hr class="big">

## Large print

Large print publications are documents with a point size of 16 and above.

Large print versions of publications are essential for some disabled people, for example people with visual impairments, learning disabilities, dyslexia and problems with coordination or manual dexterity. (Source: <a href="https://www.gov.uk/government/publications/inclusive-communication/accessible-communication-formats#large-print" target="_blank">GOV.UK - Accessible communication formats</a>)

- A minimum size of 16 point is recommended for people with a visual impairment
- Some fonts appear larger than others at the same point size
- Very large type sizes can be counter-productive because they cause publications to become bulky and difficult to navigate
- Offering alternative formats – for example, providing an audio version of the information or emailing someone a text document so that they can access the information using a screen reader on their computer
- Allow 50 to 65 characters, including spaces, per line
- Consider reducing the amount of text before reducing the point size

> If you are producing information in large print for an individual, ask which size best suits their needs. They might also benefit from specific colours and contrast between the text and the background, so do ask.

<a href="#" class="button">Back to top</a>

<hr class="big">

## Try a screen reader for yourself   

To test how your documents would work with a screen reader, you can download one yourself and try it out. We’d recommend <a href="https://www.nvaccess.org" target="_blank">Non-Visual Desktop Access (NVDA)</a>. 

 
 <hr class="big">

## Media files

You need to provide an alternative for people who can’t hear or see.

Videos with audio require captions synchronised with the audio track. Everything said in the video should be included in the captions. It should  include names, sounds and descriptions.

<p style="margin-bottom: 0"><strong>2 types of captions:</strong></p>
- **Open caption**: is embedded into the video itself, and cannot be turned off
- **Closed captioning**: can be turned on and off

**Auto-generated captions** are better than nothing but usually not great: Often inaccurate, especially if the speaker has an accent or when captioning names (people, brand, places etc…)

This will also be used by many people who are not native speakers, or are in a noisy environment or don’t want others to hear what they are watching for example.

<p style="margin-bottom: 0">Ideally, <strong>provide a transcript</strong> of your media, so people can either read it or use a screen reader to hear it:</p>
- allow people to scan the content and see if they want to engage with it 
- can be searched by people and search engines so better for SEO (Search Engine Optimisation)
- this is the only way a deafblind person can engage with your content


<p style="margin-bottom: 0"><strong>Audio descriptions</strong> speak out what is happening in the video so that it’s accessible to people with low vision. There are two ways to create audio descriptions:</p>
1. a narrator describes all the visual information
2. add a separate audio track that describes the visual information

<a href="#" class="button">Back to top</a>

<hr class="big">

## Further reading: 
- <a href="https://www.gov.uk/government/publications/inclusive-communication/accessible-communication-formats" target="_blank">GOV.UK - Accessible communication formats</a>
- <a href="https://www.abrightclearweb.com/accessible-word-document-checklist" target="_blank">An Accessible Word Document Checklist</a>
- <a href="https://www.gov.uk/guidance/how-to-publish-on-gov-uk/accessible-pdfs" target="_blank">How to publish on GOV.UK - Document accessiblity</a>
- <a href="https://www.w3.org/WAI/teach-advocate/accessible-presentations" target="_blank">How to Make Your Presentations Accessible to All</a> - W3C resource
- <a href="https://www.worcestershire.gov.uk/sculpt" target="_blank">SCULPT - Shaping your documents and content for accessible and inclusive practice</a> - Great resource from the Worcestershire county council
- <a href="https://readabilityguidelines.co.uk/audiences-devices-channels/presentations" target="_blank">Presentations - Readability Guidelines</a> - by Content Design London
- <a href="https://support.microsoft.com/en-gb/office/make-your-powerpoint-presentations-accessible-to-people-with-disabilities-6f7772b2-2f33-4bd2-8ca7-dae3b2b3ef25?ui=en-us&rs=en-gb&ad=gb" target="_blank">Make your PowerPoint presentations accessible to people with disabilities</a> - Microsoft support

{% include feedback.html %}
<br>
<a href="#" class="button">Back to top</a>

<div>Last updated: {{site.time | date_to_string}}</div>

<!-- 
<a href="" target="_blank"></a>
<p style="margin-bottom: 0">
-->
