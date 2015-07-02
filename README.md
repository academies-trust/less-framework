# less-framework


## Installation

Run the following

	bower install less-framework --save

At the top of your **app.less**, include the **standards**. In a standard installation of Laravel 5.1 this looks a little something like this:

	@import "../../../vendor/bower_components/less-framework/standards";

The next time you run **gulp**, the standards will be imported.


## Usage

Please view the wiki to find information on the included components: https://github.com/academies-trust/less-framework/wiki/

This package uses bootstrap grid, the documentation of which can be found here: http://getbootstrap.com/css/#grid


## Overriding

**It is recommended that you do not update the files in the framework directly, as they will be overwritten when an update is published.**

Instead, you should create a **modules** and/or a **components** folder within your *resources/assets/less*. Include any of these within your app.less.