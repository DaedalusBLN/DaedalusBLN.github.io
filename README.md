## DaedalusBLN Kodi Repository

This unofficial Kodi add-ons repository is based on [drinfernoo](https://github.com/drinfernoo)'s **repository.example** template and the [Add-on zips/Repo XML Generator](https://github.com/drinfernoo/repository.example/blob/master/_repo_xml_generator.py) python script.

To automate the process of updating/adding to the repo even further and eliminate the continuous need of access to a personal computer, I have setup a continuous integration configuration script for [Travis-CI](https://travis-ci.com) that runs the xml/zip generator python script on a virtual machine in the cloud each time I push a commit of a new or updated unzipped add-on folder to the root directory of this repository and makes and pushes another followup commit with the generated/updated contents of the _zips_ folder.

Feel free to look around or open an issue to ask me how you can do it too, it's simpler than you think.

Have fun with the add-ons!

_Daedalus_
