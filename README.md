# Snyk Application Security Hands-On Workshop

Snyk Code and Snyk Open Source together provide easy-to-use, fast and accurate SAST and SCA testing, enabling developers and security teams to easily find and fix both security issues in their own proprietary code as well as known vulnerabilities in their open source dependencies, reducing risk and improving the pace of development

## Prerequisites

* public GitHub account - http://github.com
* git CLI - https://git-scm.com/downloads
* snyk CLI - https://support.snyk.io/hc/en-us/articles/360003812538-Install-the-Snyk-CLI
* Registered account on Snyk App - http://app.snyk.io

## What we will do in this hands-on workshop?

In this workshop we will use the Snyk Platform to monitor and perform application security scans across various different artifacts in the repository. This workshop will focus on Snyk Open Source and Snyk Code capability.

* Step 1 - Fork our sample repo into your own GitHub account
* Step 2 - Configure GitHub Integration
* Step 3 - Analyze Snyk Open Source Scan Results
* Step 4 - Analyze Snyk Code Scan Results 
* Step 5 - Fix a Vulnerability Using Snyk's Pull Request feature
* Step 6 - Perform Snyk Test Using Snyk Open Source
* Step 7 - Perform a Snyk Test Using Snyk Code
* Step 8 - Using Snyk VS Code IDE Plugin

# Workshop Steps

_Note: It is assumed your using a mac for these steps, but it should also work on Windows or linux with some modifications to the scripts potentially_

## Step 1 - Fork our sample repo into your own GitHub account

Navigate to the following GitHub repo - https://github.com/papicella/snyk-boot-web

* Click on the "**Fork**" button
* Ensure you are forking this repo to your public GitHub account
* Click done

![alt tag](https://i.ibb.co/JdvF8pP/app-sec-snyk-workshop-1.png)

## Step 2 - Configure GitHub Integration

_NOTE: You may have already setup GitHub integration in that case go ahead and skip this step_

* Login to http://app.snyk.io Sign up if you haven't already.
* Navigating to Integrations -> Source Control -> GitHub
* Fill in your Account Credentials to Connect your GitHub Account.

![alt tag](https://i.ibb.co/bPqqybM/snyk-starter-open-source-1.png)

Now that Snyk is connected to your GitHub Account, import the Repo into Snyk as a Project.

* Navigate to Projects menu option
* Click "**Add Project**" then select "**GitHub**"
* Click on the Repo you forked.

![alt tag](https://i.ibb.co/q9Rsxsh/snyk-starter-open-source-3.png)

![alt tag](https://i.ibb.co/f9JsRQX/app-sec-snyk-workshop-2.png)

_Note: The import can take up to one minute so you can view the import log while it's running _

![alt tag](https://i.ibb.co/ZMZBNjR/app-sec-snyk-workshop-3.png)

The scan should not take longer then a few minutes once complete more onto the nxt step below

## Step 3 - Analyze Snyk Open Source Scan Results

TODO://

## Step 4 - Analyze Snyk Code Scan Results

TODO://

## Step 5 - Fix a Vulnerability Using Snyk's Pull Request feature

TODO://

## Step 6 - Perform Snyk Test Using Snyk Open Source

TODO://

## Step 7 - Perform a Snyk Test Using Snyk Code

TODO://

## Step 8 - Using Snyk VS Code IDE Plugin

TODO://



Thanks for attending and completing this workshop

![alt tag](https://i.ibb.co/7tnp1B6/snyk-logo.png)

<hr />
Pas Apicella [pas at snyk.io] is a Principal Solution Engineer APJ at Snyk
