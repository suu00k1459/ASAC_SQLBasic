---
title: "Docker - image pull & tag"
datePublished: Sun Jan 12 2025 17:18:42 GMT+0000 (Coordinated Universal Time)
cuid: cm5tvq054000309lhcgzacvs5
slug: docker-image-pull-tag
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1736701610583/fcb5b01a-7e23-4285-a67a-d5611b82ad03.png
tags: docker, error-handling, docker-images, docker-pull

---

I have to use the docker in mac because oracle is not working in macOS.

But I have a problem with install image in docker.

## My wrong code

docker pull oracledb19c/oracle.19.3.0-ee

## What is wrong

I didn’t check the detail tag of it.

## How to fix the error

1. Enter the docker hub : [https://hub.docker.com/r/oracledb19c/oracle.19.3.0-ee/tags](https://hub.docker.com/r/oracledb19c/oracle.19.3.0-ee/tags)
    
2. Find the image what you want and click the “tag” page.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1736701515206/8e8563bb-9e25-4f4c-8056-f39d3abe7a80.png align="center")
    
3. Copy the code and put in your terminal
    

---

Thank you.