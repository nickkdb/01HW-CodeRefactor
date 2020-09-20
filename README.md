I made many changes to this file to refactor this html. These changes include:

1. Giving the page the title "horiseon social solutions" within the <title> tag

2. Added missing id classification to line 29, missing id was causing html to not pick up commands from css thus "search engine optimization" button wasn't functioning

3. Added missing alt attributes to the images on line 30, 37, 44, 54, 61, and 68

4. Originally, lines 52, 59, and 66 were assigned to different classes but all were using the same css styling, making three indentical copies of the same code. Added them all to the "benefits-style" class instead, this allowed me to condense the styles applied to the entire class, the h3 tags, and the images into one bracket of code each

5. created the "description" class, which allowed me to combine classes "search-engine-optimization", "online-reputation-management", and "social-media-marketing" into one class. The styles applied to their entire class, h2 tags, and images were condensed as well

6. changed a div tag put into the class "footer" to a <footer> tag, therefore changing the css from .footer { to footer {



# 01HW-CodeRefactor