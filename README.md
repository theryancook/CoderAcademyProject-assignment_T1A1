## T1A1 Workbook - Ryan Cook

### Q1 - Research the development of the internet from 1980 to today. You must describe at least FIVE key events in the development of the internet. You can refer to events, people of significance, or technologies and how they have changed over time.

It’s difficult to narrow it down to only 5 key events in the development of the internet from 1980 until today, however, I will delve into a little more detail on 5 *interesting* topics.

DNS was an early key development in how the internet operates as we know it today. Standing for Domain Name System, it operates as a large interconnected system of servers all over the globe, containing a distributed database of domain names and IP addresses. Whenever you type an internet address into your browser ie www.ryancook.com, it’ll use a DNS server to resolve the IP address of that website’s server. This will enable your local machine to contact the website’s server, and display the information to you.

In 1989, we saw the launch of the first commercial Internet Service Providers (ISPs). The very first was known as ‘The World’. The internet was initially ‘dial up’, and ran through phone lines. It was excruciatingly slow, and was nothing like it is today. Due to the low capacity of data transfer, there was not much available to users at that time and websites didn’t offer much in terms of functionality, but it brought the internet into people’s homes for the first time. Until ‘The World’ launched, ISPs were actually banned by the US Federal Government as the internet was reserved for the government only. After the initial success of ‘The World’, we saw other household names begin to rise such as AOL.

In 1991 we had our first "web" page hosted on the internet. This was created by a CERN employee by the name of Tim Berners-Lee and the address was "http://info.cern.ch". Funnily enough, the content of this initial web page was to actually describe what the "World Wide Web" was and how it worked on the internet. Other names were thrown around at the time, such as "Mine of Information" and "Information Mesh", but they don’t really have the same ring as "World Wide Web", do they? The idea was hashed out of the frustration of not being able to collaborate on projects, and that information was often locally hosted on different physical machines using different programming languages. Berners-Lee, having worked on foundational technologies such as HTML, HTTP and URL, finally launched his initial site in 1991. Also interestingly, against advice, he decided against commercialising his idea much to the benefit of society.

Still in the 90s, and in 1998 we had the launch of Google. Just about everyone in the world knows what Google is, and is these days considered to be a verb. Just Google it! But Google wasn’t the first search engine. So, what made it that much better than all the competitors? Google was fast - faster than the rest. You ever notice that Google *used to* write at the bottom how fast they return results? It had a really deep index - we just searched 10 *bazillion* sites for these results. It’s results were extremely relevant (I personally think this was key above all else). It was simple to use - 1 box, type in anything, and bingo. Finally, it’s technology just managed to stay that far above the competition, no matter how much time went past.

Mobile web has been around since the late 90s, but was really popularised with the launch of the iPhone in 2007. Technologies were much evolved by that time, and people who didn’t have access to the internet previously (think isolated communities in 3rd world countries) now had an incredible amount of communication ability all based on something that fit into their pocket. Mobile internet usage has surpassed that of desktop usage since 2018 and that trend looks to continue for the near future.

### Q2 - Define the features of the following technologies that are essential in terms of the development of the internet:
### - packets
### - IP addresses (IPv4 and IPv6)
### - routers and routing
### - domains and DNS

### Explain how each technology has contributed to the development of the internet.

#### Packets
Packets are little pieces of information that is sent between an origin and a destination to allow communication over a network. When any data is sent via a network such as the internet, it’s broken up into little pieces (packets) to allow for more efficient transmission of the data. A protocol exists (TCP) for breaking up, and reassembling these chunks of data.

#### IP addresses (IPv4 and IPv6)
Similar to how we have postal addresses, every internet connected device has an IP address. This allows devices to have a unique ID, whereby information can be sent via the internet. Originally, the protocol was IPv4 which was created using 32 binary bits. As the amount of devices connected to the internet exploded, there was some worry we’d run out of unique IP addresses and IPv6 was born using 128 binary bits. IPv4 addresses are expected to be exhausted in 2020.

#### Routers and routing
Routers are hardware devices that enable computers (in a home network for example) to be connected to the internet. The router creates a network in the home (could be 1 PC, could be multiple devices connected in the network such as phones, TVs etc) and connects that network to the internet via a modem. Routers often have some form of security capabilities such as a firewall. Ultimately, routers facilitate the transfer of the packets discussed before, and decide which is the best route for them to take the reach their destination.

#### Domains and DNS
DNS or Domain Name System is commonly acknowledged to be the phonebook of the internet. Whenever you type in a domain name (such as www.google.com) the DNS will translate that into an IP address, which will let it find the appropriate place on the internet to connect to and do so. This is important as it saves humans from having to remember long strings of numbers in order to connect to websites which could be as complex as 2400:cb00:2048:1::c629:d7a2 in the case of an IPv6 address. Simply, this lets people access websites far more easily than would be otherwise possible.

### Q3 - Define the features of the following technologies that are essential in terms of the development of the internet:
### - TCP
### - HTTP and HTTPS
### - web browsers (requests, rendering and developer tools)

### Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

#### TCP
TCP stands for Transmission Control Protocol. While we discussed previously that an IP address is like the street address to all devices that are connected on the internet, the TCP is a standardised way to send the information between the different devices. It was important to develop a standardised system for how computers are able to communicate and send information. This establishes in what format the information is sent, how much information, how to interpret the information, as well as how to put the information back together again to be useful.

#### HTTP and HTTPS
HTTP is another protocol, but this one lets you fetch resources through the internet. It is known as a client server protocol as the requests are initiated by the recipient. Generally, these requests would be made by a web browser, on behalf of someone who’s browsing the internet. The protocol would, for example, get all the information held within an HTML file, and let the browser render the information in a specific way. HTTPS then later followed HTTP, with the S standing for secure. What this now meant was that information sent via HTTP is now encrypted. Why this was so important, was that previously anyone on a network (say in an internet cafe) could ‘sniff’ the packets sent via HTTP and read them in plain text. With the new HTTPS, if someone were to sniff the packets of data on my network, they’d be now presented with a nonsensical string of characters that can’t be interpreted by a human.

#### Web browsers (requests, rendering and developer tools)
A web browser does many things. Firstly, it takes all of the information we’ve just discussed being sent through networks via HTTP etc and renders that in such a way that it’s usable to whoever is using the web browser. Although there are several different companies who build these tools, they all comply with accepted web standards to ensure the information is accessible to all people who are on the internet. How the browser specifically makes a request is as follows. 1) Uses the DNS lookup 2) Browser sends an HTTP request to the IP address 3) Servers responds, sends back HTML file 4) The browser then renders that HTML file 5) The browser then requests additional information such as any Javascript, CSS etc required. Browsers also have inbuilt developer tools, which let you then explore on a deeper level the HTML etc that has been rendered by the browser. You can see the core HTML, CSS and different elements of the page, enabling web users to see what’s going on under the hood.

#### TCP
Before the invention of TCP, every single computer and hardware manufacturer had to come up with their own system for communicating with other computers, and generally this wasn’t compatible with computers from other vendors. It wasn’t until there was an industry standard, computers from all different vendors were more easily able to be connected onto the same network.

#### HTTP and HTTPS
There were a couple of reasons that led to HTTP becoming the common standard. Firstly, it was simple and able to be read by humans. This enabled people to get involved in the development more easily. HTTP is very extensible, and this meant that as other improvements have been made to the internet, HTTP was able to add the encryption in HTTPS and also able to incorporate things such as video and javascript into web pages.

#### Web browsers (requests, rendering and developer tools)
The development of the web browser can not be understated. Prior to web browsers, along with their associated web standards, it was difficult for end users to navigate the internet efficiently. Nowadays, bowsers enable a very fast experience loading web pages. It made the internet very accessible - essentially anyone who knows how to type is able to access the internet via a web browser and it offers a more secure solution - modern browsers have inbuilt security functionality.

### Q4 - Identify THREE data structures used in the Ruby programming language and explain the reasons for using each.

Arrays can act as a base for more complicated types of data structures. Often they’re used for collecting items, or holding the results of information gathered from running processes. They can hold different types of information such as a string, integer or float. Arrays have index numbers associated with where the information is being held. In Ruby, you’re also able to apply built in methods to arrays.

Sometimes you don’t want the values to be indexed, and in that case you might be better off using a Hash. A hash is a collection of key & value pairs. Now, we’d use the key to access the value in the hash, not the index value. The value can be anything - it can be a string, or a number etc

A linked list is another data structure in Ruby. It contains elements that hold 2 pieces of information 1) the information itself and 2) a reference to the next information on the list. Linked lists are similar to an array, but carry out certain functions a lot faster than you’re able to with an array. The cons vs an array are that there’s no indexing, no random access, however, removing and adding data into the middle is a lot faster.

### Q5 - Describe the features of interpreters and compilers and how they are different.

A compiler is a computer program that takes a program or code written in a high level language such as Ruby or Javascript, and translates it into a lower leverage language that can then be used by the computer. This is all done before the program runs.

An interpreter works very similarly to a compiler. It also takes high level computer programs and makes them able to be run on computers, but the core difference is that it does not translate the code before the program is run. It does this as the code is running, so there’s one less step then if the code was compiled.

Compiled code tends to run faster than interpreted code. The ways that errors are handled is different - compiled code will display them all at the end, whereas interpreted will give the errors line by line.

### Q6 - Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.

One of the most widely used programming languages is Python. This language places a large focus on readability of the language itself. There are various benefits and drawbacks of this language. The benefits include but are not limited to: extensive support libraries which mean that most of the frequently performed tasks someone would code in Python are already scripted in. This reduces the amount of code that needs to be written when using the language. Integration features means that Python makes it easy to develop web services. It is a great option for building scalable multi-protocol network applications.

There do also exist several limitations and disadvantages to Python as well. Even though Python is widely recognised as a language that’s easy to learn and use, it’s not widely used in the enterprise software development world. We talked about how the libraries were such a strength, but when going back to code in other languages, people can often forget the intricacies of other less easy to use languages. While it’s very popular for desktop and server use, it’s regarded as being a weak language for mobile development. Python executes with the help of an interpreter instead of the compiler, which causes it to slow down because compilation and execution help it to work normally. 

Another widely used language in the programming world is Ruby. First we’ll take a look at some of the positives. It’s been said that it’s got a learning curve that isn’t as steep as some other languages, so you’ll be up and running using the language faster. For people who are new to coding, or perhaps starting a business and trying to develop an MVP, this can translate into getting an idea to market faster, or just saving time and money on development. There are hundreds of different helpful community-created “gems" and libraries that you can use as a part of your own software. Some of them can help you in debugging, some are a great help in optimization, and some are related to the testing stage of your work. What’s also great is the size of the active community surrounding Ruby (and of course, the Rails framework as well). This means that you can always ask for help if you’re just getting started, information is readily available, and as discussed above, the amount of “gems” available and also being released is pretty large.

Like with the case of Python, with Ruby, there are also some downsides to using the language as well. The one issue that gets raised time and time again is the boot time. The boot time of the framework is quite long, especially when you work with a massive project. Within the community, it's reportedly a poor choice for developing GUI.

### Q7 - Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue.

### List of topics containing ethical issues:
### - access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)
### - intellectual property, copyright, and acknowledgement.
### - criminal acts such as theft, fraud, trafficking and distribution of prohibited substances, terrorism
### - GPS tracking data and other types of metadata, MAC addresses, hardware fingerprints
### - freedom of thought, conscience, speech and the media
### - aggressive sales and marketing practices designed to mislead and deceive consumers
### - trading of shares on the stock exchange OR crypto-currencies

### For each ethical issue identify a source of legal information relating to the ethical issue and discuss whether the law is helpful in assisting a developer to act in an ethical way. (Word count guide: 200 words max)

### Conduct research into a case study of ONE of the ethical issues you have chosen discuss how an ethical IT professional should respond to the case study and how they might mitigate or prevent ethical breaches. (Word count guide: 400 - 600 words)

#### Access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)
I chose this particular ethical issue as it’s proved to be pretty topical over the past couple of years, with the introduction of the governments “My Health Record” (MHR). For context, in the past, often patient documents and information would be held in all different locations, often in non-digital formats that are hard to locate and share. The government brought out MHR so that regardless of which medical practitioner you see, they’ll have access to all your information to best treat your condition.

This means that we’re dealing with highly sensitive data. People do have to specifically op into the service, so there’s no one forcing them to.

Like many other services or applications that deal with highly sensitive data, there is a high degree of responsibility placed on the shoulders of the IT professionals who build and then manage the system. IT professionals here have an ethical responsibility to ensure that the data is as secure as possible. There’s functionality so that specific information is available to specific people and/or medical professionals. If any information or data is accessed, despite the fact it should be hidden, and it’s the fault of the developer or individual maintaining the system, then the responsibility lies with them.

There’s another way in which private and confidential information may become available, and that’s through hacking. Again, IT individuals must also take some responsibility here. If all reasonable steps are taken by IT professionals in terms of security etc, then they should not be responsible. Hacks are often a result of vulnerabilities in other software packages such as operating systems. In this event, then the IT professionals should not be held responsible for any data breach. Having said that, there’s also ways to ensure data is secure despite other system breaches so IT professionals should endeavour to incorporate these as well.

In terms of how laws that are in place assist IT professionals making decisions, on the ATO website concerning data security (a good comparison for MHR with sensitive data), the ATO has specifically referenced Australian Privacy Principles, contained in schedule 1 of the Privacy Act 1988 (Privacy Act). It goes on to say that there are 13 Australian Privacy Principles that govern standards, rights and obligations around:
* the collection, use and disclosure of personal information
* an organisation or agency’s governance and accountability
* integrity and correction of personal information
* the rights of individuals to access their personal information
It goes on to say that The Australian Privacy Principles are principles-based law. This gives an organisation or agency flexibility to tailor their personal information handling practices to their business models and the diverse needs of individuals. They are also technology neutral, which allows them to adapt to changing technologies. A breach of an Australian Privacy Principle is an ‘interference with the privacy of an individual’ and can lead to regulatory action and penalties.

I believe these are strong guidelines to guide the actions of IT professionals.

#### Trading of shares on the stock exchange OR crypto-currencies
Again, another topical issue of late, is the issue of crypto currency trading.

What we’ve seen happen in several incidents over the past couple of years, is that someone opens a bitcoin exchange or a bitcoin wallet. It’s marketed at individuals who are looking to trade and store their cryptocurrencies. Then once there’s a certain amount of crypto currencies in that company’s wallet, it vanishes. It’s extremely hard to track down who’s responsible, because the nature of crypto currencies means that they’re anonymous.

The industry is largely unregulated - there’s no laws that govern what a crypto currency is, how they’re to be bought and sold etc but actions such as the one above, are still illegal. 

When you’re specifically looking at the role of an IT professional, it’s their ethical responsibility to develop and operate a system where the chance of this is minimized. While it’s impossible to know whether you’ll encounter a rogue business operator or employee, there are measures that can be put in place to minimise the amount of access one individual may have to be able to steal crypto currency. It is an IT professionals duty to ensure the system is maintained and has an appropriate level of up time for users who wish to trade. It needs to be extremely secure, much in the same way a bank’s systems need to be secure.

While an IT professional can take all reasonable steps to ensure how secure and well maintained a system is, if there is a 3rd party from either within or external to the organisation that accesses the information and steals the crypto, as long as all reasonable measures were taken, those IT professionals cannot be held responsible. We’ve seen ‘social hacking’ result in lost funds, as well as people being ripped off by unscrupulous vendors, neither of which can be helped by the IT professionals.

Laws:
As discussed earlier with specific reference to Bitcoin - it’s largely unregulated. There are some laws which you must adhere to, for example, any realised profits are treated as taxable income by the ATO and therefore tax must be paid. On the community website bitcoin.org, it does have some information as well as links to a community agreed upon list of ethics, places to discuss the development, acknowledgement of communities and individual developers etc.

Despite the fact there are few laws, the community is attempting to self regulate and do the best by the rest of the community. This does help IT professionals have some guidance in making decisions.

#### Conduct research into a case study of ONE of the ethical issues you have chosen discuss how an ethical IT professional should respond to the case study and how they might mitigate or prevent ethical breaches.
In a case that definitely draws parallels to the issues discussed at the launch of MHR, a private cardiology practice based in Melbourne was the victim of a ransomware attack. It was a classic ransomware style attack, whereby the highly sensitive and valuable information is encrypted and only unlocked once the victim pays a ransom. It’s estimated that around 50% of ransomware attacks are targeted at healthcare institutions which means that attackers are very aware of the value of the information and institutions likelihood to pay. This is combined with the fact that often the computer systems of a such institutions, such as a hospital, are very hard to protect as there’s often a lot of integrated systems communicating together. There’s value for the hackers in the ransom, and due to the nature of the information, information could also be sold onto other 3rd parties on the dark web for a hefty fee as well.

To add further complexity to the issue, it’s almost impossible to trace and find the perpetrators. Even if they are found, depending on jurisdiction, it can be even harder to bring any charges.

The article also makes a couple of points which I think are relevant for IT professionals. It stressed the importance of having several system and data back ups, all of which are distributed separately (even offline). While this might not solve the issue of the data being stolen, it solves the issue of not being able to access it if it’s encrypted by a hacker.

Another key takeaway for IT professionals is that, as much as they can implement strong cyber security, continually to invest in new systems, it’s also important to educate users on the best practices for usage. Sometimes all it takes is one user to have their password written down and found, or for it to be left as the default, and that can be enough to bring down the whole system.

### Q8 - Explain control flow, using an example from the Ruby programming language

Control flow refers to the order in which instructions are run and executed by a program. The control flow statements determine which part of the program is being run at any given time. In Ruby, we’ll look at an if/else statement. Here, we’d make a statement such as 

```ruby
puts “please enter a number”
gets.chomp.to_i = x

if x > 0 
    puts “positive”
else
    puts “negative or zero”
end
```

In this statement, we’ve asked the user to enter some information (a number). As we move through the program, the control flow first would test to see whether this agrees or disagrees with the first if statement. If yes, the condition is met and it will print that specific string we’ve said to print and end the program. If it does not agree with the initial statement, it will move onto the 2nd statement. Since we’ve used else, it does not need to test against any argument, it simply knows to print the 2nd message, but only does so if the initial argument is not satisfied.

### Q9 - Explain type coercion

Type coercion is being able to convert some data from one data type into another data type. Using some concrete examples that one may find in Ruby, you need to take a look at data types such as string, integer, float and booleans etc. Type coercion would involve transforming a number into a string, eg 3 into “three” or a number into a float 3 into 3.0. Another example would be the boolean true to the string “true”. However, not all values can be converted to other types. I can’t convert “apple” into an integer (I can but it won’t be apple, it’ll be 0).

### Q10 - Explain data types, using examples

Data types refer to the different ways in which data can exist in a program. There are 6 different data types in Ruby that include boolean, symbols, numbers, strings, arrays, hashes. They all have important distinctions, as well as different functions for use within programs. A string contains text and is formatted with “ “. Integers are whole numbers, and can only be numbers. A boolean only takes 2 values, true or false. While you can have a string “true”, the boolean true can provide more information in the form of agreeing or disagreeing with a statement. Arrays and hashes are a little different, as they are considered to be containers (you can have several strings in an array). Arrays have index values, whereas hashes have hash keys.

### Q11 - Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?”
### - Identify the classes you would use to solve the problem
### - Write a short explanation of why you would use the classes you have identified

Working under a couple of assumptions - that the customers will have iPads on their tables to replace the servers, and that we’ve got some robot chefs out the back cooking up the food. 

The classes that I would use to solve the issue would be:
Meal-Creation class
This class is all to do with preparation of the food (basically replacing the chefs). The objects in this class would include ordered items, ingredients required, preparation time, cooking instructions.

Order class
This class is all to do with the order and selection of the food from the customer on the iPads. The objects within this class would be things such as the different menu items, different drink items, quantity, modification to menu items.

Sever class
This is mostly giving the customer information (replacing the server), as well as taking payment. The elements would include greetings, confirmation of selection, payment options, reviews.

I’ve divided the restaurant up into 3 different aspects. Interacting with the clients, the ordering of the food, and the preparation of the food. I’ve just created different classes that are associated with the different functions. The server class replaces the need for a server. It would greet the customer, and explain how the iPad ordering system works and provide instructions on how to use it. It’s then time for the order class to take over. Here, the customer will be able to browse the different items on the menu, make any changes or special requests, add quantity etc. Before the order is submitted, we revert back to the server class of objects to confirm the order and to take payment before it’s ready to be made. Once we’ve received payment, we move onto the Meal_Creation class that effectively replaces chefs in this situation. It is able to calculate the ingredients required, fetches ingredients, calculates time to completion for the customers. Assuming we have robot chefs, it’ll also have the recipe there too for it then to cook up all the food.

It made sense to divide the classes up to be representative of the different functions of individuals and their functions within the restaurant.

### Q12 - Identify and explain the error in the code snippet below that is preventing correct execution of the program

When you get input from the user with “gets”, and then they enter a number, for example “5” it’s stored in the variable celsius. However, it’s stored as a string. On the next line you then attempt to multiply a string by an integer, which doesn’t work. You need to transform the string number into the integer by adding to_i and changing it from

```ruby
celsius = gets
fahrenheit = (celsius * 9 / 5) + 32
print "The result is: "
print fahrenheit
puts "."
```

```ruby
celsius = gets.chomp.to_i
fahrenheit = (celsius * 9/5) + 32
print "The result is: "
print fahrenheit
puts "."
```

I found that you also need to remove the spaces from after 9 and before 5 to make sure that it runs properly.

### Q13 - The code snippet below looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.

You need to use an extra variable to store the information, otherwise arr[i] and arr[i+1] will end up equalling the same thing.

```ruby
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr[i] < arr[i + 1])
	i = i + 1 end
puts i
    arr[i] = arr[i + 1]
    arr[i + 1] = arr[i]
```

```ruby
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr[i] < arr[i+1])
    i = i+1 
end
puts i
    var = arr[i]
    arr[i] = arr[i+1]
    arr[i+1] = var
p arr
```

### Q14 - Demonstrate your algorithmic thinking through completing the following two tasks, in order:
### 1. Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive). Your flowchart should make use of standard conventions for flowcharts to indicate processes, tasks, actions, or operations
### 2. Write pseudocode for the process outlined in your flowchart

![alt text][docs/diagram.png]

We’d start with an array of numbers from 1, all the way to 100 inclusive. We already know that if it’s prime, it can only be divided by 1 or itself (aka n/n = 1). That also means that, if we were to divide it by every number from 1 up to itself, there will only be 2 occasions where the remainder (modulo %) is equal to 0.

We can start a new array. Starting with 1, we’d go along the array n+1 and as we go through these numbers, we’d divide them all by every number that’s smaller than them n / n - i until it gets divided by itself n / n. This would be a loop that’s inside another loop. 1 loop to move through every number 1-100, another loop for testing whether there’s any % from 1 to n.

Once we’ve divided it by all the possible options up to n, we’d then go through the array and count how many times the % of the answer is = 0. If it’s 2, then the number is prime. If it’s any number higher than 2, then it’s not prime.

### Q15 - Write pseudocode OR Ruby code for the following problem:
### You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”.

```ruby
raining = true
temperature = 14

if raining == true
    if temperature < 15
        puts "It's wet and cold"
    else
        puts "It's warm and raining"
    end
elsif raining == false
    if temperature < 15
        puts "It's not raining but cold"
    else
        puts "It's warm but not raining"
    end
end
```

### Q16 - An allergy test produces a single numeric score which contains the information about all the allergies the person has (that they were tested for). The list of items (and their value) that were tested are:
### - eggs (1)
### - peanuts (2)
### - shellfish (4)
### - strawberries (8)
### - tomatoes (16)
### - chocolate (32)
### - pollen (64)
### - cats (128)

### So if Tom is allergic to peanuts and chocolate, he gets a score of 34.

### Write a program that, given a person’s score can tell them:
### a) whether or not they’re allergic to a given item
### b) the full list of allergies.

Couldn't come up with a solution to this question :(


