# slide-out-form
Forms -- they are one of the single most important elements for capturing leads on a website. But some forms are more engaging to your website’s visitors than others. One of the most effective form types are slide out forms. These simple sliders pop out when a visitor clicks a button (i.e. wants to sign up for more information or start a free trial).
  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Craft a Slide Out Form](https://www.solodev.com/blog/how-to-craft-a-slide-out-form.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/pLbv39hs/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container">
  <div class="row mt-5">
	  <div class="col-sm-12">
	  	<p class="text-center">
			<img alt="logo" src="https://www.solodev.com/_/images/solodev-logo.png" class="img-responsive mx-auto" />
		</p>
		<p class="text-center">
		  <a href="#" class="btn btn-info btn-lg cta-open">Start a free trial</a>
		</p>
	  </div>
  </div>
</div>

<section class="toggle-form">
  <div class="formwrap px-4">
    <div class="icon-close pos-a"><img src="https://www.solodev.com/_/images/cross.png" alt="Close Button"></div>
    <p class="text-white mt-4 h3">Try Solodev for Free!</p>
	
	<form action="#" method="post" role="form" data-toggle="validator">
		<div class="form-group margin-top-m">
		  <label for="fname" class="control-label">First name</label>
		  <input type="text" id="fname" name="fname" class="form-control" data-error="Please enter your first name" required>
		  <div class="help-block with-errors"></div>
		</div>
		<div class="form-group">
		  <label for="lname" class="control-label">Last name</label>
		  <input type="text" id="lname" name="lname" class="form-control required" data-error="Please enter your last name" required>
		  <div class="help-block with-errors"></div>
		</div>
		<div class="form-group">
		  <label for="email_address" class="control-label">Email address</label>
		  <input type="text" id="email_address" name="email_address" class="form-control validate[required,custom[email]]" data-error="Please enter a valid email" required>
		  <div class="help-block with-errors"></div>
		</div>
		<div class="form-group">
		  <label for="phone" class="control-label">Phone number</label>
		  <input type="text" id="phone" name="phone" class="form-control required" data-error="Please enter a valid phone number" required>
		  <div class="help-block with-errors"></div>
		</div>
		<div class="row">
		  <div class="col-md-6 mid-col">
			<div class="form-group">
			  <label for="company_size" class="control-label">Company Size?</label>
			  <select name="company_size" id="company_size" class="form-control required" data-error="Please select your company size" required>
				<option value=""></option>
				<option value="1-4 employees">1-4 employees</option>
				<option value="5-9 employees">5-9 employees</option>
				<option value="10-49 employees">10-49 employees</option>
				<option value="50-199 employees">50-199 employees</option>
				<option value="200-499 employees">200-499 employees</option>
				<option value="500-999 employees">500-999 employees</option>
				<option value="1000+ employees">1000+ employees</option>
			  </select>
			  <div class="help-block with-errors"></div>
			</div>
		  </div>
		  <div class="col-md-6 mid-col">
			<div class="form-group">
			  <label for="role" class="control-label">Select you role</label>
			  <select name="role" id="role" class="form-control required" data-error="Please select your role" required>
				<option value=""></option>
				<option value="Web Developer">Web Developer</option>
				<option value="Marketing Professional">Marketing Professional</option>
				<option value="Business Executive">Business Executive</option>
			  </select>
			  <div class="help-block with-errors"></div>
			</div>
		  </div>
		</div>
		<p class="text-center margin-top-s"><small>By clicking "Submit" you agree to Solodev’s <a href="/terms/">Terms of Service</a>.</small></p>
		<p class="margin-0"><button type="submit" class="btn btn-lg orange w-100 margin-top-s">Submit</button></p>
	</form>    
  </div>
  <div class="toggle-bg"></div>
</section>
```

## CSS

All required CSS is contained with slide-out-form.css

## JavaScript

All required JS is contained with slide-out-form.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

