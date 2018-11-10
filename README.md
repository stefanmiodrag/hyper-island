
> **Note:** (This was my application to Hyper Island for 2018… Of course I got accepted.)

## Identified Problem
Reading grocery labels is complicated and exhausting. How can it be improved to become more accessible, convenient and uncomplicated?  

---

Have you ever gone to the grocery store, looked at a products label trying to figure out if you can eat it, but instead end up leaving the store confused, overwhelmed, and empty-handed? I discovered that the situation is actually common: even with frequent and competent buyers.

According to a user study I conducted, 86.7% of people said that they’ve been confused about the ingredients in the products they’ve purchased. The same percentage of people also said that they’ve left a product because they weren't sure if they could consume it. And when asking what common issues they face daily when grocery shopping, most of them mentioned trouble figuring out if they could eat something based on reading the label.

Once the problem had been identified I worked toward finding a solution. I started by defining a handful of different situations in which the application could be used:

- Busy and exhausted people with dietary restrictions or food allergies.
- Elderly or people with disabilities who struggle with reading the labels.
- People who want to avoid certain chemicals or additives. But find it difficult and overwhelming, and want assistance.
- A family member, friend or caregiver who’s buying for someone else.

I then used these assumptions to create user story maps, to better understand the problem and to identify potential opportunities. These findings helped me decide the scope of the product and what features I should primarily focus on.

## The Solution
The findings that I gathered from my online user study and in-person user interviews led me to imagine a digital product that could tell if an item is consumable depending on a person's food preference.

It would primarly be targeted to people with strict food restrictions. But could also be used for those who’d like to avoid certain chemicals or additives.

### Defining a scanning system
I conceived a scan system that could read the information of a grocery item (thanks to the barcode). This would allow the user to quickly find out if a product matches their requirements, without the hassle of having to read the label and trying to determine if it’s OK to consume.

First I had to figure out how I was going to display the different results after scanning an item. This included:

- The system determined that the item is 100 percent consumable.
- Item wasn’t in the database and therefore couldn’t conclude anything.
- It contains one, or several ingredients that the user can’t consume.

I approached it by keeping the application simple and non-intrusive. For example, you shouldn’t have to fumble with your phone in a crowded and busy store in order to get an answer to the simple question _“can I eat this?”_

So that’s just what I did. The user will only get the bare minimum information upfront, either a YES or a NO. If the product isn’t in the database the user will get a message telling them: “Thanks for scanning a product that isn’t in our database, it’ll be added shortly. In the meantime, try to scan another item."

If the user wants additional information about the product they can swipe down to get the entire list of ingredients. In the case that the product wasn’t consumable, the user will be able to see which ingredient, or ingredients didn’t pass their requirements.

### Smart recommendations
I discovered that some people already had a routine and wouldn’t purchase any product they hadn’t used in the past. Therefore I decided to create a feature that would make it so if a product was scanned that the user couldn’t consume, the application would then recommend alternatives.

It would work by matching the scanned product with similar products that are in the database.  To further improve the value of this feature, it could be based on the users geolocation and only recommend products that are the in-store.

The application would also send out notifications to users based on their preferences. For example, gluten-free users would get notifications when products are on sale or when a new product is in-store. This would help brands find their target audience and allow them to market directly to them.

### A profile system that adapts
According to my user study, 66,7% of people grocery shop for people other than themselves. I used this information to create a profile system that would adapt to different situations. For instance, a family might be looking to create a shared account. In constrast, a group of friends might be holding a dinner party and want to collect everyone’s information, making sure that no one is left with food that they can’t eat.

Let’s use the second example to showcase how the system would work. You and your friends are planning a dinner party. You head to the grocery store but quickly discover that it’s difficult to keep everyone’s preferences in mind. So you go ahead and create a profile called “dinner party”, you click ‘share’ and get a unique 4 number code that you can send in your group chat. Your friends then enter it into the application and pick what profile to share with you. Now you have all of youfriends preferences collected into one place!

It also works in both personal and professional situations. For example, you could easily use it at a retirement home, kindergarten, or even at a company.
