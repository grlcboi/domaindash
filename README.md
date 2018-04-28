# domaindash
Domain management dashboard:

* Pulls registration data from WHOIS
* Pulls certificate information from certificate
* Pulls DNS health from MXToolbox API

Currently builds a database in RAM on demand and is slow

TODO:
* Implement database backend (Postgresql or Redis w/ Sentinel)
* Dynamic URLs (Flask url_for)
* Dockerize
