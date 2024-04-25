# Techolution-Assignment-1
Associate Python Developer Role Assignment

Packages Utilized - requests, BeautifulSoup


First we inspected the website home page using chrome dev tools and found out links to the steps of the installation guide.
We retreived responses from the url requests and collected all html href tags with the links and parsed them into a list.


# Main Program

We looped through all links to get responses from each page separately.
Upon examination of each web page, we found out that each page is divided in sections and some sections have further subsections.



We have 3 user defined functions in the loop for various purposes as following:
  1) h_tags() for traversing heading and subheading tags
  2) code_parse() for checking whether the code block is present on the page
  3) store() is utilised to store necessary data in variables as a list from time to time as



The Program ends with writing parsed data from each page into separate csv files


