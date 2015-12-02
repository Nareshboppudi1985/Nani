<!DOCTYPE html>
<html lang="en" ng-app="app">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>cart multi line monthly ways to save</title>
    <!-- Dependencies -->
    <link rel="stylesheet" href="../../lib/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="../../lib/angular/angular-csp.css">
    <!-- Custom styles -->
    <link rel="stylesheet" href="../../css/common.css">
    <link rel="stylesheet" href="cart_multi_line_monthly_ways_to_save.css">
</head>

<body>
    <header class="container-fluid">
        <div class="content"></div>
    </header>
    <div class="container">
        <div id="cart-multi-line-monthly-ways-to-save">
            <!-- cart multi line monthly ways to save -->
            <div id="cart-multi-line-today-unexpanded" class="strict">
                <!-- Left Panel-->
                <div class="row equal-heights left-fixed">
                    <!-- LEFT PANEL -->
                    <div class="col-xs-12 col-sm-4 left-panel" ng-class="isFixed()">
                        <!-- All the content need to be inside of this dev -->
                        <div leftpanel>
                            <div class="row price-box gray">
                                <div class="col-xs-6 strict text-center price-button" ng-click="showPrice(0)">
                                    <h2 class="price-text gray-dark"><sup>$</sup>921<sup>30</sup></h2>
                                    <p class="xsmall">Due today* <span class="carret-icon"><i class="fa def" ng-class="{'fa-angle-down':activePrice!=0, 'fa-angle-up':activePrice==0}"></i></span>
                                    </p>
                                </div>
                                <div class="col-xs-6 strict text-center price-button border-l" ng-click="showPrice(1)">
                                    <h2 class="price-text gray-dark"><sup>$</sup>180<sup>38</sup></h2>
                                    <p class="xsmall">Due monthly* <span class="carret-icon"><i class="fa def" ng-class="{'fa-angle-down':activePrice!=1, 'fa-angle-up':activePrice==1}"></i></span</p>
							</div>
						</div>

						<div class="arrow-top arrow-l on-gray strict" ng-show="activePrice==0">

							<h3 class="m-b-25 title">John’s Line</h3>						
							
							<div class="row m-b-25">
								<p class="col-xs-8 small"> Apple iPhone 6 <br> Monthly Payment</p>
								<p class="col-xs-4 small text-right">$27.08</p>
							</div>

							<div class="row m-b-25">
								<p class="col-xs-8 small"> Simple choice plan <br> with 5GB 4G LTE Data </p>
								<p class="col-xs-4 small text-right">$70.00</p>
							</div>

							<div class="row m-b-25">
								<p class="col-xs-8 small"> JUMP!™ </p>
								<p class="col-xs-4 small text-right">$10.00</p>
							</div>
							
								
							<h3 class="m-b-25 title">Jill’s Line</h3>

							<div class="row m-b-25">						
								<p class="col-xs-8 small">Simple Choice Plan </p>
								<p class="col-xs-4 small text-right">$60.00</p>
							</div>
							

							<div class="line"></div>

							<div class="row m-b-15">
								<h5 class="col-xs-6">Subtotal</h5>
								<h5 class="col-xs-6 text-right">$167.08</h5>
							</div>

							<div class="row">						
								<p class="col-xs-8 small">Estimated Sales Tax</p>
								<p class="col-xs-4 small text-right">$13.30</p>
							</div>

							<div class="line"></div>

							<div class="row m-b-25">
								<h3 class="col-xs-6">Total</h3>
								<h3 class="col-xs-6 text-right">$180.38</h3>
							</div>
						</div>

						<div class="arrow-top arrow-r on-gray strict" ng-show="activePrice==1">

							<h3 class="m-b-25 title">John’s Line</h3>						
							
							<div class="row m-b-25">
								<p class="col-xs-8 small">Apple iPhone 6 <br> Monthly Payment</p>
								<p class="col-xs-4 small text-right">$27.08</p>
							</div>
							
							<div class="row m-b-25">						
								<p class="col-xs-8 small">Simple choice plan<br>with 5GB 4G LTE Data</p>
								<p class="col-xs-4 small text-right">$70.00</p>
							</div>
							
							<div class="row">
								<p class="col-xs-8 small">JUMP!&trade;</p>
								<p class="col-xs-4 small text-right">$10.00</p>
							</div>

							<h3 class="m-b-25 title">Jill’s Line</h3>

							<div class="row m-b-25">						
								<p class="col-xs-8 small">Simple Choice Plan</p>
								<p class="col-xs-4 small text-right">$60.00</p>
							</div>

							<div class="line"></div>

							<div class="row m-b-15">
								<h5 class="col-xs-6">Subtotal</h5>
								<h5 class="col-xs-6 text-right">$167.08</h5>
							</div>

							<div class="row">						
								<p class="col-xs-8 small">Sales Tax</p>
								<p class="col-xs-4 small text-right">$13.30</p>
							</div>

							<div class="line"></div>

							<div class="row m-b-25">
								<h3 class="col-xs-6">Total</h3>
								<h3 class="col-xs-6 text-right">$180.38</h3>
							</div>
						</div>						
					</div>		
				</div>

				<!-- RIGHT PANEL -->
				<div class="col-xs-12 col-sm-8 right-panel extra-padding-l strict">

					<!-- ********************* -->
					<h3 class="title-spacing">John’s Line</h3>

					<div class="row row-fix column-fix m-b-15">
						<div class="col-xs-3 col-8-3 extra-padding-l text-center">
							<img src="http://placehold.it/75x156&text=FPO" alt="iphoned">
						</div>
						<div class="col-xs-7">
							<div class="row m-b-25">
								<p class="col-xs-12 col-sm-3 xsmall n-padding-l">Device</p>
								<div class="col-xs-12 col-sm-9 n-padding-xs">
									<p class="xsmall m-b-10">Apple iPhone 6 16GB Gold</p>
									<p class="xsmall n-margin">(Monthly Payment)</p>
								</div>
								
							</div>
							<div class="row m-b-25">
								<p class="col-xs-12 col-sm-3 xsmall n-padding-l">Plan</p>
								<div class="col-xs-12 col-sm-9 n-padding-xs">
									<p class="xsmall m-b-25">5GB 4G LTE Data</p>
									<p class="xsmall m-b-10">Includes</p>
									<p class="xsmall m-b-10">Unlimited talk, text &amp; data</p>
									<p class="xsmall m-b-10">Data Stash included</p>
									<p class="xsmall n-margin">+ JUMP!&trade;</p>
								</div>
							</div>
							<div class="row">
								<p class="col-xs-12 col-sm-3 xsmall n-padding-l n-margin-xs">Equipment</p>
								<p class="col-xs-12  col-sm-9 xsmall n-margin n-padding-xs">SIM Starter Kit</p>
							</div>
						</div>

					</div>
					

					 <div class="row row-fix tertiaty-buttons task">
						<div class="col-xs-4 button-box small">
							<a href="#"><span class="center"><i class="fa fa-pencil"></i><br>Edit</span>
                                        </a>
                                </div>
                                <div class="col-xs-4 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-files-o"></i><br>Duplicate</span></a>
                                </div>
                                <div class="col-xs-4 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-close"></i><br>Remove</span></a>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-12 gray-line visible-xs"></div>
                            </div>
                            <div class="col-xs-12 gray-line hidden-xs"></div>
                            <!-- ********************* -->
                            <div class="row m-b-25 ">
                                <div class="col-xs-12">
                                    <h3 class="title-2">Jill’s Line</h3>
                                </div>
                            </div>
                            <div class="row row-fix column-fix m-b-15">
                                <div class="col-xs-3 col-8-3 extra-padding-l text-center">
                                    <img src="http://placehold.it/75x156&text=FPO" alt="iphoned">
                                </div>
                                <div class="col-xs-7">
                                    <div class="row m-b-25">
                                        <p class="col-xs-12 col-sm-3 xsmall n-padding-l">Device</p>
                                        <div class="col-xs-12 col-sm-9 n-padding-xs">
                                            <p class="xsmall">Samsung Galaxy S5 128GB</p>
                                            <p class="xsmall">Charcoal Black</p>
                                            <p class="xsmall n-margin">(Pay in Full)</p>
                                        </div>
                                    </div>
                                    <div class="row m-b-25">
                                        <p class="col-xs-12 col-sm-3 xsmall n-padding-l">Plan</p>
                                        <div class="col-xs-12 col-sm-9 n-padding-r n-padding-xs">
                                            <p class="xsmall m-b-25">Unlimited 4G LTE Data</p>
                                            <p class="xsmall m-b-10">Includes</p>
                                            <p class="xsmall m-b-10">Unlimited Talk, Text &amp; Data</p>
                                            <p class="xsmall m-b-10">Unlimited Nationwide 5G LTE Data</p>
                                            <p class="xsmall n-margin">5GB Smartphone Mobile Hotspot</p>
                                        </div>
                                    </div>
                                    <div class="row">
                                        <p class="col-xs-12 col-sm-3 xsmall n-padding-l n-margin-xs">Equipment</p>
                                        <p class="col-xs-12  col-sm-9 xsmall n-margin n-padding-xs">SIM Starter Kit</p>
                                    </div>
                                </div>
                            </div>
                            <div class="row row-fix tertiaty-buttons task">
                                <div class="col-xs-4 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-pencil"></i><br>Edit</span></a>
                                </div>
                                <div class="col-xs-4 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-files-o"></i><br>Duplicate</span></a>
                                </div>
                                <div class="col-xs-4 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-close"></i><br>Remove</span></a>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-12 gray-line visible-xs"></div>
                            </div>
                            <div class="col-xs-12 gray-line hidden-xs"></div>
                            <!-- ********************** -->
                            <div class="row">
                                <p class="col-xs-12 small magenta n-margin m-t-25">Add a line</p>
                                <h3 class="col-xs-12 m-b-25 title">Accessories</h3>
                            </div>
                            <div class="row m-b-15">
                                <div class="col-xs-4 text-center">
                                    <img src="http://placehold.it/75x156&text=FPO" alt="iphone-gold">
                                </div>
                                <div class="col-xs-8 col-md-6 info-case">
                                    <h6 class="n-margin m-b-15">Samsung Galaxy S® 5 Case Mate Glam Case - Champagne</h6>
                                    <p class="small m-b-25">(Pay in Full)</p>
                                    <p class="small m-b-15">Genuine crystal with premium leather accent</p>
                                    <p class="small m-b-15">Interior patterned inlay adds greater protection & finished feel throughout</p>
                                    <p class="small n-margin">Sophisticated interlocking case design adds higher level of protection for your GS5</p>
                                </div>
                            </div>
                            <div class="row tertiaty-buttons task">
                                <div class="col-xs-6 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-pencil"></i><br>Edit</span></a>
                                </div>
                                <div class="col-xs-6 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-close"></i><br>Remove</span></a>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-12 gray-line visible-xs m-b-40"></div>
                            </div>
                            <div class="col-xs-12 gray-line hidden-xs m-b-40"></div>
                            <!-- ********************* -->
                            <div class="row m-b-15">
                                <div class="col-xs-4 text-center">
                                    <img src="http://placehold.it/75x156&text=FPO" alt="iphone-gold">
                                </div>
                                <div class="col-xs-8 n-padding-r">
                                    <h6 class="n-margin m-b-15">Universal Charge Cable</h6>
                                    <p class="small m-b-25">(Pay in Full)</p>
                                    <p class="small m-b-15">Micro USB tip</p>
                                    <p class="small m-b-15">Also allows data sync</p>
                                    <p class="small n-margin">1.5 meter cord length</p>
                                </div>
                            </div>
                            <div class="row tertiaty-buttons task">
                                <div class="col-xs-6 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-pencil"></i><br>Edit</span></a>
                                </div>
                                <div class="col-xs-6 button-box small">
                                    <a href="#"><span class="center"><i class="fa fa-close"></i><br>Remove</span></a>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-12 gray-line visible-xs"></div>
                            </div>
                            <div class="col-xs-12 gray-line hidden-xs"></div>
                            <!-- ********************* -->
                            <!-- Blade-->
                            <div class="row">
                                <div class="col-xs-12">
                                    <div ng-controller="SingleCollapseCtrl">
                                        <div class="row blade border-t border-b">
                                            <div class="col-xs-10 header strict p-l-30">
                                                <div class="header-container">
                                                    <h6>Ways to save</h6>
                                                    <p class="blade-desc">Trade in, promo code, and more</p>
                                                </div>
                                            </div>
                                            <div class="col-xs-2 carret-box">
                                                <a href="" ng-click="isExpanded = !isExpanded"> <i class="fa def" ng-class="{'fa-angle-down':!isExpanded, 'fa-angle-up':isExpanded}"></i>
                                                </a>
                                            </div>
                                            <div class="col-xs-12 expanded-blade" collapse="!isExpanded">
                                                <div class="col-xs-12  form-group  text-center m-b-12">
                                                    <div class="row m-tb-25">
                                                        <div class="button-box col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3 p-l-0">
                                                            <input type="text" class="form-control" placeholder="Enter Promo code">
                                                        </div>
                                                    </div>
                                                    <br>
                                                    <div class="button-box">
                                                        <button class="btn btn-primary" disabled="">Apply</button>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-xs-12 header strict p-l-0">
                                <div class="header-container ">
                                    <p class="xsmall m-tp-15 m-b-0 ">Trade in your device </p>
                                </div>
                            </div>
                            <!-- Buttons-->
                            <div class="col-xs-12 buttons-container-vertical button-spacing text-center">
                                <div class="button-box">
                                    <button class="btn btn-primary">Get Started</button>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-xs-12 n-padding blade border-b  ng-scope" style="
							    margin: 0px;"></div>
                            </div>
                            <div class="col-xs-12 buttons-container-vertical button-spacing text-center">
                                <div class="button-box m-t-15 m-t-0">
                                    <button class="btn btn-primary">Checkout</button>
                                </div>
                                <div class="button-box">
                                    <button class="btn btn-secondary">Keep shopping</button>
                                </div>
                                <div class="button-box">
                                    <button class="btn btn-secondary">Save cart</button>
                                </div>
                            </div>
                            <!-- Legal text-->
                            <div class="col-xs-12 m-b-50">
                                <p class="legal">*This is the total amount due today. Total does not reflect final price after any mail-in rebates or shipping. This is the estimated amount you will be charged every month for your wireless service and Equipment Installment Plan and does not include charges for additional services you purchase or taxes and fees. Final EIP payment may be up to $0.99 more per item and is listed in your EIP Agreement. See your EIP Agreement for details. Not applicable for T-Mobile Prepaid customers. Your first month’s bill will include taxes and fees and any applicable discounts. Any non-recurring charges (e.g., app purchases) incurred during your monthly use will appear on the following month's bill. State and Local Sales Tax is calculated based on full price of device.</p>
                            </div>
                        </div>
                    </div>
                    <!-- Left Panel-->
                </div>
            </div>
            <!--/ div#cart-multi-line-monthly-ways-to-save -->
        </div>
        <!--/ div.container -->
        <footer class="container-fluid">
            <div class="content"></div>
        </footer>
        <!-- Dependencies -->
        <script src="../../lib/angular/angular.js"></script>
        <script src="../../lib/angular/angular-animate.js"></script>
        <script src="../../lib/angular-bootstrap/ui-bootstrap-tpls.min.js"></script>
        <script src="../../lib/angular-sanitize/angular-sanitize.min.js"></script>
        <script src="../../lib/angular-ui-select/select.js"></script>
        <!-- Custom scripts -->
        <script src="../../js/app.js"></script>
        <!-- Uncomment if you need to include specific scripts for this page
	<script src="js/cart-multi-line-monthly-ways-to-save.js"></script>
	-->
</body>

</html>

