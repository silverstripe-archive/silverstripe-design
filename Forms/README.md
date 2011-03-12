# SilverStripe HTML Form Templates

This folder contains the new form html and css styles for the core sapphire form
library. 

The purpose of this library is to provide a minimal set of styles (enough for
most sites) and allow developers which need more flexibility, to customize the 
form templates as much as they wish.

## Compiling SASS Files

The core form library uses scss for it's styles but in the final result will link
to the compiled css. To work on the css you need to make your changes to the
scss files then 'watch' the project.

### Install Compass

	# install compass
	gem install compass
	
### Compile CSS

	# set compass up to 'watch' this folder
	compass watch ./
