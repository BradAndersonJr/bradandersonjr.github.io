>>> Conversion for .ipynb to .html

    move 20200322.ipynb C:\Users\bradl\OneDrive\Documents\GitHub\bradandersonjr.github.io\apathtopython\notebooks & 
    cd C:\Users\bradl\OneDrive\Documents\GitHub\bradandersonjr.github.io\apathtopython\notebooks & 
    jupyter nbconvert --to html 20200322.ipynb

>>> Search and delete below from .html: [ Ctrl + H ]

@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}

### >>> Search and replace below: [ Ctrl + H ]

From:

body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;

To:

body {
  overflow: hidden;
  padding: 8px;
}

div#notebook {
  overflow: hidden;
  border-top: none;

From:

 */
body {
  background-color: #fff;

To:

 */
body {
  background-color: #fdfdfd;

### >>> Add to just beneath <style type="text/css"> :

/* Header/Logo Title */
.header {
    padding: 40px;
    text-align: center;
    background: lightsteelblue;
    color: white;
    font-size: 20px;
}  


https://getbootstrap.com/docs/4.0/components/alerts/

https://www.w3schools.com/bootstrap4/bootstrap_alerts.asp