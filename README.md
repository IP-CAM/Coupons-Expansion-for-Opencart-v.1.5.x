OpenCart-Coupons-Expansion
==========================

Installation:

1. In phpMyAdmin or another MySQL client, execute the query:
ALTER TABLE `oc_coupon` ADD` discount_plan` TEXT CHARACTER SET utf8 COLLATE utf8_bin NOT NULL AFTER `discount`
Notice your OpenCart table prefix. If necessary, change the 'os_' in the request to your prefix.

2. Make a backup copy of the files that the module overwrites

3. From the 'upload' folder for OpenCart versions 1.5.3.x and 1.5.4.x and from the 'upload' folder for 1.5.1.x copy the module files to the site

For instructions on working with cumulative discounts, see the website: http://sourcedistillery.com/nakopitelnye_skidki_v_opencart.html 
