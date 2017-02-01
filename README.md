<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Responsive Layout</title>
<style>
/********** Base styles **********/
* {
  box-sizing: border-box;
  box-background-color: black;
  
}
h1 {
  margin-bottom: 15px;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
}
/********** Large devices only **********/
@media (min-width: 767px) {
  .col-lg-1, .col-lg-2, .col-lg-3 {
    float: left;
    border: 1px solid black;
  }
  .col-lg-1 {
    width: 33.33%;
  }
  .col-lg-2 {
    width: 33.33%;
  }
  .col-lg-3 {
    width: 33.33%;
  }
  
}
/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3 {
    float: left;
    border: 1px solid black;
  }
  .col-md-1 {
    width: 50%;
  }
  .col-md-2 {
    width: 50%;
  }
  .col-md-3 {
    width: 100%;
  }
}
}
/********** Small devices only **********/
@media (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3 {
    float: left;
    border: 1px solid black;
  }
  .col-sm-1 {
    width: 100%;
  }
  .col-sm-2 {
    width: 100%;
  }
  .col-sm-3 {
    width: 100%;
  }
}
</style>
</head>
<body>
<h1 style="text-align:center">Our Menu</h1>


<div class="row">
  <div class="col-lg-3 col-md-2 col-sm-1"><p style="text-align:right">Chicken</p></div>
  <div class="col-lg-3 col-md-2 col-sm-1"><p style="text-align:right">Beef</p></div>
  <div class="col-lg-3 col-md-1 col-sm-1"><p style="text-align:right">Sushi</p></div>
</div>


</body>
</html>
