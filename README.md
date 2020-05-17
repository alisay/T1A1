## 1. Research the development of the internet from 1980 to today. You must describe at least FIVE key events in the development of the internet.

In 1980, the internet was owned by the American government. Commerce was forbidden and internet protocols developed with little regard to security due to the small and select nature of the community of users. The internet subsequently became public after being privatized in 1994-95. Today the internet works by a system of rents and tolls not dissimilar to feudalism. 

When researching the history and development of the internet, we should ask ourselves to which internet we are referring. Do we mean all digital networks, or only those that implement internet protocols. If the latter, which protocols do we have in mind? There are a great many alternatives to 'our' internet - both historical alternatives and those which make up small components of the broader internet  (I mean the one I am connected to right now) and do not always operate in the same way as the whole. These include Fidonet, Usenet, BITNET, X.25, XNS, DECnet and CSNET (Dourish 2017). 

With this in mind, we could consider the moment when CSNET became operational, in 1981, as a first key event after 1980. While histories of the internet tend to emphasize its military roots through ARPANET, from an infrastructural point of view, CSNET has a reasonable claim to being the more significant progenitor of the contemporary internet. CSNET was developed in competition to ARPANET by universities (funded by the National Science Foundation) that were not conducting ARPA-sponsored research and thus were denied access to ARPANET. It was CSNET that later formed the backbone of NSFNET, which was eventually turned over to private industry in the moment that birthed the commercial internet. 

Technical protocols and standards nowadays are established by a self-selected oligarchy of scientists from an extremely homogenous social class (Zeb 2020a). For example, of the twenty-five or so original protocol pioneers, three of them (Jon Postel, Steve Crocker and Vint Cerf) all went to the same high school in Los Angeles’s San Fernando Valley (Galloway 2003). There are a number of protocological institutions who have variously occupied themselves with internet standardisation: the International Electrotechnical Commission, the International Organization for Standardization (who together coordinate as the Joint Technical Committee), the International Telecommunication Union, the Internet Society, the Internet Architecture Board, the Internet Engineering Steering Group, the Internet Engineering Task Force, and the World Wide Web Consortium. These adistributed, bureaucratic institutions enforce technical standardisation, organised implementation, almost universal agreement and adoption, and directed participation. In this way, distributed control results in rigid hierarchies (Galloway 2003).

A further key event in this extremely non-comprehensive history of the development of the poorly defined multiplicity that is the internet was the development of gopher, which went live in April 1991. This was a navigation aid for the increasingly expanding network of the internet based on TCP/IP. Gopher allowed users to browse using a menu-based interface and was the most popular model of knowledge organisation until superseded by Tim Berners-Lee's web in late 1994. It is postulated that gopher failed due to the University of Minnesota's assertion of intellectual property rights, and necessity for a centralised directory (Campbell-Kelly & Garcia-Swartz 2013). The move to a web without centralised directory paved the way for the boom in the web search industry, which was eventually comprehensively cornered by Google. 

Here's a final key event (this is the fifth, at least): in 2013, Edward Snowden revealed information showing the US National Security Agency and other federal equivalents were spying on internet users through access provided by phone companies, tech giants, tapping fibre optic cables, and circumventing encryption. Everyone continues to use the internet and seems totally fine with this.


## 2. Define the features of the following technologies that are essential in terms of the development of the internet:
  
### - packets

Messages from one node to another on the internet are broken into small units, called packets. An IP packet can be up to 65,000 bytes in length and is made up of the header, which stores information about addressing and processing, and the data that makes up the actual content of the packet. In some cases this content might be just a single byte. Packets are transmitted one bit at a time, meaning they have a length, which can be measured in millimetres. From the moment you turn on a networked computer, it sends and receives, stores and discards packets, which you the user can only read if you install a packet sniffer and translate from the hexadecimal. The path of a packet through a network is also opaque to the user – if you attempt to source route your packets, they will usually be rejected by hosts as security risks. Thus the internet entails the constant sending of necessary, unceasing and involuntary transmissions which are opened, broadcast and redirected by unknowable others. 

### - IP addresses (IPv4 and IPv6)

There are six versions of the Internet Protocol, which guides the assignment of a numerical address to each device in a network. Versions 1–3 were experimental precursors to the widely deployed IPv4. Version number 5 was assigned to the experimental Internet Streaming Protocol, which was never considered as a replacement for IPv4. The main difference between 4 and 6 is that IPv4 defines an IP address as a 32-bit number, while IPv6 uses 128 bits. The original strategy for internet address allocation was a class-based system, with the 32 bits of an IP address being divided into 8 bits of network identifier and 24 bits of host for class A (16 million available addresses), 16 and 16 for class B (65,000 addresses), and 24 and 8 for class C (250). This resulted in various inequities of allocation, such as MIT (18.0.0.0/8) being allocated more addresses than China. Despite being developed in the mid-1990s, IPv6 is still not in widespread use. 100 words is not enough to talk about the joys and tribulations of IP addresses. 

###  - routers and routing

Routing refers to the function whereby packets get from the network to which their source computer is connected to the network to which their destination computer is connected. Gateways, also known as routers, are essentially a computer connected simultaneously to two or more networks and thus possessing the capacity to receive packets via one network and retransmit them to another. To do so effectively, they require information about how the network is organised. There are protocols that govern the distribution of routing information, for example: RIP (Routing Information Protocol), EGP (External Gateway Protocol), BGP, (Border Gateway Protocol), CIDR (Classless Inter-Domain Routing). Depending on the protocol, routing becomes less a matter of topology and more a material instantiation of institutional and economic relationships (Dourish 2017).

###   - domains and DNS

A computer does not know its own name. It only knows its address. When it boots, it asks a network server, "what's my name?" and it is told by the network authority. The right to choose a name is taken away from the individual. DNS stands for Domain Name System. It is a hierarchical architecture, with bureaucratic governance, which translate URLs into numerical IP addresses, thus allowing the distributed and open architecture of the Internet Protocol. The translation from URL to IP address is the move from one abstraction level to another. When a domain name is translated into an IP address does it remain materially the same? Is information an abstract property that can be transferred across substrates? If not, the transhumanists are going to be very upset.  

## 3. Define the features of the following technologies that are essential in terms of the development of the internet:

### - TCP

Transmission Control Protocol (usually paired with Internet Protocol, with which it is designed to operate in concert) uses the unreliable datagram service of IP to deliver packets, but introduces extra mechanisms to produce the effect of smooth and reliable transmission. TCP also stands for Transmission Control Program - the original design proposed by Vint Cerf and Robert Khan in 1974 as a monolithic program that managed both problems of network navigation (subsequently delegated to IP) as well as establishing reliable communication between endpoints. It replaced NCP, which managed network transmissions when there was just the single network of ARPANET. Until 2013, when multipath TCP was introduced, TCP connections were associated with a single IP address. Multipath allows a single TCP connection to take advantage of multiple network interfaces and paths, further decoupling TCP and IP. 

###  - HTTP and HTTPS

The Hypertext Transfer Protocol is a generic, stateless, application-level protocol for distributed, collaborative, hypermedia information systems (Masinter 1998). An HTTP client sends an HTTP request to a server as a message including: a request line, a zero or more header, an empty line, and an optional message body. We can think of an HTTP request as the paradigmatic body-without-organs: "not an empty body stripped of organs, but a body upon which that which serves as organs is distributed according to crowd phenomena, in Brownian motion, in the form of molecular multiplicities" (D&G 1980). Https is the more secure version of http - the 'S' stands for Secure. 

 ### - web browsers (requests, rendering and developer tools)

  Web browsers are the most world's most widely used software, capable of rendering and displaying requested content, making network calls and requests, and storing data locally. Modern browsers include a user interface, browser engine, rendering engine, networking, UI backend, JavaScript interpreter and data storage. The user interface is not specified by any formal protocol, but the majority have very similar elements including address bar, forward, back and refresh buttons, bookmarking ability, etc. The rendering engine varies by browser but, with minor variations, all go through the self-same gradual process of parsing html documents and converting elements to a content tree and, together with the parsed css files, building a render tree. The render tree is composed of the visual elements in the order they are displayed. These are displayed to the screen using the renderer's "paint()" method. This of course all happens in an *order* and is very complicated (Garsiel & Irish 2011). "God did not ban networking" but sometimes it's hard to understand why not. Developer tools, as implied in the name, provide tools within a browser, which developers might use to develop for the web. Developer tools are themselves developed by developers. Tools always mediate between the tool user (in this case, the developer) and their milieux (information). There have been a number of browser wars throughout history, where organisations obviously and consciously compete for share in the economic sphere in a manner which has been analogised to the way in which pacification and control is enforced through the propagation of drug addiction among certain specific communities (Fuller 2012).

## 4.	Identify THREE data structures used in the Ruby programming language and explain the reasons for using each. 

In order for an algorithm to be operable, there is a prerequisite that structured data exist. Although we reason about these two things separately, one is useless without the other. "The distinction between the two is formal" (Goffey 2008). Data comes to be structured through a critical operation of translation: the transformation of things, actions or processes into information. This is always an abstraction. Humans are literally infected by abstractions (Whitehead 1938).

### Linked List

The kings of Mesopotamia regarded leaving a list inscribed on a tablet, after death, as insurance for an everlasting legacy. A list in Ruby is sequentially stored data, with each node containing a reference to the next piece of data. Lists provide an elegant data structure for representing information about the world in formal language, and thus for programming the operations involved in deduction (McCarthy 1996). This is the reasoning behind the heavy use of lists in the LISP programming language, the use of which is "the equivalent of communing with the old gods" (Zeb 2020b).

### Hash 

A hash is essentially a look-up table – a data structure dating back to the Ptolemaic dynasty, when trigonometric tables were first compiled for use by astronomers, navigators and builders. It is a mapping from a certain symbol (the look-up key) to a value associated with this key. One might use a hash of key-value pairs in cases where it is advantageous to precompute a function and save having to recalculate it later (with the argument vector as the key and the result as the value). The decision to do this would be based on an algorithmic trade-off between processing time and memory space (Babbage 1837).
 
### Binary Tree

"We're tired of trees... they've made us suffer too much," wrote Deleuze & Guattari in 1000 Plateaus (D&G 1980). A tree is a non-linear structure, where data branches from a root node. It can be used to store data that naturally forms a hierarchy. A binary tree has at most two children to each node. It allows for fast search, insert and delete on sorted data. Binary trees supply the precision, speed, unambiguity, continuity, discretion, unity, strict subordination, and reduction of friction that is essential to the entrenching of bureaucracy in contemporary society (Castelle 2013).

## 5. Describe the features of interpreters and compilers and how they are different.

Both compilers and interpreters convert higher level programming languages into machine-readable code. An interpreter reads an expression that is typed to the terminal, evaluates that expression, and prints the result. Each time an interpreter evaluates an expression, it must perform the work of classifying the expression and testing for the end of the operand list. Any time it runs, it must follow a process that is applicable to any expression in the language and be prepared for any contingency. It does so by using the stack to save all registers that will be needed later, when a subexpression requires arbitrary evaluation (Abelson et al 1996). This is not the case for a compiler. A compiler analyses the expression only once - at compile time - when reads the source code and creates an executable program. It can exploit the structure of any particular expression it will process to generate code that avoids unnecessary stack operations. A compiler can also analyse code to know where variables are located and access those frames directly, rather than performing a search (Abelson et al 1996). A compiled program is therefore often more efficient than an interpreted program. Interpreters are simpler to develop and debug than compilers. They also allow for debugging at runtime, which can be done line-by-line and using real data. 

## 6 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.	

Because any programming language that is Turing complete necessarily must be able to express any computation, every language is, formally speaking, interchangeable. The differences in programming languages is therefore human and cultural: they lend themselves to different problem sets and different styles of thinking based on their semantic structures, grammar and algorithm construction. Programming inevitably involves double-coding: programs mean something simultaneously to the machine and to the human reader. 

According to Wikipedia, Haskell is the 23rd most popular programming language in terms of Google searches. Hopefully, this meets the criteria for "commonly-used". Haskell is a statically typed, purely functional programming language with type inference and lazy evaluation (Wikipedia 2020).  In functional programming languages functions do not consult memory or have side effects. Any given input will return the same output. Lazy evaluation means that Haskell programs wait until the last moment to evaluate expressions. Where something like Ruby is dynamically typed, meaning that variable can hold any value, regardless of type, in a statically typed language, every variable has a specific type, which is known at the time it is compiled. Haskell, however, while statically typed, does not usually require types to be declared. Instead, type is inferred by the compiler. Haskell is useful for data intensive industries where reliability, speed and scalability are important. It is currently used for all the spam filtering on facebook. Some of the criticisms that have been levelled at Haskell include its lack of tooling, libraries and documentation; the steep learning curve for beginners; and the way in which lazy evaluation complicates programmers' reasoning about the performance of code. 

Perl is ranked 21 in the languages most commonly used on GitHub - seven spots up from Haskell at 28. There has been a steep and ongoing decline in Perl's popularity over the past two decades. It refers to a family of interpreted, dynamic programming languages. Perl was first developed in 1987 by Larry Wall as an open source project to combine the speed of coding available in shell programming with the power of advanced tools, without needing to use a lower level language like C or assembly. It borrows elements from both C and shell script. It uses a highly flexible syntax, providing freedom of expression to developers. Its concise regular expressions and string parsing abilities allow complex search and modification operations to be densely encoded. This can make Perl difficult to read and "kind of ugly" (Schwartz & Phoenix 2011). This inelegance, alongside Perl's flexibility, power and ubiquity, has garnered the language accolades like "the Swiss Army chainsaw of scripting languages" and the "duct tape that holds the Internet together" (Wikipedia 2020). In addition to string manipulation, it is also a language that lends itself to the problem domain of poetry (see for example https://www.perlmonks.org/?node_id=1111395). 

## 7 Ethics 

Normative ethics revolve around the fulcrum of the human subject and its choices. However, quantum entanglement and geophilosophy problematise the ontological separability of subject and other: time and space, cause and effect are co-constituted (e.g. Barad 2007, D&G 1980). Ethics in this model is inseparable from ontology and epistemology. We cannot therefore consider ethics as an added concern to be reflected upon subsequent to an established material state of technology, but must instead consider how every practical action is ethopoietical. It is also nonsensical to discuss responsibility at the level of the individual IT professional: dividuation is necessarily collective (Simondon♥ 1989). This does not diminish the importance of ethics, but rather recognises that it is always already embedded in the fabric of the world. 

One issue in which this is made clear is in artificial intelligence: a term that is currently used interchangeably with machine learning (or applied statistical inference). There is currently a great deal of resources being channelled into research on how machine learning might be applied in, for example, the case of criminal acts, aggressive sales and marketing practices, or the trading of shares on the stock exchange. The technical and ethical dimensions of these machine learning-driven systems are irreducibly intertwined; however, the systems cannot be characterised as a monolithic actor. The IT professional who develops machine learning algorithms is inextricably linked in a complex socio-technical web, which makes explicit the contingency and uncertainty of societal values (Parisi 2019). This professional will be acting in an ethical way if they acknowledge the inseparability of their bodies from the material-discursive practices that constitute the world's becoming (Barad 2007). 

There is little legal guidance on this issue. In 2016 the European Union passed a report urging for a set of regulations to govern the use and creation of artificial intelligence (European Parliament 2016). This is yet to happen, though they did publish a further white paper in February of this year laying out a series of policy options. There are no laws specific to artificial intelligence in Australia. It is still worth considering to what extent the law in general is helpful in assisting a developer to act in an ethical way. Law is a technology of power deployed by the state (and by those individuals with influence over the state's processes), where the content of the law is not aligned with ethical principles but is the outcome of contests of power; "humanity installs each of its violences in a system of rules and thus proceeds from domination to domination" (Foucault 1977). The genesis of the common law (from which Australian law descends) was in the criminalization of poverty as a means of controlling the bodies of the working class (Linebaugh 1991). Caution should therefore be exercised in using it as an ethical guide. 

Another ethical issue that might involve an IT professional is the question of encryption of data. In some instances, when a message is sent, there is a desire on the part of the sender and receiver that its contents remain private from third parties: for example, in the case of a source providing information relevant to a matter of public interest to a journalist. On the other hand, encryption might also be used in the commission of crimes, like in the distribution of child pornography An IT professional might be involved in both developing and cracking means of encryption. In Australia, the *Assistance and Access Bill* (2018) compels technology companies to allow the government access to encrypted messages. This might mean that a developer is in breach of the law if they implement a fully secure method of encryption. However, there is a conflicting legislative instrument in Australia in the *Human Rights (Parliamentary Scrutiny) Act* (2011), which establishes the right to privacy and freedom of expression. Where there is a potential conflict like this in law, it must be resolved through the courts. Ultimately, any action brought would be decided by the justices of the High Court of Australia, of whom 4 were nominated by a Liberal government and 3 by Labor. The cost of such an extended legal process required to resolve the ethical dilemma for the IT professional tasked with developing digital encryption means that it is likely unfeasible that the law might provide assistance in guiding that professional's actions. 

A case study which demonstrates how an IT professional might respond to the ethical consideration of developing encryption in a fraught legal environment is that of the creation of a method of public-key cryptography by Whitfield Diffie and Martin Hellman in 1976. This method had previously been developed by two separate national secret agencies since 1969, but had remained classified. The National Security Agency of the United States sought to prevent publication of Hellman and Diffie's paper outlining this cryptographic system, threatening prison time for the two IT professionals under laws restricting export of military weapons. This case study provides one option for an IT professional seeking to mitigate any ethical breach which might flow from their actions, which is to align oneself with the academy and hope that an institution such as a Stanford might better balance the conflicting priorities of public interest and crime-doing. Ultimately, the two programmers who developed public key encryption were honoured with prestigious awards and honorary doctorates, and generally hailed as iconoclasts, which might not have happened had they not had the backing of a wealthy and respected institution. 

## 8 Explain control flow, using an example from the Ruby programming language

In computer science, control flow is the order in which individual statements, instructions or function calls of an imperative program are executed or evaluated (Wikipedia 2020). In Ruby, statements are executed sequentially from the top of the source file to the bottom. Conditionals and loops will alter the flow of the program. Conditionals will execute statements only under specific conditions and loops will execute a block of code multiple times. For a Ruby program to be redistributed as a flow, other media forms are necessary: sketches, complex process mappings and charts, and abstractions of event-driven process chains. Although control flow is an abstraction, it has material effect on actual practice allowing command-and-control structures to sanititize and routinize production (Fuller 2012). One example of control flow in the Ruby programming language could be expressed as follows: 
```ruby
{condition} ? {true-code-block} : {false-code-block}
```
This is a conditional statement, commonly known as a ternary operator, which will alter the flow of the program depending on whether a condition is true or false. The {true-code-block} will be executed if {condition} is true, else the {false-code-block} will be executed.

## 9 Explain type coercion

Type coercion is a method of changing the data type of one entity into another when performing an operation or evaluation. There is a hierarchy in programming languages as to which type will take precedence in any coercive operation. Type coercion can be explained by the human desire to minimize exceptions and unknowability. It provides a way to ensure the flow of control through a program can be maintain even in the face of unexpected data types, ensuring that an application need not crash simply because two or more different data types are being evaluated. By facilitating this smooth running of software, type coercion stabilizes not only the software but also the practice itself. It allows for errors to be framed as technical problems created by the user not understanding the software rather than the inverse. In this way, the practice of type coercion thwarts efforts to more closely consider the relationship between technical object and its environment.

## 10 Describe the data types recognised by the Ruby programming language. In your description you should give example code which uses each data type, and include the name of the Ruby classes which represent each data type.	

### Booleans (TrueClass and FalseClass)
A boolean refers to a value of true or false. In Ruby these have their own data types. Booleans make it possible to perform logical reasoning. 

```ruby
1 + 1 == 3 #=> false
```

### String
A string is zero or more characters enclosed by inverted commas. They are used to manipulate text. 
```ruby
"wow" * 3   #=> "wowwowwow"
```

### Symbol
A symbol is like a string, but immutable. 
```ruby 
puts "string".to_sym.class #=> Symbol  
```

### Numbers (Numeric: Integer, Float, Complex, Rational, etc.)
Numbers are for doing maths. 
```ruby
1 + 1 #=> 2
```

### NilClass
Nil is a class in Ruby which cannot be instantiated. There is only one nil object, with an object id of 4. The nil value acts more like a keyword than an instance, and expresses the notion of the lack of an object.  
```ruby
[1,2,3][3] #=> nil
```

### Hash
Hey, I already spoke about hashes in question four. Is it a data type or data structure? Well, it's both; a data type is a way of organising data while a data type is just a class of object that share some property. They're not mutually exclusive. You can think of a hash as an array that lets you use any object type as the index. What's an array? Why, that's coming up next!
```ruby
Hash["a", 100, "b", 200] #=> {"a"=>100, "b"=>200}
```

### Array 
Arrays are ordered, integer-indexed collections of any object. 
```ruby 
ary = [1, "two", 3.0] #=> [1, "two", 3.0]
```

## 11 There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?

I would use the following classes: 

**Order** - which allows food choices to be added to a hash when the customer places an order, totals the cost of the order and prints the order and cost to screen on request. 

**Food** - which initializes with the attributes name, cost price and selling price. Each item on the menu will inherit from this class, with its own particular attributes. 

**Menu** - which allows for food available to be added to a hash that can be displayed to the customer. 

I would also have a module **Cafe** which prescribes the interaction by which customers can see the menu, order and be presented with the total cost of the order. It will also allow for food to be added to the menu. 

I have chosen to use a module where there is a static function and class where there might be multiple instances of an object. 

## 12 Identify and explain the error in the following code that is preventing correct execution of the program	

On the second line, the program is trying to manipulate a string as if it is a number. This error could be resolved by using the gets.to_i method on the first line to coerce the input from the user into an integer. 

## 13 The following code looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.	

 ```ruby
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
n = arr.length
(n-1).times do |i|
    if arr[i] > arr[i+1]
    arr[i], arr[i + 1] = arr[i + 1], arr[i]
    break
    end
end
```

## 14 
```bash 

                      +------------+
                      |    Start   |
                      +------+-----+
                             | 
                             v
                 +---------------------+
                 |  Create a list of   |
                 |  integers 2 to 100  |
                 +-------+-------------+
                             | 
                             v
                       +---------------+
                       |Let p = 2 (the |
                       |smallest prime)|
                       +--------+------+
                               v
+---------------+       +--------------------+
|Let this number|       |Find the multiples  |
|equal p        |------>|of p in the list and|
+------^--------+       |cross them out      |
       |                +--------+-----------+
       |                         v
       |               +---------------------------+           +----------------+
       |               |  is there a number in     |           |All the numbers |
       +------------+  |  the list bigger than p   | +-------->+left not crossed|
                       |  that is not crossed out? |           |out are primes  |
                       +---------------------------+           +----------------+

```

Psueudocode:

    let A be an array of boolean values, indexed by integers 2 to 100,
    initially all set to true.
    
    for x = 2 ... 100 do
        if A[x] is true
            for y = x^2, x^2+x, x^2+2x, x^2+3x, ..., not exceeding 100 do
                A[y] = false

    return all x where A[x] is true.


## 15 Weather advice

```ruby 
def weather(raining, temperature)
    result = case [raining, (temperature<15)]
    when [true, true] then puts "It’s wet and cold"
    when [true, false] then puts "It’s warm and raining"
    when [false, true] then puts "It’s not raining but cold"
    when [false, false] then puts "It’s warm but not raining"
    end
end
```

## 16. Allergy Test

```ruby 
def allergy_test(score)
    puts "You are allergic to the following:"
    allergies = ["eggs", "peanuts", "shellfish", "strawberries", "tomatoes", "chocolate", "pollen", "cats"]
    array = []
    while (score > 0)
        array.append(score%2)
        score = (score/2)
    end
    for i in 0..(array.length) 
        puts allergies[i] if (array[i] == 1)
    end
end

```

### Bibliograpy

H Abelson, GJ Sussman & J Sussman 1996 *Structure and Interpretation of Computer Programs* MIT Press, Cambridge Mass. & London, England.

C Babbage 1837 *The ninth Bridgewater treatise: a fragment* John Murray, London, England.

M Castelle 2013 "Relational and Non-Relational Models in the Entextualization of Bureaucracy", *Computational Culture* Issue 3, <http://computationalculture.net/relational-and-non-relational-models-in-the-entextualization-of-bureaucracy/>, acccessed 6 May 2020.

G Deleuze & F Guattari 1980 *Mille Plateaux: Capitalisme et schizophrénie* Editions de Minuit, Paris, France. 

P Dourish 2017 *The Stuff of Bits: An Essay on the Materialities of Information* MIT Press, Cambridge, Mass & London, England.

European Parliament, Committee on Legal Affairs 2016 *Draft Report with recommendations to the Commission on Civil Law Rules on Robotics* 31 May 2016, <https://www.europarl.europa.eu/doceo/document/JURI-PR-582443_EN.pdf>, accessed 6 May 2020.

M Foucault 1977 "Nietzsche, Genealogy, History" in *Language, Counter-Memory, Practice: Selected Essays and Interviews* edited by D. F. Bouchard. Ithaca: Cornell University Press, <https://philarchive.org/archive/FOUNGH>

M Fuller 2012 *Evil Media* MIT Press, Cambridge Mass. 

U Frohne 2002 "Screen Tests: Media Narcissism, Theatricality, and the Internalized Observer" in TY Levin (ed.) *CTRL [ SPACE ]: Rhetorics of Surveillance from Bentham to Big Brother* MIT Press, Cambridge, Mass.

A Galloway 2003 *Institutionalization of computer protocols*, Nettime, 12 Jan, <https://nettime.org/Lists-Archives/nettime-l-0301/msg00052.html>, accessed 6 May 2020. 

T Garsiel & P Irish 2011 *How Browsers Work: Behind the scenes of modern web browsers* <https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/>

A Goffey 2008 "Algorithm" in M Fuller (ed.) *Software Studies* MIT Press, Cambridge Mass & London, England.

M Campbell-Kelly & DD Garcia-Swartz 2013 "The history of the internet" *Journal of Information Technology* 28(1), pp. 18–33.

P Linebaugh 1991 *The London Hanged* Verso, London, New York.

L Masinter 1998 *Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0)* ,RFC 2324, <https://www.ietf.org/rfc/rfc2324.txt> 

J McCarthy, 1996 *LISP Prehistory—Summer 1956 through Summer 1958* <http://www-formal.stanford.edu/jmc/history/lisp/node2.html>, accessed 6 May 2020.

L Parisi 2019 The alien subject of AI, *Subjectivity* 12: 1, pp. 27–48. 

RL Schwartz & T Phoenix 2011 *Learning Perl*, Fourth Edition, O'Reilly.

G Simondon 1989 *L'individuation psychique et collective* Aubier, Paris.

Z Stevenson 2020a *FlexTrack - CSS Essentials Lecture* Coder Academy, Monday 4 May, Melbourne Australia.

___________ 2020b private correspondence, Wednesday 6 May.

AN Whitehead 1938 *Science and the Modern World* Penguin Books, Middlesex, England.


