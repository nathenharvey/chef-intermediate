* Update Nathen's Intro slide
* Unhide Nathen's Intro slide
* Rename the webserver role s/webserver/web
  * See also https://github.com/learnchef/chef-fundamentals-repo/tree/london-2015
* Download chef-fundamentals-repo-london-2015
* Have the students rename the unzipped directory to `chef-repo`
* Remove duplicate slide "Exercise: Create and populate a .chef directory"
* No more "Enterprise" Chef.  Switch to "Hosted Chef" or just "Chef" as appropriate
* Add an exercise to set-up hosted Chef access - give them time to do on their own
* Add an exercise to bootstrap the node - give them time to do on their own
* Add the role during bootstrap
* Layout changes for the knife bootstrap sequence
* Hide some slides since we specified the role during bootstrap
* Add note about using chef generate for the lwrp
* Add a slide about grabbing the london-2015 branch of the chef-repo
* Add slides for AWS-based lab, including bit.ly to a gist
* Hide the Cloudshare lab setup
* Add a review of multiphase execution
  * cribbed from fundamentals
  * befor talking about use_inline_resources
* Skip the chef-shell section
* Add the ohai plugin recipe to the web role, not directly to the run list.
* Add instructor notes suggesting to go through the ohai logic in irb
* Skip the chef-shell debugging of ohai plugins
* Add link to docs that describe lazy evaluation
* Upgrade to version 2.0.1 of the ohai cookbook
* use `chef` to generate the email_handler cookbook
* chef generate an attribute file for the email_handler cookbook
* use `chef` to generate the mailx cookbook
* Update formatting of slide showing cookbooks/email_handler/metadata.rb
* Upgrade postfix cookbook to version 3.6.2
* Skip the installation of foodcritic, it comes with ChefDK
* Update the way to skip foodcritic rules:  put them in a .foodcritic
* Skip the installation of rubocop, it comes with ChefDK
* Update rubocop output
* Remove auto-gen-config options from rubocop, it seems to be broken
* Skip the installation of chefspec, it comes with ChefDK
* Make the spec directory before writing any files into it
* Add a Test-Driven Infrastructure with Chef slide
* Update some URLs in the further resources section
* Update the ChefConf image
* Update the ChefSpec code
* Update verstion to 1.1.6
* Update Nathen's intro slideA
* from irb to pry
* Add a slide for chef-client -l debug
* Update the url of the report handler
* Update George's email
* Add notes about not creating a default_action for the lwrp
* Restore rubocop workflow stuff
