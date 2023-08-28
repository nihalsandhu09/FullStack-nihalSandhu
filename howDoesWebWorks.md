### How the Web works 
```
 how the web works provides a simplified view of what happens when you view a webpage in a web browser on your computer or phone.
 
 1): Clients and Servers 
 cmputers  connected to the internet are called clents and servers.

 * clients are the typical web user's internet-connected devices (for example, your computer connected to your wifi, or your phone connected to your mobile network)and we-accessing software available on those devices(usually a web browser like Firefox or Chrome).

 * server are computer that store webpage, sites, or apps. When a client device wants to access a webpage,  a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser


 The Client and server we've descrbed above don't tell the whole story. There are many other parts involved,and we'll describe them below.

 For now , let's imagine that web is a road.On one end of the road is the client, which is like your house. On the othher end of the road is the server, which is a shop you want to buy something from.

 In addition to the client and the server, we also need to say hello to :

 * Your internet connection: Allows you to send and receive data on the web. it's basically like the street between your house and the shop.

 * TCP/IP: Transmission control Protocol and Internet Protocol are Communication protocols that define how data should travel across the internet. This is like the transport mechanisms that let you place an order, go to the shop, and buy your goods. in our example, this is like a car or a bike (or however else you might get around).

 *DNS: Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address it can retrieve the website. The  Browser needs to find out which serveer the website lives on, so it can send HTTP messages to the right place  this is like looking up the address of the shop so you can access it.

 *HTTP: Hypertext Transfer Proctocol is an application protocol that defines a language for clients and servers to speak to each other. this is like the language you use to order your goods.

 *Component files: A website is made up of many different files, which are like the different parts of the goods you buy from he shop. these files come in two main types:

 1) Code files : Website are built primarily from HTML,CSS and Javascript, thought you'll meet other technologies a bit later.
 2) Assests    : this is a collective name for alll other stuff that makes up a website, such as image, music, Video,Word documents and PDF's
```

### So what happens , exactly? 
```
when you type a web addresss into your browser(for our analogy that's like walking to the shop):

1. The browser goes to the DNS server, and finds the real adress of that server that the websiote lives on (you find the address of the shop).

2. the browser sends an HTTP request to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). this message, and all other data sent between the client and the server, is ent across your internet connection using TCP/IP.

3. if the server approves the client's request, the server sends the client a "200 OK" message, which means "of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets(the shop gives you your goods, and you bring them back to your house).

4. the browser assembles the small chunks into a complete web page and dispays it to you (the good arrive at your door - new )
```