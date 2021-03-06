# Wordpress on DigitalOcean

## Purpose
The intent of this repository is to provide lifecycle management of a WordPress site on DigitalOcean. This repo is part of an ongoing [blog series](https://chasberndt.com) I'm working on. In time, I hope others will find this useful.

## Status
This is very much a work-in-progress and should not be used by anyone at this point. ***Be warned!***

## Technologies Leveraged
* Ansible (2.9)
* Shell Scripts
* Python 3
* Requests

## Goals
Below is a list of the goals of this project along with their current status. Additionally, the goal is to learn how to leverage DigitalOcean's APIs and create a fault-tolerant WordPress website with HA/DR.

* [done] Create a droplet via Ansible.
* [done] Create a block storage volume via Ansible.
* [done] Attach a block storage volume to a droplet.
* [done] Replace droplet and re-attach block storage volume.
* [done] Destroy a droplet and block storage volume.
* [done] Create managed MySQL instance via Ansible.
* [done] Install and configure Apache.
* [done] Install WordPress.
* [done] In-place upgrade of WordPress.
* [done] Automatic backup of WordPress site.
* [done] Harden droplet against common attacks.
* [done] Configure SSL on droplet.
* [done] Configure monitoring.
* [future] Attach droplet to load balancer.
* [future] Configure SSL on load balancer.
* [future] Configure HA WordPress.

## Contribution
Sorry, this repo isn't open to contribution, but let me know if you find this useful. My intention is to move on to do something similar on top of AWS and Azure so eventually I will open this up to accepting outside contributions.

## License
Copyright 2020 Chas Berndt

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
