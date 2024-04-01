Create the First Block
======================


In this activity, you will learn to create the First block for the blockchain.




<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10628630/ezgif.com-video-to-gif__26_.gif" width = "521" height = "281">



Follow the given steps to complete this activity:
1. Make a request.


* Open file `app.py`.


* Create the dictionary named `blockData` and add the block data to it.

```sh
    blockData = {
    "sender": sender,
    "receiver": receiver,
    "amount": amount
    }
```
    
* Send the dictionary to `index.html` file.

```sh
    @app.route("/", methods= ["GET", "POST"])
```
    
* Using `Jinja` combine conditional statements, loops, variables, etc., in HTML:
Use conditional statements to  display the block.
 
```sh
    if request.method == "GET":
        return render_template('index.html')
```
    


* Add an else condition to get the data that the user entered on the form and send it to the server.

```sh
    else:
        sender = request.form.get("sender")
        receiver = request.form.get("receiver")
        amount = request.form.get("amount")
```
    


* Print the data on the console and display the index page.

```sh
    print(sender, receiver, amount)
    return render_template('index.html')
```
   
* Save and run the code to check the output.
