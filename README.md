# StreamCast ![GitHub package.json version](https://img.shields.io/github/package-json/v/TheRealFakeAdmin/StreamCast?filename=node-src%2Fpackage.json&label=Client%20Version) ![Docker Image Version (tag)](https://img.shields.io/docker/v/airensoft/ovenmediaengine/latest?label=OME%20Version) ![Docker Image Version (tag)](https://img.shields.io/docker/v/_/nginx/alpine?label=nginx%20Version)

A private streaming platform built off OvenMediaEngine (OME), allowing playback from the web or any Cast device.[1]


## Nginx

Used for the reverse proxy linking the two parts, Express/Pug web app & OvenMediaEngine streaming server.


## Node

Express API and Pug front end for user-facing web app.


## OvenMediaEngine (OME)

OME low-latency streaming server for near real–time origin-to-user streams.


## Feature Targets

- [ ] Nginx Reverse Proxy
    - [ ] Web App access
    - [ ] OME Access
- [ ] OvenMediaEngine Server
    - [ ] OBS -> Server with RTMP
    - [ ] Server -> Client with WebRTC or LL-HLS (m3u8)
        - [ ] WebRTC
        - [ ] LL-HLS
- [ ] Express Web App
    - [ ] Log in Screen
    - [ ] Roll-Based Access Management
        - [ ] Admin
            - Manage Account Creation
            - Manage User Permissions
            - Manage Streams
            - Low-Level Server Controls
            - Everything Bellow
        - [ ] Streamer
            - Generate Stream Key
            - Everything Bellow
        - [ ] - User
            - View Stream (with invite code)
    - [ ] Enter Invite Code Screen
    - [ ] Stream Viewer
        - [ ] Cast Support
    - [ ] High-Level API
- [ ] Database?
