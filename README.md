# IRIDA IslandViewer Pipeline Plugin

This project contains the <a href="http://www.pathogenomics.sfu.ca/islandviewer/">IslandViewer</a> genomic island prediction pipeline implemented as a plugin for the <a href="http:/www.irida.ca">IRIDA</a> bioinformatics analysis system. 



This code is based on the update-example branch of the <a href="https://github.com/phac-nml/irida-plugin-example">irida-example-plugin</a> at the National Microbiology Laboratory
 <a href="https://github.com/phac-nml">GitHub</a> page. If you are interested in using a template for implementing your own pipelines within IRIDA,  please visit the Example Plugin page or view the pipeline documentation at <https://irida.corefacility.ca/documentation/developer/tools/pipelines/> for more details.

If you are interested in using this pipeline in your IRIDA installation, copy the latest islandviewerclient-plugin-\<VERSION\>.jar release to /etc/irida/plugins/ and restart both tomcat and the galaxy server.