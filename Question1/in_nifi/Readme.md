1- get the yml file up and run all images using:
docker-compose up 
2- nifi is exist on local port 8080
on your browser open >> localhost:8080/nifi/
3- to upload the template "CsvToJson"
right click on template icon and drag it to the working space
choose "upload template" >>
select the XML file "CsvToJson"
select "CsvToJson" template
drag and drop template >>
select "TEST1" CsvToJson >>
ADD
5- start the workflow from the operate in left side of the window

6- then your CSV (in_nifi folder) will be converted to JSON file in (out_nifi folder)



