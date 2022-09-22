# CSS Demo: Semantic Refactoring

# Purpose 
The purpose of this challenge is to get familiar with HTML, CSS, and Git. In the process, code refactoring is done on both the HTML and CSS files to clearly
introduce semantic as well as give a more clear skeleton of the architecture of the HTML. To that extent, I viewed the page in the following way from top down:

1. The wildcard character (*) and body CSS selectors affect the page the most. The base padding, margin, box-sizing, and background color of the page are determined here.
2. The next semantic section would be the header section. Within this section, there are the following components:
  - header-title
  - nav bar
    - unordered list of links
      - Search Engine Optimization
      - Online Reputation Management
      - Social Media Marketing 
3. Image 
4. Main section
  - Reasons section
    - Visually on the left portion of the top of the main content section, there are three cards each detailing more about the reasons to consider the fictional Horiseon services:
      - Search Engine Optimization card (text and image)
      - Online Reputation Management card (text and image)
      - Social Media Marketing card (text and image)
  - Benefits section
    - Visually on the right portion of the top of the main content section, there are three benefits stacked vertically on top of each other:
      - Lead Generation benefit (image and text)
      - Brand Awareness benefit (image and text)
      - Cost Management benefit (image and text)
5. Footer section
  
# Takeaway
Overall, I think this challenge helped me to abstractly think of the HTML in an architecture from a top down perspective. After refactoring the HTML to partitions and sections that made logical sense to me, I then worked on the CSS portion; there I refactored CSS tag and selectors to keep the original styling of the page intact with more clear and succint rules. This included recognizing patterns of reused styles as well as lifting styles that can be more generalized to higher level parent components. 

    