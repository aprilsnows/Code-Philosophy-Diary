# Code & Philosophy -- Diary
###16.2.2017
####Guest Lecture: How and why Web App security Fails? -- Antti Virtanen @SOLITA 

> Philosophy of Security: 

> "Security is risk management."

> "If you know the enemy and know yourself, you need not fear the result of a hundred battles." -- Sun Tzu, Art of War

#####RECIPE FOR SECURE SOFTWARE:

1. Design it properly. Do the right thing. 
  * Don’t roll your own. 
    * Especially, don’t invent hash algorithms, RND or crypto!
    * Seriously. Failure imminent and certain. 
  * Follow best practices. ([best practices from Futurice](https://github.com/aprilsnows/backend-best-practices#security))
  * Understand what you are doing. 
    * Read the RFC. Understand your tools and libs.
2. Do it right (Mistake in implementation = bug = security issue)
3. Prepare for the unthinkable

Resource: [SlideShare](http://www.slideshare.net/Solita_Oy/webapp-securitytut2017), [Webhack](http://www.webhack.fi/), [google-gruyere](http://google-gruyere.appspot.com/)

Tools: [Burp prox](https://portswigger.net/burp/), [OWASP Zed Attack Proxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)

Reading: [OWASP Top-10 risks](https://www.owasp.org/index.php/Top_10_2013-Top_10), [The Web Application Hacker's Handbook](https://leaksource.files.wordpress.com/2014/08/the-web-application-hackers-handbook.pdf), [Hacking: The Art of Exploitation](https://leaksource.files.wordpress.com/2014/08/hacking-the-art-of-exploitation.pdf)
