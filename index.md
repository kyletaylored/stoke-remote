---
layout: default
---

<h1>{{ site.name }}</h1>
<p>{{ site.description | escape }}</p>
<form class="form text-center form-horizontal" id="stoke-form" name="stoke-form">
	<div class="row">
		<div class="col-md-12 mb-4">
			<fieldset>
				<!-- Form Name -->
				<legend>Form Name</legend> <!-- Text input-->
				<div class="form-group">
					<label class="col-md-4 control-label" for="worker-name">Name</label>
					<div class="col-md-4">
						<input class="form-control input-md" id="worker-name" name="worker-name" placeholder="Your name" required="" type="text">
					</div>
				</div><!-- Text input-->
				<div class="form-group">
					<label class="col-md-4 control-label" for="company-name">Company name</label>
					<div class="col-md-4">
						<input class="form-control input-md" id="company-name" name="company-name" placeholder="You company" required="" type="text">
					</div>
				</div><!-- Text input-->
				<div class="form-group">
					<label class="col-md-4 control-label" for="company-website">Company website</label>
					<div class="col-md-4">
						<input class="form-control input-md" id="company-website" name="company-website" placeholder="You company website" type="text">
					</div>
				</div><!-- Select Basic -->
				<div class="form-group">
					<label class="col-md-4 control-label" for="company-category">Company Category</label>
					<div class="col-md-4">
						<select class="form-control" id="company-category" name="company-category">
							<option value="Data Entry">
								Data Entry
							</option>
							<option value="Accounting &amp; Finance">
								Accounting &amp; Finance
							</option>
							<option value="Software Development">
								Software Development
							</option>
							<option value="Computer and IT">
								Computer and IT
							</option>
							<option value="HR &amp; Recruiting">
								HR &amp; Recruiting
							</option>
							<option value="Nonprofit &amp; Philanthropy">
								Nonprofit &amp; Philanthropy
							</option>
							<option value="Engineering">
								Engineering
							</option>
							<option value="Editing">
								Editing
							</option>
							<option value="Writing">
								Writing
							</option>
							<option value="Graphic Design">
								Graphic Design
							</option>
						</select>
					</div>
				</div><!-- Text input-->
				<div class="form-group">
					<label class="col-md-4 control-label" for="company-office">Office Address</label>
					<div class="col-md-4">
						<input class="form-control input-md" id="company-office" name="company-office" placeholder="Denton, Texas, 76205" required="" type="text"> <span class="help-block">City, State, Zip</span>
					</div>
				</div>
			</fieldset>
		</div>
	</div>
	<div class="row mb-3">
		<div class="col-md-12">
			<button class="btn btn-lg btn-primary btn-block" style="margin-top:1em" type="submit">Find your movies</button>
		</div>
	</div>
	<div class="loading-wrapper hidden row">
		<div class="loading col-md-6 col-md-offset-3">
			🎥
		</div>
		<div class="col-md-6 col-md-offset-3">
			<br>
			<em>retrieving birth records...</em>
		</div>
	</div>
	<div class="fighter"></div>
</form>
