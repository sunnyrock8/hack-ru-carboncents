# CarbonCents

## Inspiration

We chose to make a project like this for a variety of reasons and based on a variety of motivating factors. The government's implementation of large scale digitisation of transactions and the carbon credit system, made us realise that we could capitalise on this to make an impact on society. In addition to that, up until now sustainability was rarely incentivised. It was often the harder, more expensive process. Our app helps circumvent these issues and reward the users for their efforts.

Our usage of blockchain promotes security and general accessibility and tradability across the world. At the same time, as the app's user base grows, so will the value of our cryptocurrency. Therefore users and vendors will be rewarded for their loyalty and continued faith in the platform, promoting a new way to be sustainable

## What it does

An app that allows you to track and reduce your CO2 emissions, while also being rewarded for the process. The app's main feature is for the user to be able to scan QR codes at public transport stops such that they can start and stop a journey by scanning the QR code at the start and stop stations respectively. Based on the distance traveled the app calculates an estimate of how much carbon emission has been avoided compared to the average transport emissions. Based on the reduction in emission, the user is awarded with a calculated amount of cryptocurrency tokens. These tokens can then be used by the user to cash out and earn money through sustainable travel or directly purchase goods via an e-commerce platform available within the app. The app also has an AI assistant that helps people effectively embed sustainable travel into daily life errands without compromising on convenience, and operates on a general gamified methodology to promote engagement.

The business works by combining all these processes with partnerships with vendors, which allow consumers to seamlessly purchase goods through the app. It also works by using the eliminated emissions data to receive carbon credits (a carbon-saving reward system government) from the government. These credits can then be sold for revenue. Revenue can be reinvested into the development process and can also be used to maintain the value of our cryptocurrency at a fairly stable level.

## How we built it

We started the frontend development by creating a few design iterations and hand-drawn wireframes. Putting down our ideas on paper helped us evaluate each option and decide on one to move forward with. We settled on the most user-friendly design which managed to isolate the user from the complex calculations and processes on the backend and reduce the barrier to entry for the not-technically-adept. We then used Flutter to make the pages we had decided upon, while adding upon and editing our original designs as we went, based on what we thought the ideal user flow was.

The backend was a similar story, starting with a rough storyboard of a Blockchain-based app that magically tracks carbon footprints to a tangible output based on math. As we started building the project, one of our foremost concerns was addressing scalability, especially considering that we decided to use Blockchain. We settled upon using the Internet Computer protocol because of its undeniable elegance, Web 3.0 brilliance, and scalability. From here, we based the project around a modular Django backend that let us prototype rapidly, while also maintaining a relatively scalable system.

## Accomplishments that we're proud of

One of the things we're particularly proud of is being able to implement the actual functionality in most of the app, rather than just a prototype. We built the entirety of the backend for the current app and make everything functional - every button on the app is actually linked with a valid backend call. We spent a lot of time on this to not just make a proof of concept but take a solid step towards building a finished product, including a completely functional admin panel with Django. Another thing we're proud of is being able to implement a cryptocurrency-based transaction system on the Internet Computer (IC). The only part of this that we did not complete is deploying this to the main IC network, since we ran it on a localhost simulation of the IC network.

## What we learned

There's a couple of important lessons we learned here. The first and one of the most important was division of labour. 36 hours is pretty tight to build an app like this, especially considering that we implemented a backend. To make it on time, we had to prioritise. I (Aarush) worked on coding the frontend, while Zene and Nayan coded the backend, and Juhi helped with all our design work. We faced quite a few technical lessons too while dealing with an insanely overwhelming number of bugs during development. One of these required bugs us to rewrite a Flutter library to get the connection to the Internet Computer working properly. I have always been more of a frontend developer than backend, so working on this project in a full-stack capacity (using StackOverflow, of course) taught me a fair bit of working with Django. We also learned some valuable time management skills, the most memorable of which is letting shuffle handle the music playlist, and not wasting time skilfully selecting each song!

## Challenges we ran into

As college students, a lot of aspects of this project were entirely unfamiliar to us. Particularly, while each of us has always taken an intellectual interest in researching Web 3.0, none of us had ever attempted to implement it on such a scale. We ran into quite a few problems integrating the Internet Computer within a Flutter app, partly because of poor community support for the Dart package, and spent several hours on the first day of the hackathon.

### Design and Prototyping Philosophy

We realised early on that spending too much time on design or prototyping was not wise, especially in a time-constraint scenario like this. We decided to enact two practices that would help us not only speed up the process but ensure that it is the best possible design, as mentioned in the Frontend Section. The first method is to build and test with a quick 'turnaround time'. This helped us deal with errors and changes much faster. The second was making a single page in multiple passes.

## What's next for Carbonix

There are a few improvements in terms of scalability that we feel would help us move towards universal access and also improve the user experience. We are looking forward to gamifying our UI even further, with these design changes being motivated by user surveys to promote engagement even further. We also hope to expand into more cities and more travel modes, and to partner with governments to get live data for transport services to provide real-time updates.

### Government Partnerships

The first step forward would be to partner with the local transport authority in New Jersey to ensure that our QR codes are present in visible places at public transport stations, such as trains and metros. The next stop is to target bus stations, which would be harder to accomplish given their sheers number and geographical range. The success of our platform in the New Jersey would serve as a proof of concept and would help make our case to and encourage other Municipal corporations. Our goal is to make this a commonplace nationwide service with the potential to expand into global markets.

### Vendor Partnerships

Partnerships with vendors are essential for a good customer experience. The more vendors we can partner with, the greater the variety of products available to users. This provides incentive for customers to continue using the app and integrating it into their routines to avail the rewards through purchases. This grows the user base and a larger user base both improve the value of our cryptocurrency and encourages new vendors and users to sign up with us. This establishes a positive feedback loop conducive to growth which is, to a large degree, self sustaining

### Internet Identity

One potential improvement is to integrate the internet identity as a potential sign up/account management method. It gets rid of the hassle of authentication, is extremely secure and ensures the sovereignty of data. While people may shy away from the idea of using a cryptocurrency, especially linked to their own phone number (and possibly blank account), the internet identity provides an alternative that inspires greater confidence.

### Personalization and Gamification

The marketplace and how often someone would use the platform varies depending on their geographical demographics, income level, etc. The AI assistant could integrate with other scheduling apps that the person uses to provide them insights on how to incorporate sustainable travel into their day with automatic daily notifications. We could introduce loyalty programs as well based on their usage levels, increasing incentives to engage.
