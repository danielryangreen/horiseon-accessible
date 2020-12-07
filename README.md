# Horiseon Webpage - Refactor for Accessibility
## Description
Refactored an existing webpage to make it accessible. Changed the div tags to semantic HTML. Added a title element for the page and alt attributes for all images.

I noticed that the page did not display well at screen widths less than 1152px, so I added a fixed width to the body. The hero photo at the top of the page was entered as a background image in the CSS stylesheet. Since the photo no longer needed to scale with the page, I moved it to an img tag in the HTML and added an alt attribute to make it more accessible. Previously the hero photo had a fixed height of 800px. I removed the height rule so it would not stretch the image. It now displays at a fixed size of 1152 x 768.

Deployed at [GitHub Pages](https://danielryangreen.github.io/horiseon-accessible/)
## Installation
Open __index.html__ in your favorite modern browser!

View the code in your favorite text editor. I suggest VS Code.
## Usage
Here is a mock-up of the original webpage.

![Horiseon webpage](assets/images/01-html-css-git-homework-demo.png)
## Credits
Starter code and images provided by [Trilogy Education Services](https://www.trilogyed.com/)
## License
MIT License

Copyright (c) 2020 Daniel Ryan Green

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.