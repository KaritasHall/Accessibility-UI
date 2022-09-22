# Accessibility-UI

I started off by using the appropriate html semantics to make sure that the page had logical structure and all sections had accessible names.
I then added aria labels and other descriptive tags to elements to make sure they were readable by screen readers.
In the css I used :focus to put a focus state on interactive elements.
I chose to use Arial as my font as it is considered among the most readable fonts (Acoording to this source: https://www.siteimprove.com/glossary/accessible-fonts/).
The general text is 16pt, clickable elements are 18pt and h1 is the standard 1,5em.

I used Lighthouse to check for contrast issues and such, and I used ChromeVox screen reader to help me get the readability I wanted.

I found that I didn't have to over rely on specific aria labels when using the proper html semantics and taking care to make names accessible. Overall it was
a lot simpler process than I thought, but I learned a lot!
