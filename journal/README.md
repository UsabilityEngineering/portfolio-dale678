# Journal 1

 As someone who is in the middle of a restoration project on an older vehicle, it can be difficult at times to find parts. Some parts may just not exist anymore, or on the off chance that you do find a part, it ends up being sold by a sketchy website. A website that I regularly use is [RockAuto](https://www.rockauto.com/). It is hands down one of the better websites to use to find a part or even cross-reference parts across other automotive websites. Unlike other automotive websites, it uses a very simple format that follows a catalog model. The same catalog model one might use to find what windshield wiper size they need for their vehicle at the store. The catalog model in the automotive industry is very standard, where the person using the catalog finds the make, year, and model of their vehicle to find the correct part for their vehicle.
  
(Below is the landing page of RockAuto that displays its catalog-style interface)
  <img width="1920" height="1032" alt="catalog" src="https://github.com/user-attachments/assets/d82b96ec-9b44-42bc-9528-170c2dfce44b" />

(This is an example of easily accessible data that can be used to cross-reference parts in other websites)
  <img width="1920" height="1032" alt="data" src="https://github.com/user-attachments/assets/7f86c8d6-4047-4d71-91f0-ba32355116fd" />
  
However, one area where RockAuto unfortunately falls flat is handling the return to the catalog page of your selected vehicle while in the “Show Closeouts Only” section. One of my favorite sections in the catalog is the “Show Closeouts Only” section, which has a list of parts that RockAuto wants to get rid of that fit your specific vehicle. The parts that they want to get rid of are not defective or damaged goods, but rather, they want to get rid of these parts to free up storage space. Which is why some products display "Only 1 remaining".

(Example of what the “Show Closeouts Only” looks like)
  <img width="1920" height="1032" alt="closeouts" src="https://github.com/user-attachments/assets/f1d7522c-8415-4493-9719-bfc91fc78c4c" />

When I selected "Add to Cart" in the “Show Closeouts Only” section, I was redirected to the main shopping cart page. I thought to myself, "That's annoying, but there must be a button that takes me back to the section I was just on". I pressed the "Continue Shopping" button, expecting it to redirect me to the section I was just on, but it redirected me to the main landing screen, showing me a list of the makes of vehicles. This isn't a big deal, but it can get annoying very quickly. This does not create a good user experience since it makes the user feel like they did something wrong. When in reality they pressed the button that best matches their **mental model** of how a website typically works. 

(Reenactment of my experience. FULLSCREEN recommended)

https://github.com/user-attachments/assets/c96c72be-43a6-45ef-81ab-e55fcabdb600

When this first happened, I thought I must have done something wrong, but every time I retraced my steps, the same thing kept happening. It made me wonder if I was interpreting the given **affordances** incorrectly, or if my own mental model of how a typical shopping cart in a website behaves was misremembered. The more I looked into it, the more I realized it must be a mistake on the website's behalf, since there are elements similar on the website that do not behave that way. I do not know how the website is structured, but I am sure they can figure out a way to redirect the user back to the section they were just at. This minor fix can significantly increase the user's experience when shopping, and might even cause more sales. This highlights the importance of how one's own mental model can be different from others. I am certain that the button action made sense to the developer who implemented that function, and that there might be a way to actually go back to that section faster. However, the developer's mental model does not translate to what affordances are given to the user. 

A cognitive walkthrough could have solved this issue from the very start. They could have made a persona who is new to technology and have them do a specific task that mirrors the steps that I took. They would have found that instead of redirecting the user back to the section they came from, it redirects them to the home landing page.
