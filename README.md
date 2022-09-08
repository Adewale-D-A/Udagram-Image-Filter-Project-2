# Udacity Udagram Image Filter Project 2 for Cloud Developer nanodegree.

**_Github Link:_**
* https://github.com/Adewale-D-A/Udagram-Image-Filter-Project-2

**_Endpoint for Running EB instance:_** 
* http://udagram-project2-cloud-dev-nanodegree.us-east-1.elasticbeanstalk.com/

### BRIEF DESCRIPTION:
This project was deploy on AWS Elasticbeanstalk with the help of EB CLI and IAM Policies. 
Image URL is passed as a query paramter into the url and the filtered image is displayed.

> An example of how the query paramter is passed is shown below:
> https://{{HOST}}//filteredimage?image_url="https://www.planetware.com/)..."
> where the {{HOST}} is the server instance endpoint which is http://udagram-project2-cloud-dev-nanodegree.us-east-1.elasticbeanstalk.com/ and the content in the quotation mark is replaced with the url path of the image you want to filter eg "https://media.istockphoto.com/photos/male-lion-resting-on-a-rock-picture-id1333977253?b=1&k=20&m=1333977253&s=170667a&w=0&h=q_EqYl_GqFCR1XmF_AK91YRFDapwAClOoc2fZbsnmr4="

