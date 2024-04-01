Display Date and Time
======================

In this activity, you will add and display the date and time.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10628697/ezgif.com-video-to-gif__28_.gif" width = "521" height = "281">


Follow the given steps to complete this activity:
1. Add date time module


* Open file `app.py`.


* Import the `datetime` module.

```sh
    from datetime import datetime
```
    

* Declare a `now` variable and set the `datetime.now()` module to it to get the current date and time.

```sh
    now = datetime.now()
```

*  Add `date` key in the `blockData`.

```sh
    blockData = {
            "sender": sender,
            "receiver": receiver,
            "amount": amount,
            "date": now
        }
```


2. Display the time.


* Open the file `index.html` from `templates` folder.


* Create a `div` and add the date field to display the date from the `blockData`.

```sh
    <div id="Date">
        <img src="../static/assets/calender.png"> Date: {{blockData["date"]}}
    </div>
```

* Save and run the code to check the output.
