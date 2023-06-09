# JS-and-API
&emsp;  <img src="https://github.com/SKindij/SKindij/blob/main/animation/Book.gif" title="Book" alt="Book" width="20" height="20"/>&ensp; 
something :dragon: about interaction JS with APIs

#### examples of my projects

**Marvel Comics app**
* github [repo](https://github.com/SKindij/JS-and-API-practice/tree/main/marvel)
* web [link](https://marvel.maxkin.xyz/)

___

### In code 

> helper function that can be used to fetch data from an API endpoint
> > ```javascript  
> >   getResource = async (url) => { // asynchronous arrow function that takes in a url parameter
> >     // 'await' is used to wait for response to come back before moving on to next line of code
> >       // 'fetch' send GET request to specified URL
> >     let res = await fetch(url);  // response object is assigned to 'res' variable
> >       // this 'if' statement checks whether response status code is not in 200-299 range
> >       if (!res.ok) { throw new Error(`Could not fetch ${url}, status: ${res.status}`); } 
> >         // 'await' is used to wait for JSON parsing to complete before returning data
> >         return await res.json();
> >   };
> > ```
> In summary, 'getResource' function fetches data from specified API endpoint,<br> 
>   checks response status code for errors, and returns parsed JSON data if request is successful.
___

### Loading, waiting, and spinning animations.
* GIF, SVG, and APNG formats. https://icons8.com/preloaders/
* Animation Made Easy. https://loading.io/

&emsp;  The [object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) CSS property sets how the content of a replaced element, such as an ``<img>`` or ``<video>``, should be resized to fit its container.



___

### react-lifecycle-methods
<div>
  <img src="https://github.com/SKindij/SKindij/blob/main/recources/react-lifecycle-methods.jpg" 
    title="react-lifecycle-method" alt="react-lifecycle-method" width="640" height="240"/>  
</div> 





___

### [Hide](https://betterprogramming.pub/how-to-hide-your-api-keys-c2b952bc07e6) Your API Keys
> _if at some point you committed your API keys to your git repo, you should remove all traces of it. \
> You can do this by using git rebase and removing the commit that added the keys_

&emsp; Services like Google Cloud and AWS make it possible to set restrictions on the usage of the API key.

> _If you created your app with create-react-app, please be mindful of that your env variables will become a part of the build, meaning, they will be publicly available for anyone who’d inspect your files. Then, before deploying your page, delete the .env file and use the platform’s key management system ( for [Heroku](https://www.heroku.com/) or [Netlify](https://www.netlify.com/) )._


So, if you wish to totally mask your key, you should make a backend that proxies your requests, and store the API key there.





___

|     public-apis         |      web address          | additional info              |
|-------------------------|---------------------------|------------------------------|
| Ice And Fire  | https://anapioficeandfire.com/      | Game Of Thrones              |
| Catalogopolis | https://api.catalogopolis.xyz/docs/ | Doctor Who episodes          |
| STAPI         | http://stapi.co/                    | Info on all things Star Trek |
| SWAPI         | https://www.swapi.tech/             | Star Wars Info               |
| Marvel Comics | https://developer.marvel.com/       | Marvel age of comics         |
| OMDb API      | https://www.omdbapi.com/            | Open Movie Database          |
| IMDb API      | https://imdb-api.com/               | Film Rating System           |
| enders Guru   | https://tenders.guru/ua/api         | Procurement in Ukraine       |
[Public APIs]   | https://github.com/public-apis/public-apis#index | list of free APIs |

[emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
