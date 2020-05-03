https://guides.github.com/features/mastering-markdown/

## Research the development of the internet from 1980 to today. You must describe at least FIVE key events in the development of the internet. You can refer to events, people of significance, or technologies and how they have changed over time.	500 words

During the 1980s, the internet was owned by the American government. Commerce was forbidden and internet protocols developed with little regard to security due to the small and select nature of the community of users. The internet subsequently became public after being privatized in 1994-95. 

The theorectically open organisations //deciding how to control // were made up of members of a relatively homogenous social class - for example, Alexander Galloway points out, of the twenty-five or so original protocol pioneers, three of them—Vint Cerf, Jon Postel and Steve Crocker—all came from a single high school in Los Angeles’s San Fernando Valley. (Galloway net-time)

Although histories of the internet tend to focus on its principles of freedom and decentralisation, it can be seen to be highly controlled and managed through protocols, standardisation and institutional frameworks. 

When researching the history and development of the internet, we should ask ourselves to which internet we are referring. Do we mean all digital networks, or only those that implement internet protocols. If the latter, which protocols do we have in mind? There are a great many alternatives to 'our' internet - both historical alternatives and those which make up small components of the broader internet  (I mean the one I am connected to right now) and do not always operate in the same way as the whole. These include Fidonet, Usenet, BITNET, X.25, XNS, DECnet and CSNET (see Dourish stuff of bits). A key event in the development of the internet came in 1981, when CSNET became operational. While histories of the internet tend to emphasize its military roots through ARPANET, from an infrastructural point of view, CSNET has a reasonable claim to being the more significant progenitor of the contemporary internet. CSNET was developed in competition to ARPANET by universities (funded by the National Science Foundation) that were not conducting ARPA-sponsored research and thus were denied access to ARPANET. It was CSNET that later formed the backbone of NSFNET, which was eventually turned over to private industry in the moment that birthed the commercial internet. 

Another key event was 


Say something about Chun / Cyberspace / Promiscuity


A final key event (this is the fifth): in 2013, Edward Snowden revealed information showing the US National Security Agency and other federal equivalents were spying on internet users through access provided by phone companies, tech giants, tapping fibre optic cables, and circumventing encryption. Everyone continues to use the internet and seems totally fine with this, so perhaps it is the case that observation and surveillance are necessary in order for us to experience ourselves as real; "I am seen, therefore I am". (Ursula Frohne ‘Screen Tests’: Media Narcissism, Theatricality, and the Internalized Observer,’’ in CTRL [SPACE]: Rhetorics of Surveillance from Bentham to Big Brother, eds. Thomas Y. Levin et al., 275, 262.)


## 2. Define the features of the following technologies that are essential in terms of the development of the internet:
  
### - packets
### - IP addresses (IPv4 and IPv6)
###  - routers and routing
###   - domains and DNS

DNS stands for Domain Name System.  translate URLs into numerical IP addresses

## Explain how each technology has contributed to the development of the internet.	

### 3. Define the features of the following technologies that are essential in terms of the development of the internet:
  - TCP
  - HTTP and HTTPS
  - web browsers (requests, rendering and developer tools)

Explain how each technology has contributed to the development of client and server communication over the internet	


## 4.	Identify THREE data structures used in the Ruby programming language and explain the reasons for using each.

In order for an algorithm to be operable, there is a prerequisite that structured data exist. Although we reason about these two things separately, one is useless without the other. "The distinction between the two is formal" (Goffey in Software Studies p. 18). Data comes to be structured through a critical operation of translation: the transformation of things, actions or processes into information. This is always an abstraction. Humans are literally infected by abstractions (WHitehead?)

### Hash 

A hash is essentially a look-up table – a data structure dating back to the Ptolemaic dynasty, when trigonometric tables were first compiled for use by astronomers, navigators and builders. It is a mapping from a certain symbol (the look-up key) to a value associated with this key. One might use a hash of key-value pairs in cases where it is advantageous to precompute a function and save having to recalculate it later (with the argument vector as the key and the result as the value). The decision to do this would be based on an algorithmic trade-off between processing time and memory space (Babbage). A hash is also useful as a a way of storing a collection of discrete samples, where the function... bla... between the data isn't known
 

### Binary Tree



### Linked List

The kings of Mesopotamia regarded leaving a list inscribed on a tablet, after death, as insurance for an everlasting legacy. 

## 5. Describe the features of interpreters and compilers and how they are different.	

l

## 6 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.	

Lisp?

## 7 Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue. 

## For each ethical issue identify a source of legal information relating to the ethical issue and discuss whether the law is helpful in assisting a developer to act in an ethical way.

## Conduct research into a case study of ONE of the ethical issues you have chosen. Discuss how an ethical IT professional should respond to the case study and how they might mitigate or prevent ethical breaches.	

The objective of this paper is to consider the practicability of the ethical model implied
by Karen Barad’s ethico-onto-epistemological theory. I wish to ask the question of
whether the idea of individual responsibility, which appears to constitute the backbone
of traditional ethics, can be reconciled with the new materialistic idea of the intra-activity
of matter, which calls human individualism and independency into question. According
to Karen Barad agency is the quality not limited to human actors only. No longer can
humans be perceived as independent beings capable of making autonomous choices,
because the non-human subjects actively influence their decisions. That said, human
behaviour cannot be reduced to a set of mechanical involuntary responses to external
factors (or internal ones for that matter, since plethora of different bacteria shape our
perception from within our bodies). When scrutinized through the lens of Barad’s
agential realism, the picture of personal responsibility becomes hazy: if ‘blame’ cannot
be justly attributed to either human or non-human actants, where else should it be
placed? Perhaps the validity of the very idea of blame, understood as the immediate
result of a free subject’s independent activity, should be questioned? Liberatory and
somewhat romantic, as the ideas of intra-activity as well as ‘intra-material community’,
where every form of existence matters, are, they do prompt one to ask the question of
their applicability to a human being’s conduct of everyday life.

## 8 Explain control flow, using an example from the Ruby programming language	

## 9 Explain type coercion

Type coercion in ruby means changing the data type of an object into another.

## 10 Describe the data types recognised by the Ruby programming language. In your description you should give example code which uses each data type, and include the name of the Ruby classes which represent each data type.	

## 11 Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?”>
  - Identify the classes you would use to solve the problem
  - Write a short explanation of why you would use the classes you have identified	

## 12 Identify and explain the error in the following code that is preventing correct execution of the program	

On the second line, the program is trying to manipulate a string as if it is a number. This error could be resolved by using the gets.to_i method on the first line to coerce the input from the user into an integer. 

## 13 The following code looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.	

 ```ruby
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
n = arr.length
(n-1).times do |i|
    if arr[i] > arr[i+1]
    arr[i], arr[i + 1] = arr[i + 1], arr[i]
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

