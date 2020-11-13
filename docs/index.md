<!DOCTYPE html>
<!--
* SAPHIR - The Coming Soon Template
* Build Date: May 2018
* Last Update: May 2018
* Author: Madeon08
* Copyright (C) 2018-2XXX Madeon08
* This is a premium product available exclusively here : https://themeforest.net/user/Madeon08/portfolio
* -->
<html lang="zxx" class="no-js">

	<head>
		<meta charset="utf-8">
		<title>Primefort -  Securing Innovation</title>
		<meta name="description" content="The description should optimally be between 150-160 characters.">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="author" content="Madeon08">

        <!-- ================= Favicons ================== -->
        <!-- Standard -->
        <link rel="shortcut icon" href="img/favicon.png">
        <!-- Retina iPad Touch Icon-->
        <link rel="apple-touch-icon" sizes="144x144" href="img/favicon-retina-ipad.png">
        <!-- Retina iPhone Touch Icon-->
        <link rel="apple-touch-icon" sizes="114x114" href="img/favicon-retina-iphone.png">
        <!-- Standard iPad Touch Icon--> 
        <link rel="apple-touch-icon" sizes="72x72" href="img/favicon-standard-ipad.png">
        <!-- Standard iPhone Touch Icon--> 
        <link rel="apple-touch-icon" sizes="57x57" href="img/favicon-standard-iphone.png">

		<!-- ============== Resources style ============== -->
		<link rel="stylesheet" type="text/css" href="css/style.css" />

		<!-- Modernizr runs quickly on page load to detect features -->
		<script src="js/modernizr.custom.js"></script>
	</head>

	<body>

		<!-- *** LOADING *** -->

		<div id="loading">

			<div class="loader">
				<span class="dots">	.</span>
				<span class="dots">	.</span>
				<span class="dots">	.</span>
				<span class="dots">	.</span>
				<span class="dots">	.</span>
				<span class="dots">	.</span>
				<p class="loader__label">Jason | <span data-words="Loading|Chargement|Lädt|Cargando|加载中"></span></p>
			</div>
		</div>

		<!-- *** / LOADING *** -->

		

		<!-- Logo on top right -->
		<a class="brand-logo" href="#Home">
			<img src="img/kj-3.png" alt="My logo" class="img-fluid" style="width: 300px;height: auto;" />
		</a>

		<!-- *** Fullpage sections *** -->
		<div id="fullpage">

			<!-- +++ START - Home +++ -->
			<div class="section" id="section0">

				<section class="content-inside-section">

					<div class="container">

						<div class="container-inside">

							<div class="main-content align-center">

								<!-- *** TEXT TITLE *** -->
								<center><img src="img/whitedevil.png" alt="Our company logo" class="img-fluid" style="width: 300px;height: auto;" /></center>
								<h1>
									I am Coming Soon
								</h1>

								<!-- *** COUNTDOWN TITLE *** -->
								<!-- Set your date at the bottom of js/jquery.countdown.js -->

								<!-- <h1>
									official launch in<br>
									<span id="getting-started"></span>
								</h1> -->

								<p class="on-home">
								</p>

								<br>

								<div class="command">

									<!-- ********** IF YOU WANT TO USE MORE POPUPS, SEE THE RECOMMENDATIONS AT THE END OF js/dialogFx.js ********** -->
									<!--<a id="popup_somedialog_1" data-dialog="somedialog_1" class="trigger light-btn colored">
										<span id="first-text">Keep me updated!</span>
										<span id="second-text">Get notified</span> <!-- On this span, it's important to use a text smaller or equal than the first one (here: Weekly Newsletter) to avoid any troubles -->
									<!--</a>-->

									

									<div class="clear"></div>

								</div>
							</div>
						</div>
					</div>
				</section>

			</div>
			<!-- +++ END - Home +++ -->

			
		</div>
		<!-- +++ / Fullpage sections +++ -->

		<!-- START - Newsletter Popup -->
		<div id="somedialog_1" class="dialog">

			<div class="dialog__overlay"></div>
					
			<div class="dialog__content">
						
				<div class="dialog-inner">
							
					<h3>You like taking the lead of line?</h3>
							
					<p>Being the first to know always feels great... Signing up to our newsletter gives you <strong>exclusive access to our Grand Opening!</strong></p>

					<!-- Newsletter Form -->
					<div id="subscribe">

		                <form action="php/notify-me.php" id="notifyMe" method="POST">

		                    <div class="form-group">

		                        <div class="controls">
		                            
		                        	<!-- Field  -->
		                        	<input type="text" id="mail-sub" name="email" placeholder="Click here to type your email" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Click here to type your email'" class="form-control email srequiredField" />

		                            <!-- Button -->
		                            <button class="btn btn-lg submit on-center"><span>Get notified</span></button>

		                            <div class="clear"></div>

		                        </div>
		                    </div>
		                </form>
        			</div>
        			<!-- /. Newsletter Form -->

				</div>

				<!-- Cross closing the Newsletter Popup -->
				<button class="close-newsletter" data-dialog-close><i class="icon ion-close-round"></i></button>

			</div>		
		</div>
		<!-- END - Newsletter Popup -->

		<!-- CONTACT FORM - Answer for the contact form is displayed in the next div, do not remove it. -->       
        <div id="block-answer" class="">

            <div id="answer"></div>

        </div>

		<!-- NEWSLETTER FORM - Answer for the newsletter form is displayed in the next div, do not remove it. -->
		<div class="block-message">

			<div class="message">

				<p class="notify-valid"></p>
			</div>
		</div>

		
		<!-- ///////////////////\\\\\\\\\\\\\\\\\\\ -->
        <!-- ********** jQuery Resources ********** -->
        <!-- \\\\\\\\\\\\\\\\\\\/////////////////// -->

        <!-- * Libraries jQuery, Easing and Bootstrap - Be careful to not remove them * -->
        <script src="js/jquery.min.js"></script>
        <script src="js/jquery.easings.min.js"></script>
        <script src="js/bootstrap.min.js"></script>

		<!-- Countdown plugin -->
		<script src="js/jquery.countdown.js"></script>

		<!-- FullPage plugin -->
		<script src="js/jquery.fullPage.js"></script>

        <!-- Alien animation plugin -->
        <script src="js/alien.js"></script>

		<!-- Contact form plugin -->
		<script src="js/contact-me.js"></script>

		<!-- Popup Newsletter Form -->
		<script src="js/classie.js"></script>
		<script src="js/dialogFx.js"></script>

		<!-- Newsletter plugin -->
		<script src="js/notifyMe.js"></script>

		<!-- Gallery plugin -->
		<script src="js/jquery.detect_swipe.min.js"></script>
		<script src="js/featherlight.js"></script> 
		<script src="js/featherlight.gallery.js"></script>

		<!-- Main JS File -->
		<script src="js/main.js"></script>

	</body>

</html>
