Setup the Localhost
===================
​
In this activity, you will learn to set up the local host server on your device.
​
​
<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10625565/pasted-from-clipboard.png" width = "521" height = "281">
​
​

Follow the given steps to complete this activity:
1. Set up  the server.
​
​
* Open file `app.py`.
​
​
* Import `flask` framework.
​

```sh
	from flask import Flask
```
​

* Set the route to `home` folder.

```
	app = Flask(__name__)
	@app.route("/")
```
	

* Define the `home()` function to return a message `Welcome to Block Chain`.

```sh
    def home():  
    	return "Welcome to Block Chain"
```   

​
​
* Set the `debug` value to `true` if the file is directly run.
​


```sh
    if __name__ == '__main__':
​
        app.run(debug=True)
```
    
       
* Save and run the code to check the output.