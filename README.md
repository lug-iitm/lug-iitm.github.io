# lug-iitm.github.io
Linux User's Group IIT Madras 

### Setup overview 
* Fork lug-iitm.github.io to your local repos
* Contributing (add/modify/fix) in any forms in your repos
* Submit a pull request @ lug-iitm.github.io
* The commiter/owner will see if the change is looking good and merges it with master.

### Forking & Contributing 

1. Go to this link https://github.com/lug-iitm/lug-iitm.github.io CLICK on FORK button on top right.
2. cd to your home dir. (~/) in terminal 
3. Type ``` git clone https://github.com/<your_name>/lug-iitm.github.io.git ``` . replace ``` <your_name> ``` with your github username.
4. Go into it using ``` cd lug-iitm.github.io ```
5. Add changes to the code. //This your MAIN step 
6. run using python as below. 
7. repeat 5 & 6 until you are done.


### Firing up a server using Python

Install Python and from inside the `lug-iitm.github.io.git` directory run:
On a Mac/*nix machine, run:
For Python version 2
```
python -m SimpleHTTPServer 8080
```
For Python version 3 onwards
```
python -m http.server 8080
```
You can of course also use WAMP or an alternative tool for serving up content but this is simpler.
Open any browser and navigate to ``` localhost:8080 ``` ! Yay!!
