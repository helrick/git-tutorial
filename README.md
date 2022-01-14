# Git Tutorial

Git Tutorial for the Primers for Predocs course, January 2022

## Contents
[Prerequisites](#prerequisites)<br>
[Set-up](#set-up)<br>

## Prerequisites
* GitHub account which you can log in to
Record the email that is registered to your account in [settings](https://github.com/settings/emails). Feel free to add your institutional (i.e. EBI or Sanger) email address.

* Record of the email which is registered to your account:
    https://github.com/settings/emails 

## Set-up
Background: last summer, GitHub removed support for password authentication, requiring users to use a Personal Access Token (PAT) or to Authenticate with SSH. I prefer the SSH route so that's what I'll be showing, though other options are possible. This method requires you to generate an SSH-key for every machine from which you'll push code to GitHub (i.e. the cluster, your laptop, any VM). It also requires that when you copy a repository's URL (i.e. to clone it), you'll need to copy the SSH link rather than the HTTPS link (don't worry if none of this makes sense, we'll go over it).
