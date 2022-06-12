Udacity Udagram Image Filter Project for Cloud Developer nanodegree.

This project was deploy on AWS Elasticbeanstalk with the help of EB CLI and IAM Policies. 
Image URL is passed as a query paramter into the url and the path of the filtered .jpg file is returned.

An example of how the query paramter is passed is shown below:
https://{{HOST}}//filteredimage?image_url="https://www.planetware.com/)..."
where the {{HOST}} is the server instance endpoint and the content in the quotation mark is replaced with the url path of the image you want to filter eg "https://media.istockphoto.com/photos/male-lion-resting-on-a-rock-picture-id1333977253?b=1&k=20&m=1333977253&s=170667a&w=0&h=q_EqYl_GqFCR1XmF_AK91YRFDapwAClOoc2fZbsnmr4="

If the url passed doesn't return the path of the filtered image in less than 1min, then the url passed is broken or not correct.
