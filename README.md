Udacity Udagram Image Filter Project for Cloud Developer nanodegree.

<<<<<<< HEAD
This project was deploy on AWS Elasticbeanstalk with the help of EB CLI and IAM Policies. 
Image URL is passed as a query paramter into the url and the path of the filtered .jpg file is returned.

An example of how the query paramter is passed is shown below:
https://{{HOST}}//filteredimage?image_url="https://www.planetware.com/)..."
where the {{HOST}} is the server instance endpoint and the content in the quotation mark is replaced with the url path of the image you want to filter eg "https://media.istockphoto.com/photos/male-lion-resting-on-a-rock-picture-id1333977253?b=1&k=20&m=1333977253&s=170667a&w=0&h=q_EqYl_GqFCR1XmF_AK91YRFDapwAClOoc2fZbsnmr4="

=======
Github Link:
https://github.com/Adewale-D-A/Udagram-Image-Filter-Project-2

Endpoint for Running EB instance: 
http://udagram-project2-cloud-dev-nanodegree.us-east-1.elasticbeanstalk.com/

BRIEF DESCRIPTION:
This project was deploy on AWS Elasticbeanstalk with the help of EB CLI and IAM Policies. 
Image URL is passed as a query paramter into the url and the path of the filtered .jpg file is returned.

An example of how the query paramter is passed is shown below:
https://{{HOST}}//filteredimage?image_url="https://www.planetware.com/)..."
where the {{HOST}} is the server instance endpoint which is http://udagram-project2-cloud-dev-nanodegree.us-east-1.elasticbeanstalk.com/ and the content in the quotation mark is replaced with the url path of the image you want to filter eg "https://media.istockphoto.com/photos/male-lion-resting-on-a-rock-picture-id1333977253?b=1&k=20&m=1333977253&s=170667a&w=0&h=q_EqYl_GqFCR1XmF_AK91YRFDapwAClOoc2fZbsnmr4="

>>>>>>> 293b447e2f979c41c81664009ee844ff5fc76f28
If the url passed doesn't return the path of the filtered image in less than 1min, then the url passed is broken or not correct.
