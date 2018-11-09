#### Docker-Mastery notes

### Section 1

## Why Docker?

Containers are the next once-in-a-decade shift in infrastrucutre and process that make or break you.

Let's Recap
Major Infrastrucutre Shifts:

- Mainframe to PC
    - 90's
- Baremetal to Virtual
    - 00's
- Datacenter to Cloud
    - 10's
- Host to Container (Serverless)
    - Now

Like all these shifts, migrating is the hard part. We need to learn new terminology and move infrastructure.
Yet, unliek previous shifts, Docker is focused on the migration experience. Built for developers, sysadmins, ops teams etc.

Containers are the "Fastest Growing Cloud Enabling Technology"

> Fun Fact:
> - @Moby Dock is the logo.
> - @GordonTheTurtle is the mascot

Docker is all about speed.
- Develop Faster
- Build Faster
- Test Faster
- Deploy Faster
- Update Faster
- Recover Faster

The "Matrix from Hell" Breeds Complexity. Each website, database, queues have different environments and.
Containers allows us to run and test the software anywhere we are running it: cloud, windows, linux etc.

Maintenance and complexity drains budgets, so innovation suffers.

There are a lot of major companies that use Docker today.

Examples:
![paypal](paypal.png "Paypal statistic")
![metlife](metlife.png "Metlife statistic")

https://landscape.cncf.io/format=landscape
![landscape](landscape.png "Landscape.cncf.io")

git clone https://github.com/BretFisher/udemy-docker-mastery.git


![docker-cheatsheet](docker-cheatsheet.png "Docker cheat sheet")

### Section 2
Docker Editions
- Docker is no longer just a"container runtime"
- Docker moves fast, it matters how you install it
- Docker CE (Community Edition)
- Three major types of installs: Direct, Mac/Win, Cloud
- Linux (different per distro)(don't use default package)
- Docker for Windows (or legacy Docker Toolbox)
- Docker for Mac (or legacy Docker Toolbox)(don't use brew)
- Docker for AWS/Azure/Google