# RESTAPI_Using_Flask_Python Integration with AWS S3

# Pre-requisite: Python installation 
On Mac Os: rum "python3" command on terminal to see the version
> python3

#Command for venv (virtual environment)
mkdir flask-s3-boto3
cd flask-s3-boto3/
pip3 install virtualenv
virtualenv -p python3 venv --always-copy
source venv/bin/activate
pip install flask
pip install flask_bootstrap
pip install boto3
touch app.py (windows)
> Go To app.py and start coding




#Command to ls and kill processes on a port say 5000
netstat -vanp tcp | grep 5000
kill -9 $(lsof -ti:5000)

#Command
source venv/bin/activate
export FLASK_APP=app.py
export FLASK_DEBUG=1
(Config file is created to call the key using python “os” library)
export S3_BUCKET=<your_bucket_name>
export S3_KEY=<your key>
export S3_SECRET_ACCESS_KEY=<your secret>
