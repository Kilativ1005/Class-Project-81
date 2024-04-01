Change Route and Post
======================


In this activity, you will create the form to directly reset the fields and clear the data.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10628939/ezgif.com-video-to-gif__29_.gif" width = "521" height = "281">



Follow the given steps to complete this activity:
1. Create a form


* Open file `index.html`.


* Create a new form to send `GET` request, so that page shows only the form and data gets reset.


* Create a `RESET` button within the form.

```sh
    <form action="{{ url_for('home')}}" method="get" id="form2" class="d-flex justify-content-center align-items-center mt-4">
      <button type="submit" class="btn btn-primary">RESET</button>
    </form>
```
  
* Save and run the code to check the output.
