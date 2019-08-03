<p align="center">
    <a href="https://appwrite.io" target="_blank"><img height="60" src="https://appwrite.io/v1/images/github-logo.png" alt="Appwrite Logo"></a>
    <br />
    <br />
    <b>Simple Backend Server for your [Vue / Angular / React / iOS / Android / Flutter / *ANY*] Frontend App</b>
    <br />
    <br />
</p>

[![Docker Pulls](https://img.shields.io/docker/pulls/appwrite/appwrite.svg)](https://hub.docker.com/r/appwrite/appwrite)
[![Chat With Us](https://img.shields.io/gitter/room/appwrite/community.svg)](https://gitter.im/appwrite/community?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

---

**WORK IN PROGRESS - NOT READY FOR USAGE**

---

Appwrite is a simple to use backend for frontend and mobile apps. Appwrite provides client side (and server) developers with a set of REST APIs to speed up app development time.

Using Appwrite you can easily manage user authentication with multiple sign-in methods, database for storing and querying user and teams data, storage and file management, image manipulation and cropping, scheduled cron tasks and many other features to help you get more results in faster times and with a lot less code.

![Appwrite](public/images/github.png)

## Installation

Appwrite backend server is designed to run in a container environment. Running your server is as easy as running one command from your terminal. You can run Appwrite on your localhost using docker-compose or on any other container orchestration tool like Kubernetes, Docker Swarm or Rancher.

The easiest way to start running your Appwrite server is by running our docker compose file:

```bash
mkdir appwrite
    && cd appwrite
    && curl -o docker-compose.yml https://raw.githubusercontent.com/appwrite/appwrite/master/docker-compose.yml
    && docker-compose up -d --remove-orphans
```

## Getting Started

Getting started with Appwrite is as easy as creating a new project, choosing your platform and integrating its SDK in your code. You can esily get started with your platform of choice by reading one of our getting started tutorials.

* [Getting Started for Web](https://appwrite.io/docs/getting-started-for-web)
* Getting Started for Android (soon...)
* Getting Started for iOS (soon...)
* [Getting Started for Server](https://appwrite.io/docs/getting-started-for-server)

## Services

<table width="100%">
  <thead>
    <tr>
        <td><b>Service</b></td>
        <td><b>Description</b></td>
        <td><b>Tutotrials</b></td>
        <td><b>Docs</b></td>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Auth</td>
            <td>Manage user authentication using multiple signin methods and account recovery.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/auth" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Account</td>
            <td>Manage current user account. Track and manage the user sessions, devices and security audit log.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/account" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Users</td>
            <td>Manage and list all project users when in admin mode.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/users" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Teams</td>
            <td>Manage and group users in teams. Manage memebrships, invites and users roles within a team.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/teams" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Database</td>
            <td>Manage database collections and document. Read, create, update and delete documents and filter lists of documents colllections using advanced filter with graph like capebilities.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/database" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Storage</td>
            <td>Manage storage files. Read, create, delete and preview files. Manipulate your files preview to fit your app perfectly. All files are scaned by ClamAV and stored in a secure and encrypted way.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/storage" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Localisation</td>
            <td>Track users location, and manage your app locale based data.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/locale" target="_blank">API References</a></td>
        </tr>
        <tr>
            <td>Avatars</td>
            <td>Manage your users avatars, countries flags, browser icons, credit card symbols and generate QR codes.</td>
            <td></td>
            <td><a href="https://appwrite.io/docs/avatars" target="_blank">API References</a></td>
        </tr>
    </tbody>
</table>

## SDKs

Currently we are supporting a few SDK libraries and we are constantly working on adding new ones.

Below is a list of currently supported platforms and languages. If you wish to help us add support to your platform of choice you can go over to our [SDK Generator](https://github.com/appwrite/sdk-generator) project and view our contribution guide.


<table width="100%">
  <thead>
    <tr>
        <td><b>Framework</b></td>
        <td><b>Language / Platform</b></td>
        <td><b>Maintainers</b></td>
        <td><b>Official?</b></td>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>[ANY]</td>
            <td><a href="https://github.com/appwrite/sdk-for-php">PHP</a></td>
            <td>Appwrite Team</td>
            <td>✅</td>
        </tr>
        <tr>
            <td>[ANY]</td>
            <td><a href="https://github.com/appwrite/sdk-for-js">Javascript</a></td>
            <td>Appwrite Team</td>
            <td>✅</td>
        </tr>
        <tr>
            <td>[ANY]</td>
            <td><a href="https://github.com/appwrite/sdk-for-ruby">Ruby</a></td>
            <td>Appwrite Team</td>
            <td>✅</td>
        </tr>
        <tr>
            <td>[ANY]</td>
            <td><a href="https://github.com/appwrite/sdk-for-python">Python</a></td>
            <td>Appwrite Team</td>
            <td>✅</td>
        </tr> 
        <tr>
            <td>[ANY]</td>
            <td><a href="https://github.com/appwrite/sdk-for-node">Node JS</a></td>
            <td>Appwrite Team</td>
            <td>✅</td>
        </tr> 
    </tbody>
</table>

## Contributing

All code contributions - including those of people having commit access - must go through a pull request and approved by a core developer before being merged. This is to ensure proper review of all the code.

Fork the project, create a feature branch, and send us a pull request.

For security issues, please email security@appwrite.io instead of posting a public issue in GitHub.