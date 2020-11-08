# Plant Page - the Static Version

## About

I created this app to practice my web development skills, with my focus for this project being to improve my design skills, gain more experience with a rigorous, time-based development process, and to practice making a solid 'Minimum Viable Product' as a precursor to making a more fully fledged CRUD web application.

This project is incomplete/flawed and will still require more work before I move on to developing the enhanced CRUD app.

This Project will NOT be 'perfect' (or as perfect as I would like) before I move on to creating the enhanced version. This project is a prototype, a proof of concept, a stepping stone on the path of developing the final product.

I will be keeping this static page while developing the dynamic version. The dynamic version will be created in a seperate repository, this repository will be kept to show progress/differences in development. When the dynamic version is created a link will be given here. This page may or may not recieve updates after development of the dynamic version begins. 

## File Structure

The file structure for this project is fairly straightforward, it consist of:
- the index file, contains the HTML structure of the page
- the styles directory, containing any .css files for the page
- the scripts directory, containing any .js files for the page
- the imgs directory, containing imgs for the plants and the background iamges for the page
- the mockup directory, containing a .epgz (evolus pencil compressed document) file for editing/viewing in Evlous' Pencil program, and .png files exported from the program for each mockup page created, in this case a proposed mobile and desktop view of the page

## TODO

### Style Improvements
- [ ] Clean Up and condense CSS - it is a hot mess at the moment
	- [ ] improve selectors - must be best readable version, and must be aware of specificity requirements for rules to overload other rules
	- [ ] Half the tags were made into flexboxs while trying to align things properly, many are obsolete/unneccesary
- [ ] Test responsiveness more thoroughly
- [ ] Adjust font size, heading sizes for mobile display of site
- [ ] ? - Use mixins/includes to make CSS more readable/easier to style new/similar content? (never used before)

### HTML Structure Improvements
- [ ] Make file structure follow 'rules' better, will help with styling complexity
	- [ ] page sections could be structured more similarly to allow for one set of rules for all, instead of each section needing some specific rules created
- [ ] Move js functions into a seperate javascript file - seperate page structure from functionality

### More To Come
- [ ] Likely many things I haven't noticed, or future problems I create while solving the above