### ORCIDity prototype developed during ORCID Hackathon, Oxford (May 23rd 2013)

This is a first version of the ORCIDity timeline mashup. Users can enter their ORCID iD and are presented with a timeline of their publications, with visual links to the source journal. Additional information including citation data (from ImpactStory.org) is also presented for each publication.

[Live Demo](http://lamp-lbi-24.rcs.le.ac.uk/orcidity)

### API Components
* ORCID public API (retrieving users publications)
* CrossRef API (for lookup of 
* ImpactStory API

### Other Components
* Timeline JS (http://timeline.verite.co/)
* Codeigniter
* Twitter Bootstrap
* jQuery

### Install

You will need to allow apache to access the .htaccess file (and possibly adjust the RewriteBase to suit your directory).

To enable ImpactStory enter your API key in the application/config/orcidity.php file.

MySQL database may need to be created (and the connection settings entered in application/config/database.php). A dump of the database structure is available in resources/sql/orcidity.sql.