+++
title = "I started a blog"
slug = "atfirst_en"
date = "03 Mar 2022"
[ author ]
name = "Suhito Sagara"
+++

　In February 2022, I launched my portfolio site while I was busy with the Applied Information Technology exam.

　In March, I had a series of opportunities for interviews, including casual ones. It was also a good opportunity for me to write code and use GitHub.

　The site has a fairly minimalist structure, with only the top page, an About page, and a Posts page, which is a blog.

　On Twitter, I tweet about trivial matters, including daily life, and collect information.

　Qiita is used to share problem-solving records.

　The blog on this site is for the purpose of recording "I know this much" and "I'm doing this now" about cryptography and cyber security for the purpose of showing people (and for the purpose of looking back by myself).

# Motive
　I am of the generation where the Corona Disaster hit job hunting, so I have never properly exchanged business cards as a member of society.

　When I was an M1 student, I was allowed to make business cards in the school's designated format with the name of my laboratory on them, and I scattered them around every time I attended an event or met someone from a company.

　Although many analog matters, such as seals and other corona disasters, have been pointed out as being obsolete, I think business cards are useful, and I would like to see them revived if possible.

　What I like about business cards is that they have name, affiliation, contact information, and the ability to write notes depending on the scene of the correspondence, all of which are necessary and sufficient for remembering and recalling people you have met for the first time.

　So, this portfolio site was created because I wanted to do "this is who I am" online, even if it can't replace the business card itself.

　I feel that it is currently smart to send the URL of this site during a video conference by chat, or to include the URL in an e-mail or Twitter message.

# GitHub Pages + HUGO as an option
　Many people in the technical community use existing blogging services, and I have used them myself.

　However, in creating my own portfolio site

* URLs can easily become cumbersome
* Domain is not memorable because it is covered by others
* Limited customization
* Japanese service is not familiar to foreign countries

　We felt these disadvantages, so we created a combination of GitHub Pages + HUGO (using the friend-hello-ng theme).

　The name is linked to the GitHub account, the theme can be pulled from the designer's GitHub or created by the designer himself, and the support for Japanese and English has solved the above demerits.

　At first, we were considering GitLab Pages + Gatsby because of its reputation, but since we were still unfamiliar with GitHub Pages, we decided to go with GitHub Pages because it had more knowledge about troubleshooting, etc. Gatsby's themes are still relatively few and we felt that it was more for designers, so we decided to reject it. It does not mean that it was not good, but that it was not suitable for me.

# What I will write in the future
　Here is a systematic summary of what I would like to do in the future at this time.

* Hands-on learning security
  * Learning from HackTheBox and TryHackMe how to use various tools
  * WriteUp of HTB Retired machine

* Three purposes of public key cryptography - signature (authentication), encryption, and key delivery

* What is quantum resistant computer cryptography (especially in terms of how it is often confused with quantum cryptography)

* How much potential does the lattice structure have for cryptography as a whole?
  * Can lattice cryptography become a standard for quantum resistant computer cryptography?
  * Types of lattice ciphers and characteristics of each
  * How to crack lattice ciphers, LWE Challenge, etc.
  * A technique for cracking elliptic curve cryptography using the structure of a lattice
    * Is the lattice also effective in deciphering homomorphic mapping ciphers?

* How much of the research on conventional elliptic curve cryptography can be transferred to homomorphic mapping cryptography, and what challenges are unique to homomorphic mapping.
  * Can homogeneous mapping cryptography become a standard for quantum computer cryptography?
  * Implementation Schemes for Homogeneous Mapping Cryptosystems
  * How to decipher homogeneous mapping ciphers

　That's all.


