# exdortes

----
## what is exdortes?

> example app to train express, docker kubernetes, aws and nginx, couchbase


----
## todo

### AWS
1. use free tier instance
* create 3 instances:
 * nginx - public
 * couchbase - private
 * express service - private



### nginx
1. setup nginx for loadbalancer (gateway)
*. download alpine, configurate
*. create dockerfile

### couchbase
1. install couchbase
2. configure it
3. create dockerfile

### express
1. make simple app which include:
 * todo list
 * connect couchbase db 
* use alpine version of Node
* create dockerfile 

**Bonus**

   * restricted area (need auth, include JWT)
   * handle customize responses (500, 404 ...)


### kubernetes
 1. create infrastructure for our webapp
 2. use terraform


----
## markdown quick reference
# headers

*emphasis*

**strong**

* list

>block quote

    code (4 spaces indent)
[links](http://wikipedia.org)

----
## changelog
* 17-Feb-2013 re-design

----
## thanks
* [markdown-js](https://github.com/evilstreak/markdown-js)

