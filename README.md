# Extending Cookbooks

This is the repository dedicated for developing **Eloquent Tests**.

## Abstract / Description

The tests you write across all your cookbooks require as much or more effort than maintaining the cookbooks that you have written. Quite a bit of boilerplate code is required to verify all the recipes, resources, and helpers. This also means quite a bit of duplication between cookbooks.

In this workshop you will use techniques to bring eloquence to your cookbook’s tests by eliminating redundancy, rebuilding common patterns into helpers, and extracting those helpers into a portable library of code.

* Refactoring tests for elegance

* Crafting reusable testing resources and helpers

* Extracting testing resources into a Ruby gem


## Learner Requirements

Participants need a network-enabled laptop with a terminal that supports SSH.

* Windows 7+ through [Putty](http://www.putty.org/) or [Cygwin with OpenSSH](https://www.cygwin.com/).

* Mac OS X 10.11

* Ubuntu 14.04

It’s best that learners have some familiarity and comfort with the following:

* Completed Chef Essentials and Test Driven Cookbook Development or equivalent experience


## Agenda

* Introduction
* let
* shared_examples
* def_method
* shared_context
* alias_example_group_to
* Creating a Ruby gem
* Conclusion

## Published Content

The latest published version of these training materials are located as follows:

### Participant Guide

The participant guide is a PDF that contains the notes export from the content slides.

This content can be found here: CONTENT IS CURRENTLY IN DEVELOPMENT
### Instructor Kit

* All slides for each module

* Instructor Guide for you to learn from, practice with, and perhaps use as reference while teaching. The instructor guide contains the notes export from the content slides with additional instructor notes and lab setup instructions.

* Participant Guide

This content can be found here: CONTENT IS CURRENTLY IN DEVELOPMENT

### Screencast Videos

This content can be found here: CONTENT IS CURRENTLY IN DEVELOPMENT

## Known Issues

There are no known issues at this time

## Workstation Setup

These modules focus on getting learners engaged with the content as quickly as possible. A workstation is provided to the learners. Details about what the workstation looks like can be found in [WORKSTATION.md](WORKSTATION.md).

For us at Chef this workstation is currently being managed as a Amazon Machine Instance (AMI). This AMI is managed by Chef through the Training AWS Account.

* Eloquent Tests - CentOS 6.7 - 1.0.0 (ami-????????)

The AMI was generated with [Packer](https://github.com/chef-training/chefdk-fundamentals-image) and adheres to the following [policy](https://github.com/chef-training/chefdk-image/blob/master/cookbooks/workstations/recipes/eloquent_tests.rb). It is based on a Marketplace AMI so it cannot be made public. If you would like access to this AMI to deliver training please contact [training@chef.io](mailto:training@chef.io) the request that includes your Amazon Account Id.
