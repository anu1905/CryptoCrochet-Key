# Secure Your Home IoT with the CryptoCrochetKey
Anuradha Reddy

## Profile of Content

### Keywords
#Crochet  
#MachineLearning  
#CriticalMaking  

### Contexts

<!--- Please answer the following questions using short, concise sentences :) --->

1. What is the context or background that inspired your recipe? (< 100 words)
During my PhD studies, I found myself feeling stuck with industry-focused IoT and AI narratives. They tended to ignore the sociotechnical realities and imaginations of marginalised folks, including women and people of colour. Working now with hacker communities, I am inspired by femhackers’ skills, their modes of hacking, and especially their use of diverse materials and hardware that challenge extant ideologies around who computation is for and who can benefit from it.  

2. Which community are you offering the recipe to? (< 100 words)
I think my recipe’s contribution lies at the intersection of two broad communities of practice. The first is the crochet/knitting communities who are often highly skilled in their craft but struggle to apply computational thinking. The other is technical communities who are deeply competent in their programming knowledge, but struggle to integrate interdisciplinary ways of knowing and doing in their computing practices. Some prefer to call this intersection the 'STEAM' community.

3. How does your submission relate to intersectional feminism? (< 100 words)
Intersectional feminism draws from the knowledge that every individual has intersecting positions of power and privilege. My submission works to show that interdisciplinary making can cut across these positions of privilege i.e., by drawing attention to the reappropriation of dominant technolgoy using techniques and grammars that are local and specific to craft communities. 

### Short Description
In a brave new world of quantum encryption, cryptocurrencies and NFT transactions, the concept of a ‘key’ is evermore abstracted by mathematical calculations when compared to the flat metal items we store in our pockets and purses. While digitally encrypted keys can make transactions relatively secure—like receiving an email, ordering a pizza, or dis/arming your home, they continue to be cryptic devices for those of us who are not already familiar with the technology nor supported by a civic hacker community. Is it possible to make a physical key, unique enough to avoid forgery while being recognisable to a local computer for making safe transactions? Thanks to a handy textile yarn called ‘Crypto’ and some inspirational reading on programmable yarn, it _is_ possible to physically encrypt a key through crochet and then to teach a computer to recognize the crocheted key using Machine Learning. The _CryptoCrochet-Key_ is meant to be part ‘hack’ and part ‘pedagogical device’ that defamiliarizes existing computational practices (learning code) from an intersectional feminist lens. It is meant to be inclusive and empowering for those skilled in other ways than traditional programmers and to show how their skills can contribute to a critical discussion of data-driven technologies—i.e. by putting the tech to radically different uses. This 3-part tutorial begins by introducing CryptoCrochet-Key with instructions for making the key and then moves to the Machine Learning part of the project. The final part shows how to run the CryptoCrochet-Key Machine Learning model securely on a Raspberry Pi 4.

## Body of Content

Crochet/knitting is a handicraft practice with strong associations to feminine, domestic hobbies and leisure. Although anyone who has engaged in the practice knows that it is, in fact, an intellectually demanding activity, one that takes advantage of the mathematical and mechanical properties of yarn and knitted fabric — anticipating how the material behaves with every stitch. Dr. Elisabetta Matsumoto, a physicist, has even argued that “yarn is programmable” and “knitting is coding” in her [New York Times](https://www.nytimes.com/2019/05/17/science/math-physics-knitting-matsumoto.html?smid=url-share) interview — a pedagogy that goes beyond coding binaries (ones and zeroes). Additionally, crocheting is an act of distributed cognition — a complex choreography between reading coded patterns and making corresponding hand movements with more than a single apparatus, sometimes in a social setting if one can afford it. Like other handicrafts, crochet does not separate the mind’s intellect from that of the body(ies). This argument is central to feminist, queer, and disability theories and a critique against positivist data-driven paradigms that strive to model reality from disembodied datasets (Thomson, 1997; Skeggs, 1997; Ahmed and Stacey, 2001; D'Ignazio and Klein, 2020). The act of crochet/knitting is also a labour of love, joy, and gift-giving — a kind of pushback and resistance to agile and extractive data-driven technology practices (Orton-Johnson, 2012; Hellstrom, 2013). If a community of crochet practitioners/fiber artists have a seat at the table with software developers and data science practitioners, what might they do (or say)? CryptoCrochet-Key is one possible answer.

![The first image shows a hacker news website featuring my CryptoCrochet-Key project. The article states “Anuradha Reddy’s CryptoCrochet-Key Gives You a Unique, Huggable Security Token for Home IoT.” The second image on the top right is the software application called ‘Teachable Machine’ where I’m training the Machine to learn how my crochet key looks using my computer webcam. The third image on the bottom right is a picture of my hand with the key testing on a Raspberry Pi computer.](https://miro.medium.com/max/1400/1*xj7IltEwUuRxjCcMKcJqOQ.jpeg)

The word ‘crypto’ in CryptoCrochet has little to do with cryptography. Rather, the name is borrowed from a yarn called [crypto 8 ply](https://www.ausyarnco.com.au/products/browse-by-brand/panda/crypto-8-ply/default.aspx) manufactured by the Panda yarn company (AusYarnCo). This yarn is multicoloured/variegated, which lends itself to _joyfully_ crafting objects that are “[uniquely unique](https://www.hackster.io/news/anuradha-reddy-s-cryptocrochet-key-gives-you-a-unique-huggable-security-token-for-home-iot-222b422ed7f0)”. With each multicoloured stitch, it becomes possible to encrypt a discrete code/pattern in the shape of an object (in our case, a key) that only you have access to, and something only you can teach your computer to recognize. If you lose the key, you can easily make a new one and then teach your computer to recognize the new key and delete data for the old one. What makes the key-making process with variegated yarn especially enjoyable is one’s loss of control over the yarn’s colours, something one can liken to not being fully in control of how water travels when painting in watercolour. In the tutorial, we will learn how even the Machine Learning model has trouble making colour distinctions, something that we can use to our advantage to deliberately toy with the model.

You will find the these key takeaways from the tutorial: (1) inspiration for thinking of other non-traditional pedagogies for learning ‘how to code,’ (2) the empowerment to experiment with technologies or methods from industry (e.g. Machine Learning) using everyday materials — layered, thick, colourful, and patterned (like yarn), and (3) to re-deploy them for ends that were never intended by their creators through feminist, queering practices. The _CryptoCrochet-Key_ is just one of many adversarial things one can make with variegated yarns to tactically encounter smart surveillance and computer vision systems. Going forward, it is possible to imagine exploring an entirely new genre of security authentication via knitted fashions (sweaters, suits) and wearables.

### Recipe
#### Part 1: Making the Key
Here’s what you will need to make the crocheted key. The first step is purchasing variegated/multicoloured yarn from your local yarn shop (fun!) and a crochet hook to go with it (the recommended size of the hook should be visible on the yarn packaging). I usually recommend a cotton yarn with a hook size of 3.5-4mm. You will also need some cotton wool for stuffing, stitch markers (or hairpins) for marking rounds and a tapestry needle with a wide eye to weave in loose yarn.

Before starting to crochet, it is useful to know some standard crochet notations that will appear in this tutorial. We will use only basic crochet stitches like the [chain stitch](https://youtu.be/o-Il8OcNAZA) (denoted by ‘ch’), the [slip stitch](https://youtu.be/AFk-fdAowbY) (‘sl st’), and the [single crochet stitch](https://youtu.be/Ik-GSXWoSak) (‘sc’), which makes this a simple starter project. If you would like to learn the full range of crochet stitches, I can’t recommend [CraftyMinx’s](https://www.craftyminx.com/2011/11/crochet-school-.html/) crochet school enough. If you are already familiar with the techniques, then the next section should be a breeze. Remember that the key is made in separate parts — the top doughnut ring, the long leg and two short legs.

You will find the pattern instructions here on Github or if you would like to slip away from the computer screen for this part of the tutorial, I compiled the instructions into a [PDF pattern](https://files.cargocollective.com/c989887/png2pdf_reduced.pdf) that you can print and take with you. Jump directly to Part 2 when you're done.

#### Part 2: Teaching the Machine to Recognize Your Key
Once you’ve made your key, you can teach your computer to recognize it. In technical terms, this entails a complex process of combining the Transfer Learning technique (unsupervised Machine Learning — Neural Nets) with an Object Detection model (a pretrained Machine Learning model) and Computer Vision (CV) that uses a camera to ‘see’ the object and learn what it looks like. Executing this feat would ideally require a prior understanding of data science and analytics, but luckily for us, there is readily available software that lets us train Machine Learning models without prerequisite programming skills or data science knowledge. We will use one such browser-based software program called ‘[Teachable Machine](https://teachablemachine.withgoogle.com/)’ for this part of the tutorial.

Teachable Machine (TM) is a software to train your computer to recognize unique sounds, images, and body poses, allowing you to personalize your interactions with the computer. For example, with TM we can capture a large number of images of the crochet key via the computer’s webcam — from different angles and under different light conditions — and use those images as training data for the model. Once trained, the computer can predict with some degree of confidence whether what it sees is your key or some other object.

This is easy to do. We start an ‘Image Project’ and create classes for the kinds of objects we want or do not want the machine or computer to recognize.

![Screenshot of the interface of Teachable Machine’s Image Project](https://miro.medium.com/max/1400/1*N_JK92O0M0e2aLUo_9KvCA.png)

For example, I made three keys, each with their unique variegated patterns. I wanted my computer to be able to recognize them individually. I named the keys ‘Candy,’ ‘Blossom’ and ‘Sunny’ (for my own visual recognition sake) and created separate classes for each of them.

![Three different crocheted keys that I named - Candy, Blossom, and Sunny](https://miro.medium.com/max/1400/1*XUD3Dml4dTlS-CfKdjSQMw@2x.png)

For each key’s class, I used the ‘webcam’ option to feed as many images as possible for that key. I also created a fourth class called ‘Empty’ because I also trained my computer on what it sees when there is no key in view.

![Screenshot of feeding images of a key via Webcam to Teachable Machine](https://miro.medium.com/max/890/1*OGg1OP15Mxq4g6IWFiOh6A.png)

Once data is fed, the next step is to ‘train the model’. This takes some time depending on the number of images, so it is recommended not to switch browser tabs while the training is ongoing. The result of the training can be viewed in the preview window to the right, which also lets you test your trained model.

![Screenshot of training the Machine Learning model through separate key image classes on Teachable Machine](https://miro.medium.com/max/2400/1*Wx13hBVZRV7am2JH7nY20Q.png)

When I presented the reverse side of Candy to the camera (image below), the model was only 78% confident that it was seeing Candy and 22% confident it was seeing Blossom. This confusion occurs because both Candy and Blossom share similar visual features from their source material but are still different enough to be recognized on their own. We can take advantage of this model uncertainty by creating several look-alike objects that are memorable to us (because we make them) but not easily distinguishable to the machine. This is the opposite of the “10000 bowls of plain oatmeal” problem found in procedural generation algorithms, where a machine can generate 10000 bowls of oatmeal with each oat in a different size and orientation. While every oat is mathematically unique to the machine, the human cannot distinguish them nor appreciate their uniqueness. The crochet-key flips this problem around by queering the objects and the training data. Using variegated yarn in this way can help to play within the boundaries of the object detection machine learning models.

![Screenshot of testing key-recognition via the preview window of Teachable Machine ](https://miro.medium.com/max/1400/1*lxpaxY2RwAFgwXkIs-GNUQ.png)

What is also attractive about TM is that the training happens locally in your browser and not elsewhere on the ‘cloud’ network, which means it is possible to download and run the TM model offline, thus allowing you to secure your project even further. This is possible by exporting your trained model using the TensorFlow framework — an open-source framework that supports machine learning on edge devices (e.g. on a browser window, on a tiny computer such as Raspberry Pi, or even a microcontroller such as Arduino Nano BLE Sense). For the remainder of the tutorial, I will demonstrate how you can create an offline secure application of the cryptocrochet-key TM model on a smaller computer i.e. the Raspberry Pi 4 using TensorFlow.

#### Part 3: CryptoCrochet-Key on a Raspberry Pi 4 with TensorFlow
We have come a long way! But truth be told, we still have some way to go and this is my least favourite part of the tutorial because it is the most technical and the part I feel least confident about. However, it is a crucial section as it adds another layer of security to the project.

You will need a Raspberry Pi 4 to go on from here. Sadly, the previous versions of RPi do not have sufficient processing power to run TensorFlow on them. Additionally, you will need a Raspberry Pi Camera Board v2 and a display board so you can see what the RPi 4 is seeing and recognizing. For the display, I used a PiTFT 2.8" Resistive Touchscreen board that I already had at home, although [Adafruit](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4) recommends an all-in-one board called BrainCraft HAT that is tailored especially for Machine Learning with RPi 4. I know this is a lot of expensive gadgetry to ask of a beginner or amateur maker, so if you can access a maker/hackerspace in your local area that allows you to borrow or rent this equipment, I would recommend that instead. There’s also a learning curve to this part of the tutorial but I think pushing through it can help to overcome the fears that some of us hold for typing terminal commands to install libraries and other software dependencies. In other words, if you are new to hardware making/hacking, consider this a learning experience than an implementation.

![Testing key-recognition via a Touchscreen display and a Raspberry Pi running the Machine Learning model on Teachable Machine.](https://miro.medium.com/max/1400/0*mDYEjJSUxK1uK_JP)

I followed this Adafruit [tutorial](https://learn.adafruit.com/teachable-machine-raspberry-pi-tensorflow-camera/getting-started) (by Andrew Reusch) to help me run the CryptoCrochet-Key TM model on Raspberry Pi 4. The tutorial is generally comprehensive, especially the TM part. However, I realised that there is actually a LOT of software setup and installations to be made for the RPi 4. I found help for this in another tutorial, but to save time, I will list out the steps I followed with links to each of them.

Step 1: [Initial setup on RPi 4](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/initial-setup).  
Step 2: [Display setup for both BrainCraft and Resistive Touchscreen](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/display-setup).   
Step 3: [Camera setup and test](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/camera-test).   
Step 4: [Install TensorFlow](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/tensorflow-lite-2-setup) (yes, the title says TensorFlow ‘Lite’ but it actually installs TensorFlow).   
Step 5: [Visit TM and create classes](https://learn.adafruit.com/teachable-machine-raspberry-pi-tensorflow-camera/create-categories) (you already know this :)).   
Step 6: [Capturing images via RPi’s camera](https://learn.adafruit.com/teachable-machine-raspberry-pi-tensorflow-camera/use-raspberry-pi-camera).   
Step 7: [Train model](https://learn.adafruit.com/teachable-machine-raspberry-pi-tensorflow-camera/use-raspberry-pi-camera).  
Step 8: [Export TensorFlow model from TM and transfer onto the RPi 4](https://learn.adafruit.com/teachable-machine-raspberry-pi-tensorflow-camera/transferring-to-the-pi).   

![A moving GIF image showing how the Machine Learning model fails to accurately recognize the crochet keys.](https://miro.medium.com/max/1200/1*bYYIgwKHUbfwrOZ5PX8j1g.gif)

Following these steps may require some patience and gut-feeling, especially if you are a newbie to terminal commands. It does work eventually! I even managed to play with the model’s uncertainty e.g. the GIF image above shows the model’s inability to distinguish between Candy and Sunny. In the end, I never deployed this project as a home security system because part of the fun was just seeing if I could and for it to be a learning experience.

## Licensing Information 
This tutorial is licensed under the Creative Commons Zero v1 (CC0 1.0) Universal license.

## Further Readings
1. Ahmed, Sara., & Stacey, Jackie. (Eds.). (2001). Thinking through the skin. Psychology Press.
2. D'Ignazio, Catherine., & Klein, Lauren. F. (2020). Data feminism. MIT press.
3. Garland Thomson, Rosemarie. (1997). Extraordinary bodies: Figuring physical disability in American culture and literature. Columbia University Press.
4. Hellstrom, Maria. (2013). Knitting ourselves into being: The case of labour and hip domesticity on the social network Ravelry. com.
5. Orton-Johnson, Kate. (2014). Knit, purl and upload: New technologies, digital mediations and the experience of leisure. Leisure studies, 33(3), 305-321.
6. Skeggs, Beverley. (1997). Formations of class & gender: Becoming respectable. Sage.
