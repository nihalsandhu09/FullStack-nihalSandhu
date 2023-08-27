## how does the Internet work? 
```  
 The internet is the backbone of the web, the technical infrastructure that makes the web possible. At its most basics,the internet is a large network of computers which communicate all together . 
 
 first we need to know history of internet ? 

 how internet found 

it began in 1960s as a US-army-funded research project, then evolved into a public infrastructure in the 1980s with the support of many public univertes and private companies.the various technologies that support the internet have evolved over time, but te way it works hasn't changed that much:Internet: is a way to connect computes all togerther and ensure taht,whatever happens, they find a way to stay connected.


deeper dive 

1): A simple network 

when two computers need to communicate, you have to link them either pyhsically (usually with an Ethernet cable) or wirelessely (for example with Wi-Fi or Bluetooth systems). All modern computers can sustain any of those connections.

Such a netwrok is not limited to two computers.You can connect as many computers as you wish.but it gets complicated quickly. if you are trying to connect,say,ten computers, you need 45 cabels,with nine plugs per computer!

To solve this problem, each computer on a network is connected to a special tiny computer called a router.this router has only one job:like a signaler at a railway station, it makes sure that a message sent from a given computer arrives at the right desination computer. To send a message to computer B, computer A must send the message to the router,  which in turn forwards the message to computer B and Make sure the Message is not deliverd to computer C.

once we add a router to the system ,our network of 10 cpmputers only requires 10 cables:a single plug for each computer and a router with 10 plugs


2): A NETWORK OF NETWORKS 

SO far so good. but what about connecting hundreds, thousands, billions of computers? of courses a single router can't scale that far, But, if you read carefully, we said that a router is a computer like any other, so what keeps us from connecting two routers together? nothings , so lets do that.By connecting computers to routers, then routers to routers , we are able to scale infinitely.

Such a network comes very close to what we call the internet, but we are missing somethinf. we built that network for our own purposes. There are others networks out there: your friends,your neighbors, anyone can have their own network of computers. but it's not really possible to set cables up bgetween your house and the rest of the world, so how can you hancle this?well , there are already cables linked to your house, for example, electric power and telephone. The telephone infrastructure already connects your house,for exapmle,electric power and tlephone infrastructure already connects your house with anyone in the world so it is the perfect wire we need To connect our network to the telephone infrastructure, we need a special piece of equipment called a modem.This modem turns the information from our network manageable by the telephone infrastructure and vice versa 

So we are connected to the telephone infrastructure. the next step is to send message from our network to the network we want to reach. to do That,we will connect our network to an Internet Service Provider(ISP).An ISP is a company that manages some special routers that are  all linked together and can also access other ISPs' routers. SO the message from our network is carried through the network of ISP networks to the destinations network. the Internet consist of this whole infrastructure of networks.


3): FINDING COMPUTERS 

if you want to send a message to a computer, you have to specfy which one. thus any computer linked to a network has a unique address that identifies it , called an "IP address" (where IP stands for Internet Protocol).it's an address made of a series of four numbers separated by dots,for example"192.0.2.172

that's perfectly fine for computers, bvut we human beings have a hard time remebering that sort of address. To make things easier,we can alias an IP address with a human-readable name called a domain name. For example(at the time of writing:IP addresses can change) google.com is the domain name used on top of the IP address 142.250.190.78. So using the domain is the easiest way for us to reach a computer over the internet


4): INTERNET AND THE  WEB 


As you might notice, when we browse the Web with a Web browser, we usually use the domain name to reach a website. Does that mean the Internet and the Web are the same thing? It's not that simple. As we saw, the Internet is a technical infrastructure which allows billions of computers to be connected all together. Among those computers, some computers (called Web servers) can send messages intelligible to web browsers. The Internet is an infrastructure, whereas the Web is a service built on top of the infrastructure. It is worth noting there are several other services built on top of the Internet, such as email and IRC.

Intranets and Extranets
Intranets are private networks that are restricted to members of a particular organization. They are commonly used to provide a portal for members to securely access shared resources, collaborate and communicate. For example, an organization's intranet might host web pages for sharing department or team information, shared drives for managing key documents and files, portals for performing business administration tasks, and collaboration tools like wikis, discussion boards, and messaging systems.

Extranets are very similar to Intranets, except they open all or part of a private network to allow sharing and collaboration with other organizations. They are typically used to safely and securely share information with clients and stakeholders who work closely with a business. Often their functions are similar to those provided by an intranet: information and file sharing, collaboration tools, discussion boards, etc.

Both intranets and extranets run on the same kind of infrastructure as the Internet, and use the same protocols. They can therefore be accessed by authorized members from different physical locations.



```