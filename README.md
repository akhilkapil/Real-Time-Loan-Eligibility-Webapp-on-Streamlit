# Real Time Loan Eligibility Prediction with ML 


In this repository I have developed an real time API to score model in real time using. For this I have hosted the app using two different ways: 
<br/>
- Flask
- Streamlit
   

<br/>
<b>Why Real time ?</b> <br/>
Because it enables your model
to be embedded in a web browser so as to get predictions and take action based on
predictions.<br/>
This is useful for making online recommendations, checking credit card approval status, and so on. The application is enormous, and it becomes easier to manage such APIs using Docker.

Still, for this project  I have used historical bank data which shows wether a customer is eligible for the loan or not based on certain features.


## Technologies Used:



1: <div style="float: left;"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Apache_Spark_logo.svg/1280px-Apache_Spark_logo.svg.png" width="15" height="15
"/></div> <br/>
- Used Pysaprk for its capability to process large amounts of data. 
- Trained model with RandomForstClassifer for predictions.

  
2: Flask <div style="float: left;"><img src="https://static.javatpoint.com/tutorial/flask/images/flask-tutorial.png" width="" height="30
"/></div> <br/>
- Used Flask to implement model in real time.
- At first I wanted to test weather the app was running successfuly or not, thats why I used flask to evaluate it.

3: Docker <div style="float: left;"><img src="https://blog.knoldus.com/wp-content/uploads/2017/12/docker_facebook_share.png" width="60" height="50
"/></div> <br/>
- Deployed the whole source code along with primiary files to the Docker. <br/>
- Docker-based deployment is useful
in a lot of ways when compared to a traditional scoring method, like spark-submit.


4: Streamlit <div style="float: left;"><img src="https://assets.website-files.com/5dc3b47ddc6c0c2a1af74ad0/5e181830b827fae3a2541766_RGB_Logo_Vertical_Color_Dark_Bg.png" width="70" height="50
"/></div> <br/>
- Build the user interface using Streamlit.
- One of the advantages of streamlit is streamlit is that you can edit the Python code and see live changes in the web app
instantly

## Implementation


To run this app on Flask:<br/>

    `dasdasdasdad`
