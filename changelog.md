#Change Log

Team membership:  Alex Xia (Captain) & Luke Lee (First Mate)  
Team conventions: Allman notation, markdown for changelog  
Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

## [0.0.3] - 2018-01-26
### Added
- created a new database named 'picassos' using phpMyadmin and imported setup/images.sql into that database
- added an Images.php in application/models/ which pull images data from db
- added a \_cell.php in views/ for internal use, to display table cell for holding images

### Changed
- modified config/database.php to allow connection to the 'picassos' database
- modified config/autoload.php to preload db driver
- added database.php to .gitignore for now for password security
- the original HTML welcome.php and gallery.php in views/ replaced with a variable parameter 
- Welcome.php and Gallery.php controllers now pull data from Images model and uses Table library to generate HTML


## [0.0.2] - 2018-01-25
### Added
- template.php holds redundant code from about, gallery, and welcome.php views

### Changed
- MY_Controller now works, and populates page title and content
- Welcome.php, About.php, Gallery.php controllers now pull data from views


## [0.0.1] - 2018-01-25
### Added
- CodeIgniter starter folders to project folder
- new views welcome.php, about.php, gallery.php
- new controllers Welcome.php, About.php, Gallery.php


## [0.0.0] - 2018-01-25
### Added
- Develop branch

### Changed
- Changelog updated
