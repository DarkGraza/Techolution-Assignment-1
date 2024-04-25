# Techolution-Assignment-1
Associate Python Developer Role Assignment

Packages Utilized - requests, BeautifulSoup


First we inspected the website home page using chrome dev tools and found out links to the steps of the installation guide.
We retreived responses from the url requests and collected all html href tags with the links and parsed them into a list.


# Main Program

We have 3 user defined functions in the loop for various purposes as following:
  1) h_tags() for traversing heading and subheading tags
  2) code_parse() for checking whether the code block is present on the page
  3) store() is utilised to store necessary data in variables as a list from time to time as


We looped through all links to get responses from each page separately.

Upon examination of each web page, we found out that each page is divided in sections and some sections have further subsections.

The program goes through each section and checks which kind of <h> tag is present in it. If it consists of h2 then it searches for further subsections and calls h_tags to extract the heading and subheading values if it doesn't consists of h2 then it calls for code_parse to check whether there are code blocks.

While looping through sections if it encounters h1 tag then it simply calls store() and code_parse(), then writes h1 content as Heading.

Finally, the Program ends with writing parsed data from each page into separate csv files


