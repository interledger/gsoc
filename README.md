# Interledger Summer of Code

> You're early! Now is an excellent time to get set up, though. *Any* experience in our open source ecosystem will help you in your application. Don't worry about picking the perfect project yet, and just get familiar with Interledger. Not sure where to start? The [Before You Apply](#before-you-apply) section of this document is very helpful for that.

## What Is It?
### Interledger

[Interledger Protocol (ILP)](https://github.com/interledger/rfcs) is an open, neutral protocol for transferring money. Very, very small amounts of money at a time, just like the internet, or the TCP/IP protocol, to be exact. TCP/IP is the set of communications protocols used to describe a network of interconnected computers that can transport and route small packets of data between them. The biggest public network that implements the protocol is colloquially known as "The Internet". In the same way, ILP is used to describe a network of interconnected account collections that can transport and route packets of value between them. The biggest public network that implements the protocol is called Interledger.

### Web Monetization

The [Web Monetization API](https://github.com/WICG/webmonetization) is a nascent JavaScript browser API that allows the creation of a payment stream from the user agent to the website. In simpler terms, it will enable a website to get paid from the browser. ILP allows the Web to Monetization standard to add payments to the Web without being tied to a single currency or payment provider.

The standard is currently being incubated at the Web Platform Incubator Community Group (WICG) in conjunction with the W3C.

### Google Summer of Code (GSoC)
 [Google Summer of Code](https://summerofcode.withgoogle.com/) is a global, online program focused on bringing new contributors into open source software development. GSoC Contributors work with an open-source organization on a 12+ week programming project under the guidance of mentors. 

### Interledger Foundation
The [Interledger Foundation (ILF)](https://interledger.org/) was founded with the mission to broaden systemic financial inclusion on and through the Web. We are also the neutral home of the [Interledger Protocol](https://interledger.org/rfcs/0027-interledger-protocol-4/), which describes a currency agnostic payment network, and the drivers behind the proposed [W3C Web Monetization](https://webmonetization.org/) standard. We are delighted to participate in the Summer of Code this year.

## Ideas List

**Web Monetization Browser Exploration**

We're experimenting with moving some of the code from the [Web Monetization extension](https://github.com/coilhq/web-monetization-projects/tree/main/packages/coil-extension) into a browser. As part of this project, please also choose one of your favourite browsers to attempt this on and let us know in your application process.

Expected outcomes: Implement Web Monetization into a browser.
Skills required/preferred: C++, JavaScript, familiarity with a browser code base
Possible mentors: Alex Lakatos, Marcos Caceres.
Expected size of project: 350 hours
Difficulty Rating: Hard

**Web Monetization Browser Exploration**

We're experimenting with refactoring some of the code from the [Web Monetization extension](https://github.com/coilhq/web-monetization-projects/tree/main/packages/coil-extension) two separate extensions, one to be a reusable Web Monetization Agent, and a second one to be a boilerplate Web Monetization Provider.

Expected outcomes: Break up the existing Coil extension in two separate projects
Skills required/preferred: JavaScript
Possible mentors: Alex Lakatos, Nicholas Dudfield.
Expected size of project: 175/350 hours.
Difficulty Rating: Medium.

**Interledger GNAP Client**

The Interledger reference node implementation is code-named [Rafiki](https://github.com/interledger/rafiki). It's an open-source package that exposes a comprehensive set of Interledger APIs. It's intended to be run by node providers, allowing them to offer Interledger functionality to their users. We're transitioning to a use GNAP protocol instead of OAuth. The project would be to write an open-sourced GNAP client in TypeScript we could use in Rafiki.

Expected outcomes: Open-sourced GNAP client for TypeScript
Skills required/preferred: TypeScript
Possible mentors: Sabine Schaller, Alex Lakatos.
Expected size of project: 350 hours.
Difficulty Rating: Medium.

**Interledger Deployment Pipelines**

The Interledger reference node implementation is code-named [Rafiki](https://github.com/interledger/rafiki). It's an open-source package that exposes a comprehensive set of Interledger APIs. It's intended to be run by node providers, allowing them to offer Interledger functionality to their users. We're trying to provide deployment instructions for various different systems, currently Docker and Kubernetes.

Expected outcomes: Deployment pipelines for Docker and Kubernetes
Skills required/preferred: Docker, Kubernetes
Possible mentors: Sabine Schaller, Matthew de Haast.
Expected size of project: 175 hours.
Difficulty Rating: Easy.

**Interledger Example**

We also provide an example wallet in a test network with [rafiki.money](https://github.com/interledgerjs/rafiki.money). As part of GSoC, we'd like to update this to use the new `Rafiki node` instead of the earlier limited `ilp-connector`. The scope of this project could also be expanded if you want into updating the client UI for it.

Expected outcomes: Use Rafikin instead of ilp-connector in rafiki.money / update the UI.
Skills required/preferred: JavaScript, Node.js
Possible mentors: Matthew de Haast, Alex Lakatos.
Expected size of project: 175/350 hours.
Difficulty Rating: Easy/Medium.

**Anything Else**

Alternatively, if you want to propose your own idea, then please reach out to [Alex Lakatos](https://twitter.com/avolakatos), the ILF Technology Lead, to discuss your idea first.

## Before You Apply

### 1. Start by Picking a Project from the Ideas List above

Our projects are related to either the Interledger network and our reference node implementation or the Web Monetization standard. Each of the projects requires slightly different skill sets.


### 2. Join Slack

Invites are available at https://communityinviter.com/apps/interledger/interledger-working-groups-slack.

### 3. Join the Community Calls

We have open community calls on the second Wednesday of the month at 4pm UTC to discuss the latest in Interledger spec development, the implementations, and to answer any questions people have. Agendas are sent out via the mailing list, and anyone can suggest an agenda item by adding to the [topic created for that purpose in the forum](https://forum.interledger.org/tag/community-call-agenda).

Recordings of previous calls are [available on Soundcloud](https://soundcloud.com/interledger).

### 4. Get Set Up

Try to clone, build and run your chosen project locally. In the case of Web Monetization, also do that for your preferred browser.

## Application

As part of your application on the GSoC website, please provide a short CV and include answers to the following questions:
> - What interests you most about our Interledger & Web Monetization?
> - As mentors, how can we get the best out of you?
> - How do you keep yourself organized?
