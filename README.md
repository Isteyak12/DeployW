<!-- from flask import Flask
# importing the Flask module and
# creating a Flask web server from the Flask module.

app = Flask(__name__)
# We are creating an instance of the Flask class
# and calling it app. Here
# we are creating a new web application. -->

@app.route("/")
def home():
return "Hello, World!"

if **name** == "**main**":
app.run(debug=True)

//finally running this cmd after complaining to gpt about some err worked:
pip install --upgrade -t lib -r requirements.txt

1995 gcloud app deploy
1996 snap install google-cloud-cli
1997 gcloud app deploy
1998 snap install google-cloud-cli # version 475.0.0
1999 --classic
2000 snap install google-cloud-cli # version 475.0.0
2001 gcloud app deploy
2002 snap install google-cloud-sdk # version 475.0.0
2003 pip install -t lib -r requirements.txt
2004 name of virtual environment\Scripts\activate
2005 source virtual/bin/activate
2006 pip install -t lib -r requirements.txt
2007 --upgrade to force replacement
2008 pip install --upgrade -t lib -r requirements.txt
2009 history

To install the Google Cloud CLI snap with classic confinement, you need to repeat the command with the `--classic` option included. Here's the correct command:

```
snap install google-cloud-cli --classic
```

This command will install the Google Cloud CLI snap in classic confinement, allowing it to perform system changes outside of the security sandbox, as mentioned in the error message. If you understand the implications and want to proceed, running the command with `--classic` is the appropriate way to do so.

Web Hosting Services:
-GCP
-Heroku
-PythonAnywhere

WARNING: Running pip as the 'root' user can result in broken permissions and conflicting behaviour with the system package manager. It is recommended to use a virtual environment instead: https://pip.pypa.io/warnings/venv

Configs(was finally able to run the jupyter cmds via watching this vid and 
jupyter notebook --allow-root): 
https://www.youtube.com/watch?v=HLD-Ll_-IT4
 1980  ssh -i "comp3340.pem" ubuntu@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1981  ls
 1982  Ls -l comp3340.pem
 1983  ls -l comp3340.pem
 1984  chmod 777 comp3340.pem
 1985  ls
 1986  ls -l comp3340.pem
 1987  ssh -i "comp3340.pem" ubuntu@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1988  chmod 400 "comp3340.pem"
 1989  ls -l comp3340.pem
 1990  ssh -i comp3340.pem Batman@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1991  chmod 400 comp3340.pem
 1992  ssh -i comp3340.pem Batman@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1993  pip install jupyterlab
 1994  python3 -m venv myenv
 1995  pip install notebook
 1996  jupyter notebook
 1997  --allow-root
 1998  jupyter notebook --allow-root




neeed to investigate jupyterlab and this:
 1910  source virtual/bin/activate
 1911  virtual environment\Scripts\activate
 1912  virtual\Scripts\activate
 1913  exit
 1914  virtual\Scripts\activate
 1915  name of virtual environment\Scripts\activate
 1916  exit
 1917  source virtual/bin/activate
 1918  pip install flask
 1919  python -u "c:\Users\Isteyak\Downloads\uWindsor\Summer 2024\Projects\DeployW\main.py"
 1920  source virtual/bin/activate
 1921  pip install -t lib -r requirements.txt
 1922  gcloud app deploy
 1923  exit
 1924  jupyter lab
 1925  apt install jupyter-core
 1926  pip install jupyterlab
 1927  jupyter lab
 1928  pip install jupyterlab
 1929  python3 -m pip install --upgrade pip
 1930  pip install jupyterlab
 1931  jupyter lab
 1932  pip install notebook
 1933  jupyter notebook
 1934  brew install jupyterlab
 1935  pip install notebook
 1936  jupyter notebook
 1937  ssh -i "comp3340.pem" ubuntu@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1938  ls
 1939  Ls -l comp3340.pem
 1940  ls -l comp3340.pem
 1941  chmod 777 comp3340.pem
 1942  ls
 1943  ls -l comp3340.pem
 1944  ssh -i "comp3340.pem" ubuntu@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1945  chmod 400 "comp3340.pem"
 1946  ls -l comp3340.pem
 1947  ssh -i comp3340.pem Batman@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1948  chmod 400 comp3340.pem
 1949  ssh -i comp3340.pem Batman@ec2-35-183-130-203.ca-central-1.compute.amazonaws.com
 1950  pip install jupyterlab
 1951  python3 -m venv myenv
 1952  pip install notebook
 1953  jupyter notebook
 1954  --allow-root
 1955  jupyter notebook --allow-root
 1956  histiry
 1957  history
 1958  gcloud app deploy
 1959  gcloud app deploy probable-signal-423215-t4
 1960  gcloud app deploy --probable-signal-423215-t4
 1961  gcloud auth list
 1962  gcloud app deploy --probable-signal-423215-t4
 1963  gcloud app deploy
 1964  gcloud auth list
 1965  gcloud projects add-iam-policy-binding probable-signal-423215-t4 --member=user:isteyakislam12@gmail.com --role=roles/appengine.deployer
 1966  gcloud app deploy --probable-signal-423215-t4
 1967  gcloud auth list
 1968  code .
 1969  gcloud config set project probable-signal-423215-t4
 1970  gcloud app deploy --probable-signal-423215-t4
 1971  gcloud auth list
 1972  gcloud app deploy
 1973  code .
 1974  gcloud app deploy
 1975  code .
 1976  pip install -r requirements.txt
 1977  gcloud app deploy
 1978  virtualenv venv
 1979  source venv/bin/activate
 1980  .\venv\Scripts\activate
 1981  pip install virtualenv
 1982  virtualenv venv
 1983  exit
 1984  source venv/bin/activate
 1985  python -m venv venv
 1986  source venv/bin/activate
 1987  venv\Scripts\activate
 1988  pip install -r requirements.txt
 1989  gcloud app deploy
 1990  gcloud app browse'
 1991  gcloud app browse
 1992  gcloud app logs tail -s default
 1993  EXIT
 1994  exit
 1995  history