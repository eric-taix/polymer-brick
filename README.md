Why polymer-brick?
-------------

WebComponents and Polymer are really awesome and every developers should have a look to these technologies.  

This project is a POC to demonstrate how to use Polymer to create a WebComponent.  
  
What is polymer-brick?
-----  
Polymer-Briwk is a web component (called a brick) which aims to display a resume of an article:  
  - title  
  - description  
  - image  
  
It also allows to share the article with some social networks (Facebook, Twitter, Google+).  
**Note:** Sharing buttons are not yet web components but it should...
  
![image](docs/polymer-brick.png)  
*Screenshot of bricks in action*  

This component has also many CSS effects which are very cool!

**Disclaimer:** I'm not web designer. Styles of this web component are really inspired by [Slate.fr](http://www.slate.fr)


How to use polymer-brick?  
----------  
 
Hey this is just a web component, so it's really easy ;-)

First import the component  
  
```<link rel="import" href="elements/b-brick/b-brick.html">```  
  
Then  use it  
  
   ```
   <b-brick    
      title="<your title>"  
      desc="<your desc>" 
      href="<link to the article>" 
      img="<the background img>"
      tw="<number of tweets" 
      fb="<number of facebook's shares>" 
      gp="<number of google+ shares>"
      >
   </b-brick>
   ```  
Et voilà!


Like it?
-------  

You can test the online [demonstration](http://eric-taix.github.io/polymer-brick/)  
It has been tested with Chrome, Safari and Firefox (it still has style issues with Firefox)
  
I created this component for fun. If you like it, just say hello to @etaix.