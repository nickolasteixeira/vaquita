# Vaquita - GitHub Contribution Panel project

## Introduction

Thanks for visiting our project, Vaquita. This is our web application that allows a user to connect to Github and (securely) display commit activities of all a user’s repositories if they provide their GitHub credentials using OAuth. This app was created in a 1 day hackathon with fellow Holberton students at https://www.holbertonschool.com/

 - The login request is forwarded to GitHub's OAuth(1) login. If the Github credentials are valid, a token is stored as a cookie on the user's local computer for future logins until its expiration.

 - The User's GitHub username and their list of their Public and Private GitHub repositories will be displayed.

 - When the user clicks on a specific repository, their commit contribution grid will be displayed. The grid serves as a heatmap indicating the number of commits made to the repository for that project in the last 12 months. The darker the color, the higher number of commits.

## Table of Contents
* [Environment](#environment)
* [Installation](#installation)
* [Usage](#usage)
* [Marketing](#marketing)
* [Credits](#credits)

## Environment

* Javascript - JQuery (v3.2), HTML/CSS
* Flask - Gets access token
* Nginx - SSL Certification to serve HTTPS content
* UFW - firewall
* Any web browser
* Python3 (v3.4.3)
* Ubuntu (v14.04 LTS)

## Installation

There is no self-install script. The Nginx web server is a basic configuration.
The firewall will need to pass HTTP, HTTPS, SSH, and TCP traffic through.

## Usage

Once the website is up, use a web browser to go to the home page to see a single button for login.

Click on a specific repository link to view the commit history and a contribution panel covering the last 12 months will appear.

## Marketing

An imaginative press release was written for this project for your amusement.

## Credits
