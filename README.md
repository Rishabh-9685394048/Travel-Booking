<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="airline1.css">
  <link rel="stylesheet" href="bootstrap.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <title>airline home page</title>
</head>
<body>
  <ul class="nav justify-content-center  ">
    
    <li class="nav-item ">
      <a class="nav-link disabled border-bottom border-white" aria-current="page" href="#"><i class="fa fa-fighter-jet"> Flights &nbsp&nbsp&nbsp&nbsp;</i></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="hotel1.html"><i class="fa fa-home">&nbsp&nbsp&nbspHotels&nbsp&nbsp&nbsp</i></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="cars1.html"><i class="fa fa-car">&nbsp&nbsp&nbspCars&nbsp&nbsp&nbsp</i></a>
    </li>
    <li class="nav-item">
      <a class="nav-link " href="sign-in.html" ><i class="fa fa-sign-in">&nbsp&nbsp&nbspSign-In&nbsp&nbsp&nbsp</i></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="login.html"><i class="fa fa-lock">&nbsp&nbsp&nbspLogin&nbsp&nbsp&nbsp</i></a>
    </li>
    
  </ul>
  <div class="container-fluid">
    <div class="row" style="position:static;">
      <div class="col-12">
        <div class="shadow p-3 mb-5 bg-body rounded">
          <h4 class="text-cyan" style="text-align: center;">Book Flights, Hotels and cars</h4><br>
          <span class="border border-danger px-2 m-2"><a href="" style="color: red;">ONE WAY</a></span>
          <span class="border border-secondary  px-2 m-2 "><a href="" style="color: grey;">ROUND-TRIP</a></span>
          <span class="border border-success px-3 m-2"><a href="" style="color: gray;">MULTI-CITY</a></span>
          <span class="border border-danger  m-2"><a href="" style="background-color:rgb(63, 35, 35); color: white;">CHARTERS</a></span> <br> <br>
          <div class="row" style="margin-top:20px;">
            <div class="col-6" style="color:black; font-weight: bold;">
              Depart From <br>
              <input type="text" class="form-control input-group-sm"><hr>
            </div>
            <div class="col-1"><i class="fa fa-arrows-h"></i></div>
            <div class="col-5 text-end "style="color:black; font-weight: bold;">
            Going To <br>
            <input type="text" class="form-control input-group-sm"><hr>
            </div> 
          </div>
          <div class="row" style="margin-top:80px;">
            <div class="col-6">
              <p>Departure Date</p>
              <input type="date"><hr>
              <br>
            </div>
            <div class="col-1"></div>
            <div class="col-5 text-end "style="color:black; font-weight: bold;">
            Return Date <br>
            <input type="date"class="form-control input-group-sm"><hr>
            </div> 
          </div>
          <div class="row" style="margin-top:80px;">
            <div class="col-12">
              <p style="margin-top:40px; font-weight: bold;" class="text-danger">Child
                <select>
                  <option>1</option>
                  <option>2</option>
                  <option>3</option>
                  <option>4+</option>
                </select>
                <div id="con1">
                  <h6>Mobile number</h6>
              <input type="number" placeholder="Enter a mobile number"></div>
              </p>
                <p style="margin-top:40px; font-weight: bold;" class="text-danger">Adult
                  <select>
                    <option>1</option>
                    <option>2</option>
                    <option>3</option>
                    <option>4+</option>
                  </select></p>
                  <p style="margin-top:40px; font-weight: bold;" class="text-danger">Younger
                    <select>
                      <option>1</option>
                      <option>2</option>
                      <option>3</option>
                      <option>4+</option>
                    </select></p>

                    <button type="button" class="btn btn-primary" style="float: right;">Search Flights &nbsp; &nbsp;<i class="fa fa-arrow-right"></i></button>
                    
                  </div>
            </div> 
          </div>
        </div>
        <br>
        
        </div>
        <div class="row">
          <p style="margin-top:50px; font-size:30px;">International Flight Routes</p><br>
          <h6>From -
            <a href="">New Delhi</a>
            <a href="" style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Banglore</a>
            <a href=""style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Hydrabad</a>
            <a href=""style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Kolkata</a>
            <a href=""style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Others</a>
          </h6>
          <div class="col-sm-12 ">
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>America</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>40,000</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Australia</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>30,770</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Canada</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>45,100</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>London</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>42,000</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>NewYork</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>48,900</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Newzeland</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>63,500</p></p1></div>
            
            
          </div>
          
          <div class="row">
            <p style="margin-top:50px; font-size:30px;"> Popular places </p><br>
            <div class="col-12 ">
              <div class="shadow p-3 mb-5 bg-body rounded " id="col-11">
                <div class="row">
                  <img src="image11.jpg" height="130px" width="10%">
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus.</p>
                </div>
              </div>
              <div class="shadow p-3 mb-5 bg-body rounded " id="col-11">
                <div class="row">
                  <img src="image10.jpg" height="130px" width="10%">
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus.</p>
                </div>
              </div>
              <div class="shadow p-3 mb-5 bg-body rounded " id="col-11">
                <div class="row">
                  <img src="image8.jpg" height="130px" width="10%">
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus.</p>
                </div>
              </div>
              <div class="shadow p-3 mb-5 bg-body rounded " id="col-11">
                <div class="row">
                  <img src="image6.jpg" height="130px" width="10%">
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus.</p>
                </div>
              </div>
              <div class="shadow p-3 mb-5 bg-body rounded " id="col-11">
                <div class="row">
                  <img src="image12.jpg" height="130px" width="10%">
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus.</p>
                </div>
              </div>
              <div class="shadow p-3 mb-5 bg-body rounded " id="col-11">
                <div class="row">
                  <img src="image7.jpg" height="130px" width="10%">
                  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus.</p>
                </div>
              </div>
              
              
        </div>
        <div class="row">
          <p style="margin-top:50px; font-size:30px;">Popular Domestic Flight Routes</p><br>
          <h6>From -
            <a href="">New Delhi</a>
            <a href="" style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Banglore</a>
            <a href=""style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Hydrabad</a>
            <a href=""style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Kolkata</a>
            <a href=""style="text-decoration: none;color: gray; font-size:20px;" class="px-3">Others</a>
          </h6>
          <div class="col-12 ">
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Goa</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>2,000</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Pune</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>1,770</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Banglore</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>2,100</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Dubai</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>2000</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Hongkong</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>1,900</p></p1></div>
            <div class="shadow p-3 mb-5 bg-body rounded " id="col-11"><i class="fa fa-arrows-v" style="font-size:130px;"></i> &nbsp &nbsp &nbsp <p1 style="position: relative; bottom: 100px;"><b>Delhi</b> <br><p style="position: relative; left:85px;"> Thrus,30 June</p> <br><p style="position: relative; left:85px;"><b>Mumbai</b></p><p style="position: relative; left:85px;">Starting From</p><p style="position: relative; left:85px; font-weight: bold; color: red;"><i class="fa fa-inr"></i>3,500</p></p1></div>
            
          </div>
      <div class="row">
        <div class="col-12 bg-primary col-12-wrap" >
          <div class="shadow p-3 mb-5 bg-body rounded " id="col-11" style="width: 100%; height:400px;">
          <h5 style="font-weight: bold;"> Security & Payment</h5><br>
          <img src="UPI.png" height="100px" width="10%" style="margin-top:20px;">
          <img src="phonepay.png" height="100px" width="10%" style="margin-top:20px;margin-left:40px;">
          <img src="paytm.png" height="100px" width="10%" style="margin-top:20px; margin-left:60px;">
          <img src="googlepay.jpg" height="100px" width="10%" style="margin-top:20px;margin-left:100px;">
          <img src="Visa.png" height="100px" width="10%" style="margin-top:20px;margin-left:120px;">
          <img src="mastercard.png" height="100px" width="10%" style="margin-top:20px;margin-left:140px;">
           <br>
           <h4 style="margin-top:50px;"> <b>Keep In Touch</b> </h4><br>
           <a href="#" style="font-size:30px;"><i class="fa fa-facebook-square"></i></a>
           <a href="#" style="font-size:30px; margin-left:20px;"><i class="fa fa-instagram"></i></a>
           <a href="#" style="font-size:30px;margin-left:30px;"><i class="fa fa-linkedin-square"></i></a>
          <br>
           <p style="float: left; margin-bottom:50px;">copyright@ 2021 Traveller online private Limited Company. All rights reserved.</p>  
        </div>
          
      </div>
    </div>
  </div>
  <script src="jquery.js"></script>
  <script>
    $(document).ready(function(){
      $('button').click(function(){
        window.location.href="search flights.html";
      });
    });
  </script>
</body>
</html>
