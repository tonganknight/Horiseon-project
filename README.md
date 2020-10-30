This repository contains the changes I have made to Horizon’s website. 
The main purposes of these changes is to add accessibility standards to the codebase that was provided, and optimized the site for search engines 

I have made the following changes to add accessibility standards to the provided code 
---------------------------------------------------------------------------------------
Line 7  I changed the title from “website” to Horiseon to be more discriptive
  
Line 30   image representing Search Engine Optimization. Since this is an informative image, I added a “Alt” explaining the image. This will add accessibility, and will aid screen readers for the visually impaired. I added the following text. 
“A sketch in a notebook with a small cloud containing the letters SEO. It is surrounded by several smaller sketches representing concepts on the internet that can be found by a Search Engine. “

Line 37  image representing Online Reputation Management. Since this is an informative image, I added a “Alt” explaining the image. This will add accessibility, and will aid screen readers for the visually impaired. I added the following text.“A man on a lap top. He is using his phone. On the laptop screen it shows a large heading labeled reputation. Below are several graphs. The largest graph in the center is a bar graph. It shows a gradual increase over time. It is accompanied by an arrow over the top of it signifying an increase.” 

Line 44  image representing Social Media Marketing Since this is an informative image, I added a “Alt” explaining the image. This will add accessibility, and will aid screen readers for the visually impaired. I added the following text.
“A large group of people at a business table. They are holding laptops, phones, and tablets. On the table there are several paper cut outs scattered around. Each cut out contains a word or a graphic. They representing elements of social media such as tweet, like, Media, share. Some of them contain common media icons such as a phone, camera, music note.”

Line 54 <img> icon representing Lead Generation Since this is an informative image, I added a “Alt” explaining the image. This will add accessibility, and will aid screen readers for the visually impaired. I added the following text.
“the icon shows a gear cog moving into a funnel emerging as a dollar sign.”

Line 61 <img> icon representing Brand awareness Since this is an informative image, I added a “Alt” explaining the image. This will add accessibility, and will aid screen readers for the visually impaired. I added the following text.
“The icon shows a light bulb emanating lighting up. The light bulb sits on top of a shirt and tie signifying the idea of a business man.”

Line 68 <img> icon representing Brand awareness Since this is an informative image, I added a “Alt” explaining the image. This will add accessibility, and will aid screen readers for the visually impaired. I added the following text.“The icon shows gear cog behind several money signs.”

--------------------------------------------------------------------------------------
I have made the following changes to code to remove redundancies to aid with better navigation and functionality of the web page. 
---------------------------------------------------------------------------------------------------------------------------------

Line 68 I removed  "im" tags they do not need closing tags.

I changed the title element in header to be more descriptive 

I removed the footer content to better reflect the mock image I was given

CSS changes and reorganization   
------------------------------------------------------------------------------------------------------------------------------------
Changed paragraph size from 16px to 20px to align with mock photo also added max width attribute of 600px

Added benefits paragraph to seperate paragraph styles for each section

Added search-engine-optimization span to move "optimize" below the other element

Added online-reputation-management span display block to move the element down

Consolidated img for seo and orm and smm to clear redundances  added width 325px

Consolidated h2 for seo and orm and smm a to clear redundances dded font size chage to 40px

Consolidated img, h2, from the content section to clear redundances 

Combine benefit-lead, benefit-brand, benefit-cost to one declaration

Removed footer content to match mock up

Added a utility section for page wide functions

Moved float left and float right declarations to utility section 0riginal line 75 now line 11-19

Moved link and paragraph codes to utility section


