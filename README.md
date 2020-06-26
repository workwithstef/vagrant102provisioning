# User Installation

## Prerequisites
		- Ruby (at least v2.6) & Bundler
		- VirtualBox
    - Vagrant

## Steps

1) Clone repo
	- Provides you with a copy of provisioning-starter-code
2) Open git bash / equivalent
3) `$ cd starter-code`
4) `$ vagrant up`
	- Starts up VM server (will take some time)
	- Check it is present / running in VirtualBox Manager

5) `$ cd environment/spec-tests`
6) `$ rake spec`
	- To initialise and perform set tests
	- EXPECTED: 9 EXAMPLES, 0 FAILURES
7) `$ vagrant ssh`
8) `$ cd /app`
9) `$ npm start`
	- 'Your app is ready and listening on port 3000'
10) In browser, go to ip:port
	- 192.168.10.100:3000
	- Welcome to the Sparta Test App

### Feedback

- BE MORE DESCRIPTIVE
- BE SPECIFIC WITH DIRECTORY LOCATIONS
- put manual in main README
- list steps to run tests
- explain how to reach website
