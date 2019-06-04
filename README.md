# BS4
Bootsrap 4
<!DOCTYPE html>
<html>
<head>
<title>bs4</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
 <link rel="stylesheet" type="text/css" href="bs4/css/bootstrap.min.css">
 <link rel="stylesheet" type="text/css" href="fa/css/font-awesome.min.css">
 <script type="text/javascript" src="bs4/js/jquery-3.4.1.js"></script>
 <script type="text/javascript" src="bs4/js/jquery.wait.js"></script>
 <script type="text/javascript" src="bs4/js/popper.min.js"></script>
 <script type="text/javascript" src="bs4/js/bootstrap.min.js"></script>
</head>
<body>
	<nav class="navbar navbar-expand-sm bg-light navbar-light">
		<a href="Home.HTML" class="navbar-brand">
			<img src="img/Quest.png" style="height: 50px" alt="Qwest Logo">
		</a>
		<button class="navbar-toggler" data-toggle="collapse" data-target="#bs4Nav">
			<span class="navbar-toggler-icon"></span>
		</button>
		<div id="bs4Nav" class="collapse navbar-collapse">
			<ul class="navbar-nav ml-auto">
				<li class="nav-item"><a class="nav-link" href=""> <i class="fa fa-home"></i> Home</a></li>
				<li class="nav-item"><a class="nav-link" href=""><i class="fa fa-scribd"></i> Services</a></li>
				<li class="nav-item"><a class="nav-link" href=""><i class="fa fa-twitch"></i> Blog</a></li>
				<li class=""><a class="nav-link" href="#"><i></i></a></li>
			</ul>
		</div>
	</nav>


  <!-- media objects start -->
<div class="container">
  <div class="row">
    <div class="col-sm-12">
      <div class="media m-2 mt-4 border border-light">
        <img src="img/3.jpg" alt="logo1" class="m-2 rounded-circle border border-light" style="width: 120px;">
        <div class="media-body pt-3 pl-2">
          <h5 class="border-bottom border-bottom-light">Mr. Edward.<br> <small class="">Quest's Core founder</small> </h5>
          <p class="mb-0 text-justify p-1">
            Lorem ipsum dolor sit amet, itation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </p>
          <div class="d-flex bg-light p-1 border-top border-top-light">
            <div class="flex-fill p-1">
              <small>11:03 am, 12<sup>th</sup> Jan 2018 </small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-thumbs-o-up"></i><small> 12 likes</small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-thumbs-o-down"></i><small> 0 dislikes</small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-retweet"></i> <small> Retweet</small>
            </div>
          </div>
        </div>
      </div>


      <div class="media m-2 mt-4 border border-light">
        <img src="img/5.jpg" alt="logo1" class="m-2  rounded-circle border border-light" style="width: 120px; height:120px">
        <div class="media-body pt-3 pl-2">
          <h5 class="border-bottom border-bottom-light">Mr. Peter.<br> <small class="">Quest's Web Designer</small> </h5>
          <p class="mb-0 text-justify p-1">
            Lorem ipsum dolor sit amet, itation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </p>
          <div class="d-flex bg-light p-1 border-top border-top-light">
            <div class="flex-fill p-1">
              <small>11:03 am, 12<sup>th</sup> Jan 2018 </small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-thumbs-o-up"></i><small> 24 likes</small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-thumbs-o-down"></i><small> 0 dislikes</small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-retweet"></i> <small> Retweet</small>
            </div>
          </div>
        </div>
      </div>


      <div class="media media-success m-2 mt-4 border border-light">
        <img src="img/4.jpeg" alt="logo1" class="mr-2 rounded-circle border border-light" style="width: 120px;">
        <div class="media-body pt-3 pl-2">
          <h5 class="border-bottom border-bottom-light">Mr. Kario.<br> <small class="">Quest's Graphics Designer</small> </h5>
          <p class="mb-0 text-justify p-1">
            Lorem ipsum dolor sit amet, itation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </p>
          <div class="d-flex bg-light p-1 border-top border-top-light">
            <div class="flex-fill p-1">
              <small>11:03 am, 12<sup>th</sup> Jan 2018 </small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-thumbs-o-up"></i><small> 9 likes</small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-thumbs-o-down"></i><small> 0 dislikes</small>
            </div>
            <div class="p-1 text-center">
              <i class="fa fa-retweet"></i> <small> Retweet</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
  <!-- media objects end -->
	
	<!--comment form-->
	<div class="container">
		<form>

		<div class="form-group">
		<label class="text-center"><b>Leave a comment:</b></label>
	<div class="input-group">
		<div class="input-group-prepend">
         <span class="input-group-text"><i class="fa fa-envelope"> </i>
         </span>
		</div>
		<input type="text" name="email" class="form-control" id="demo" placeholder="your email">
	</div>
    </div>
	
	<div class="form-group">
	<label class="text-center"><b>Comment :</b></label>
	<div class="input-group">
	<div class="input-group-prepend">
		<span class="input-group-text"> <a class="fa fa-pencil"></a>
		</span>
	</div>
	<textarea class="form-control" rows="5" id="Comment"></textarea> 
    </div>
	</div>
	<div class="form-group text-center">
  <button type="submit" class="btn btn-primary">Send comment.. <a class="fa fa-send"></a></button>
</div>
  </form>
  </div>
  <div class="container-fluid bg-light pt-1" style="position: fixed; bottom: 0px;">
            <div class="row">
                <div class="col-sm-6">
                    <ul class=" border-white" style="list-style-type: none;">
                        <li class="">
                            <b>Location</b> kikuyu <a href="#" class="fa fa-map-marker"></a>
                        </li>
                        <li class="">
                            <b> Phone :</b> 0724 123456 <a href="#" class="fa fa-phone"></a>
                        </li>
                        <li class="">
                            <b>email</b>  <a href="#" class="fa fa-envelope"></a>
                        </li>
                       
                        <li class="">
                            <b>www.quest.com</b>  <a href="#" class="fa fa-globe"></a>
                        </li>
                    </ul>
                </div>
                <div class="col-sm-6">
                    <div class="d-flex flex-row text-right">
                        <div class="p-2 flex-fill"><a href="#" class=" fa fa-facebook"></a></div>
                        <div class="p-2 flex-fill"><a href="#" class="fa fa-whatsapp"></a></div>
                        <div class="p-2 flex-fill"><a class="fa fa-telegram" href="#"></a></div>
                    </div>
                    <div class="d-flex flex-column text-right">
                        <div class="p-2 flex-fill"><a href="#" class="fa ">pwpinches@gmail.com</a></div>
                    
                        <div class="p-2 flex-fill"><b>kevokario@gmail.com</b></div>
                    </div>
                </div>
            </div>
        </div>
<!--end of comment form--->
</body>
</html>

</body>
</html>
