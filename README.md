# IMDB-Movie-Review-Prediction-with-simple-RNN
This program is about Movie Review Predictions based on reviews taken from IMDB. The dataset is downloaded using ```tensorflow.keras.import```. You can find this in the ```simplernn.ipynb``` file. This entire project follows a simple RNN structure and is a basic model for movie review prediction. 
This project should only be used for practice or learning purposes as it is not a very strong model. I uploaded this project here specifically for practicing only. If you intend to use this project or its contents such as the model for purposes other than practice, it is highly likely that you will not get good results. 
If you are looking to get better accuracy and precise answers, you can follow this approach but use a more complex technique instead of simple RNN. 

# Installing Necessary Libraries
If you want to download and try this out, fork the repository or download everything in this repository. In your IDE, it is extremely important that you first run the ```requirements.txt``` file to install all the necessary libraries.

# Virtual Environments
If you want to try this out, I suggest you run everything in a virtual environment to avoid conflicts between versions and file paths.

Refer to [Python documentation](https://docs.python.org/3.12/library/venv.html) for more information about virtual environments.

To create a virtual environment, go to your project’s directory and run the following command:  
```
 python3 -m venv .venv
```
This will create a new virtual environment in a local folder named ```.venv```

Activate your virtual environment using: 
```
 source .venv/bin/activate
```

To deactivate a virtual environment, simply type ```deactivate``` and your virtual environment should be deactivated.
```
 deactivate 
```



This program is also deployed on Streamlit Community domain. You can also modify the ```main.py``` file to edit how you want your web app to look like on the Streamlit web domain. If you want to deploy this model as a web app, you can do so by running ```main.py``` in your terminal using the following command: 
```
streamlit run main.py
```
Once you run this code in your terminal or command prompt, the app should run and a browser window should pop up taking you to the address of this app generated by Streamlit. You can also access the web app (while it is running) from the address that is shown in the terminal. 
For your clarification: Closing the browser window or tab does not necessarily close the web app. To close it properly, go to your terminal(from where you ran the streamlit app) and press <ins>CTRL+C</ins>. 


