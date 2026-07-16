# This is the basic readme.md for this project what are th properties and external things we use to build this project with the tailwind css 

```
--- first step is the setup of the tailwind css , node modules , bootstrap and vite for this twitter clone project 
```

```
--- We have to build the twitter clone it container the three different section inside the one container we build these three section one by one 
```

```
lets style the container  with the tailwind css property:-
.class=" container bg-black text-white mx-auto flex"
mx means margin in x auto 
```


```
--- Lets start with the section 1 :-

1.twitter logo inside the different div and we find the twitter logo in original twitter website inspect logo outer html copy and paste

2.the whole sidebar making in different div inside this div we make different different list and inside that list we gave the google font symbol and description for that symbol   href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0" />  return this globally in html page and uses it for diff-diff symbol.

3.for the  user profil section we use another div for that and for profile image we copy paste it the image 

*** CSS PROPERTY APPLY IN SECTION 1 :-

(1) w-[40%] = this is width or w-1/2 or w-full sticky top-0 for the sticky sidebar.  
(2)invert means logo invert like transparent mx-2 , py-2 for margin and padding 
(3)sidebar display flex , flex-col , text-2xl , space-y-2.5 , justify-centre/start, items-centre/start , hover:'different property',text-color,text-centre
(4)userprofile invert flex property , size , border ,  relative top to move the element in two dimensinal , ml,mr,mt,mb,pl,pr,pt,pb for margin and padding 

```

```
--- Lets start with the section 2 :-

1.we create the div and inside it we create the two div for for you and following which taking half-half width

2.then we make the div another for the profile logo inside it we use image tag for logo and input tag for the user input 

3.then we make another div for some globe symbol and text inside this div all the symbol comes from google font symbol website https://fonts.google.com/icons 

4.then we make the another div for the all the symbol and create another div for the show post option

5.Now we create the separate div's for the diff-diff twitter post and inside it separate div their is img,many div tag , span tag , all list tag.


***CSS PROPERTY APPLY IN SECTION 2 :-

(1)border-r/l-[0.25px] for left/right border w-full for full width (flex :- justify-centre/start items-start/ space-x/y , gap ) centre  , w-full , w-1/2 font-bold , hover:'cursor pointer or differentt property'
(2)invert means transparent generally use for logo w-full , border-none , flex:- gap, p , m for padding and margin mx-auto(auto margin in x direction )
(3)for show 492 posts ke liye my (flex:- justify-centre ,items-centre) ki jagaha my  (text-centre) bhi use kar sakta hu 

```

```
--- Lets start with the section 3 :-

1.for section third w-[70%] we create the ddiv and inside it we make the input tag for search 

2.we make another div for subscribe to preminum section and inside it their is h1 , p , span/button tag inside this div 

3.we make the another div and inside it h1 tag for how to follow section and inside this div we also have the list section inside it their is the symbol from google symbol website 

4.then we make the another div inside it in h1 tag whats happening section and their is another div inside this div for other trending in india news 


***CSS PROPERTY APPLY IN SECTION 3 :-

(1) for section third w-[70%] , or w-1/2 or w-full , m ,p mx , my ,px , py ,  mx-auto ,my-auto , px-auto ,py-auto , ml,mr,mt,mb,pl,pr,pt,pb  m is for margin and p is for padding ,  text-color ,text-centre , text-2xl/xl,xxl,xxxl , for text color,alignment,size
(2) rounded-full (border fully rounded) bg-color ,  rounded-4xl/3xl/2xl , font-bold , (flex:- justify-start/centre , items-start/centre , gap , space-x/y-) ,  hover:"proeperty apply when hover"
(3)Most important property of tailwind css is media query for this we use the md ,sm,lg,xl,2xl for responsiveness of the websites   

```


###External Sites Help to build this project

1.https://fonts.google.com/icons  for the symbol logo of sidebars .

2.https://tailwindcss.com/docs/responsive-design#targeting-a-breakpoint-range  for basic setup and responsiveness 

3.https://play.tailwindcss.com/ tailwind play for seen the side by side preview of the making of website (mostly useful for rough work for creating the website)

4.(npm i vite) is useful for live preview of my website without any referesh