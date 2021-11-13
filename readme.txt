Steps to Execute the application:

1. Install pipenv:
pip install pipenv

2. Go to Sentiment Analysis folder on terminal: (where pipfile is located.)
3. Run: pipenv sync
It will install all the dependencies mentioned in the pipfile.lock
Now activate the environment using 1. 'pipenv shell' then 2. 'activate' in the given order.

4. Run 'python ./src/app.py' to stream the tweets and storing to database.
5. Open another terminal on the above location, activate the environment using 'pipenv shell' and then 'activate'
6. Run the dashboard application: 'python ./src/dash_streaming.py'
It will print something like this: "Dash is running on http://127.0.0.1:8050/".
open the link to see the dashboard.
If dashboard doesn't updates automatically, please hit refresh.

#############################################################################
To Enter any other keyword, or change the topic of dashboard.
Please check the config.py
Update the list - keywords = ["IPL"] to any other.
We can use as many keywords we want: example: keywords = ["IPL","COVID","StateElections"]
