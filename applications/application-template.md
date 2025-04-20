# 📝 ConnectMag

## 🌟 Project Overview

Please provide the following:

- If the name of your project is not descriptive, a tagline (one sentence summary): **Connect Mag - Never miss a connection again**
- A brief description of your project: **Here is a video that we made for another grant that gives a great overview into our vision with this product https://drive.google.com/file/d/1VNKXzMVpD0qXZYxSg-xW63Bsl6BfsPGA/view?usp=sharing and https://drive.google.com/file/d/1OuNUippJbqXiGAKMWSjGXXhk-tfdMHfs/view?usp=sharing**
- An indication of how your project relates to / integrates into Polkadot: **We’re exploring how Polkadot can power the backend identity and verification infrastructure for ConnectMag. By using Polkadot’s secure, decentralized identity systems and cross-chain interoperability, we can allow users to verify credentials, store links to blockchain-verified resumes or portfolios, and connect their QR magnet to NFTs or smart contract-enabled professional profiles. With POAP, each interaction or event where ConnectMag is scanned can trigger a Proof of Attendance Protocol collectible, creating a verifiable, blockchain-based record of professional milestones—like networking at a startup summit, participating in a panel, or attending a demo day. These POAPs become part of your personal Web3 memory book and unlock new layers of community, access, or recognition.**
- An indication of why your team is interested in creating this project: **Everyone is using qr codes now (https://www.instagram.com/reel/DHMHXYhSR1B/?igsh=MTc4MmM1YmI2Ng%3D%3D), but what happens if your brightness isn't turning up or your phone dies? We want to help solve that issue with a simple one second application product, a magnet. Leah and I attend a lot of networking events. Even as students, we make time to attend at least one event a month in the Bay Area region. Additionally, my mentor (Mark Lin - built a 2 million revnue generating business and was on shark tank at 17 years old) will help us get partners, the right hires, and manufactuers to turn this dream into reality. We believe this is the future of networking—frictionless, secure, and unforgettable.**

### 🔍 Project Details

We expect applicants to have a solid idea about the project's expected final state. Therefore, please submit (where relevant):

- An overview of the technology stack to be used: **While ConnectMag is not a tech product at its core, but rather a consumer accessory, we strongly believe it presents a meaningful opportunity to bridge physical interaction with digital identity in the Web3 space. Our vision is to explore integrations that make these interactions more secure, verifiable, and memorable using tools like Polkadot.**

Frontend (possible): **Mobile-responsive web app that is accessible via QR scan**
Backend (possible): **Node.js with Firebase or Supabase for initial user data + Polkadot smart contracts for on-chain components**
Web3 Components (possible): **Polkadot.js for DOT-based wallet login + identity features, POAP minting via POAP API or SDK, NFT integration for tokenizing professional credentials or attendance**
QR Scanning: **Device-native scan → redirect to digital business card, resume, or verified profile**
Authentication (possible): **Web3 login or OAuth2 integration for syncing LinkedIn, GitHub, etc.**

- Documentation of core components, protocols, architecture, etc. to be deployed
**We are in early stages of developing the ConnectMag Web3 bridge. Current architecture goals:
QR Scan → Web App → User Profile
Integration Flow: Trigger POAP claim (if at qualifying event), log interaction with smart contract
Modular smart contracts for: POAP event linkage, verifiable credential storage (via Polkadot parachain), User permission for displaying identity badges**

- Any PoC/MVP or other relevant prior work or research on the topic
**The idea is simple. So, the physical QR magnet with custom engravings and scannable links to professional profiles (e.g., Linktree, personal websites) is simple to get. But, we are
currently working on a React-based mockup of the user interface for digital profile management + POAP claim flow.**

- Mockups/designs of any UI components
**https://www.canva.com/design/DAGjsCZsKJo/Iv8EExFA3EWWWY6XBrjaRQ/edit?utm_content=DAGjsCZsKJo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton**
Here how it works: 
**Users will begin by visiting our website, where they’ll input the professional links they want their ConnectMag to lead to—such as a Linktree, personal portfolio, LinkedIn, or a verified ConnectMag-hosted landing page. From there, they can choose between a sleek black magnet with a white QR code or a white magnet with a black QR code. For an additional charge, users can fully customize the color of both the magnet and the QR code, using either a curated palette or their own brand hex codes. Once submitted, the QR code isn’t just a sticker—it’s laser-engraved or UV-embedded directly onto the magnet for a premium, durable finish. If their phone case doesn't connect to magnets, we will offer a adhesive-backed metal plates that can be attached to the back of the phone or case. These can be affixed with tools like 3M adhesive strips or Magnetic Mounts that allow for the seamless use of the magnet. The magnet itself is slim, lightweight, and designed to attach securely to the back of a phone case while remaining easy to remove or swap out. After it’s manufactured, the ConnectMag is shipped directly to the user’s address and ready to use out of the box—no app required. Anyone who scans it is instantly taken to the user’s professional profile, making networking fast, sleek, and frictionless. We plan to integrate Web3 functionality by allowing ConnectMag users to receive POAPs (Proof of Attendance Protocol tokens) at events or meetups as digital keepsakes of meaningful interactions.**

**Alternatively, we are working to partner with major conferences like Dreamforce, where the ConnectMag process will be adapted to fit the event experience. In this model, attendees will receive a ConnectMag on-site that is pre-linked to their registration profile or badge info, allowing for fast, seamless networking without any setup needed. Users can opt to update their links post-event via our site, but the initial onboarding is handled in collaboration with the event organizer. We plan to integrate Web3 functionality by offering POAP (Proof of Attendance Protocol) drops tied to ConnectMag usage—letting users collect digital memories from professional events they attend and people they meet at the start.**

- Data models / API specifications of the core functionality
**The core functionality of ConnectMag revolves around generating and linking QR codes to professional networking profiles. The data model will store the user’s personal and professional links, including but not limited to LinkedIn, personal portfolios, and social media profiles. The QR code will be dynamically generated based on these links and embedded directly onto the magnet. An API will be provided for user profile management, enabling easy updates to links and customization options. The API will handle user authentication, profile updates, order management, and color customization. It will also provide real-time data for users to monitor QR code scans, allowing for analytics related to networking activity. We will also be using blockchain technology from Day 1.**

- What your project is *not* or will *not* provide or implement
  - This is a place for you to manage expectations and clarify any limitations
 
**While this might seem like a pro or con, depends on who you are, we don't store any personal data beyond the user’s links for the QR code. We do not store or analyze extensive personal user information. Additionally, unless we partner with a niche company, the system is designed to link to basic networking profiles and is not currently set up to integrate with every professional or social platform (e.g., specific internal company networks or niche platforms).**


### 🧩 Ecosystem Fit

Help us locate your project in the Polkadot landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
**ConnectMag fits into the ecosystem by bridging the gap between physical networking at conferences and the digital professional world. The core function of ConnectMag revolves around using QR codes on magnets that link to a user's professional profile, creating a seamless and efficient way to network during events. This aligns with Polkadot's strengths in interoperability and cross-chain messaging, which could support future integrations like POAPs (Proof of Attendance Protocol) or other blockchain-based credentials. As conferences and professional events increasingly turn to Web3 for digital credentials and collectibles, ConnectMag is poised to integrate into this trend, offering attendees and organizers a smooth, tech-enabled networking experience.**
- Who is your target audience?
 **Our target audience includes professionals, students, entrepreneurs, and event attendees—anyone who participates in networking opportunities, conferences, or professional gatherings. This could range from individuals seeking to improve their personal brand to companies looking to provide innovative business cards or networking tools at events. Additionally, conference organizers could be a major target, allowing them to integrate ConnectMag for seamless attendee interaction. We also see potential in Web3 enthusiasts who are attending digital and physical events that reward participants with collectibles like POAPs.**

**Because we are based in San Francisco, a conference hub, we are in the perfect place geographically to build this product.** 

- What need(s) does your project meet?
**Traditional networking methods—such as paper business cards or manually typing out URLs( or mispelling someone's name when searching them on linkedin)—are often inefficient and outdated, especially in high-energy conference environments. ConnectMag addresses this gap by providing an easy and streamlined solution for networking. The typical method of having a QR code stored on your phone can be problematic; it requires users to navigate through their phone or clutter their screens with unnecessary apps, creating friction when trying to connect quickly. By embedding the QR code directly into a sleek, durable magnet, ConnectMag offers a hands-free, instant connection to your professional profiles, eliminating the need for fumbling with your phone or sharing long links.**

**The magnets are designed with high-quality materials—using premium adhesive-backed magnets that securely attach to your phone case without damaging it. Unlike other solutions that might cause scratches or leave residue, ConnectMag’s magnets ensure no harm to the phone's surface. Additionally, the QR code is directly integrated into the magnet, not a sticker, so it remains a permanent, clean, and accessible part of the design. This ensures a safe, non-intrusive experience for users, making networking at conferences or events faster and more efficient. The product is designed to be removable without causing any damage, offering both functionality and protection.**
- Are there any other projects similar to yours in the Polkadot ecosystem?
  - If so, how is your project different?
  - If not, why might such a project not exist yet?
 
**Currently, there are no projects in the Polkadot ecosystem directly focusing on the intersection of physical professional networking and Web3 integration for conferences. Most Polkadot projects tend to focus on DeFi, gaming, or tokenized assets. ConnectMag differentiates itself by offering a physical product (magnet with embedded QR code) that links directly to digital professional profiles and offers potential for POAP integration to memorialize events.**

**A project like ConnectMag may not yet exist within Polkadot because most blockchain-based solutions are primarily digital, focusing on decentralized finance or digital assets.**


> **Note**: We prioritize projects building on Plaza/Polkadot Hub, games, and DeFi applications, though all types of projects will be considered.

## 👥 Team

- **Team Name:** Name of your team. If you apply as a legal entity, please use its name.
- **Contact Name:** Full name of the contact person in your team
- **Contact Email:** Contact email
- **Website:** Your website, GitHub org, blog, or similar

**We are ConnectMag. Currently it consist of the Founder (Emily Gorodetskiy), Co-Founder (Leah Mordehai), and our Advisor (Mark Lin). With this grant, we will add more professionals to our team. 
Email: emgorodetskiy@gmail.com 
In the process of buying the domain "connectmag.org/"**
### Team members

Please list the legal name of all grant beneficiaries. Solo developers (1-person teams) are eligible for funding. 
**Emily Gorodetskiy 
Leah Mordehai** 

#### LinkedIn Profiles (if available)

**https://www.linkedin.com/in/markjlin13/ 
https://www.linkedin.com/in/emily-gorodetskiy/ 
https://www.linkedin.com/in/leah-rose-mordehai-332814344/** 

### Team's experience

Please describe the team's relevant experience, including any previous blockchain projects or contributions to the ecosystem.
**Emily's experience reflects a deep involvement in entrepreneurship, leadership, and community engagement, with significant accomplishments across various initiatives, particularly in the startup and nonprofit sectors. Some key highlights include:**
**- Youth Entrepreneurship Association (YEA): Executive Director, managing over $60k in funding and a national network of 300+ students. Coordinated events, fundraisers, and a weeklong entrepreneurship program for young students.**
**- Junior Economic Club (JEC): As President, led strategic planning, executed events with major companies (Goldman Sachs, Affirm, etc.), and broke attendance records. Additionally, secured a grant to support a spring forum in FiDi.**
**- Used blender and unity to code a Virtual reality app that is now used as a civic engagement tool aimed at overcoming language barriers and educating underprivileged communities on the voting process. Secured 15k in funding.**
**- ConvoSearch: Worked as a Business Development Intern for this Bay Area-based startup, focusing on business development and sales strategies for lifestyle and e-commerce brands. Contributed to efforts in attracting VC investors.**
**- VentureEd: As a fellow and advisory board member, Emily gained hands-on experience in technology and entrepreneurship, contributing to the development of an AI-powered mental health app and taking on leadership roles in decision-making.**
**- KARMEQ: Currently serving as a Youth Financial Literacy Advisor for this startup focused on promoting early wealth-building through innovative stock-gifting platforms.**

**Mark:  A seasoned entrepreneur with expertise in consumer packaged goods, bootstrapped businesses, and social media marketing. In 2020, he founded Sliimeyhoney, the world's gourmet slime company and has scaled it to over $2M in revenue and 1 million followers across social media platforms and even pitched it to investors on ABC's Shark Tank. He has a passion for all things business that involve strategy, creativity, and communication. In addition to being an entrepreneur, he has been a product consultant at Adobe, Product Marketing Consultant at Microsoft, and was a Venture Capital Fellow at Comma Capital. He is currently studying business economics and cognitive science at UCLA.**

**Leah: She is an intern at the California Treasuer's office, was a Civics Unplugged Fellow (where she examined the most vexing problems facing the U.S. and the world and create solutions that bridge foundational principles with emerging technology and new schools of thought), and interned at OurCo (a social platform that reimagines how communities communicate and make decisions).**

## 📊 Development Status

If you've already started implementing your project, please provide a link and a description of the code. Otherwise, please provide some documentation on the research and other work you have conducted before applying.

**With Leah's connections at SalesForce, Linkedin, and PayPal, we are getting confirmation on the integratation of our product at local conferences like Dreamforce. We will provide an update from our meeting with the Dreamforce team soon! For instance, Leah attends UHS in San Francisco, where a lot of successful tech founders send their children. One of them includes the CEO of Paypal. Mark was litterly on Shark Tank and he is helping us establish the paperwork for our LLC, and draft up contracts between us and the conference hosts. In terms of documentation, we have done an in depth market analysis. Here are our results:**

**ConnectMag stands out from products like those on Zazzle and Wholesale Magnetic Signs (B2Cs) by offering a more specialized and professional networking solution. Unlike generic QR code magnets, ConnectMag is designed specifically for business networking at events, conferences, and conventions. As these eventsare our main target audience and we aim to be a B2B company. We use premium adhesive-backed magnets that are carefully tested to ensure they do not damage phone cases, and the QR code is embedded directly into the magnet, offering a durable, long-lasting solution that won’t wear out or leave residue when removed. Additionally, ConnectMag is compatible with various phone cases, using high-quality materials that ensure a secure fit without interfering with the phone’s surface. For users who don’t have a phone case that magnets can connect to, we provide an easy solution with customizable adhesive-backed metal plates that can be attached to the back of the phone or case. These can be affixed with tools like 3M adhesive strips or Magnetic Mounts that allow for the seamless use of the magnet. Furthermore, ConnectMag adds value by integrating POAP functionality, enabling users to collect blockchain-based digital memorabilia from events, which is a feature that competitors don’t offer. The combination of professional design, high-quality materials, and the ability to integrate Web3 features makes ConnectMag a superior choice for anyone looking to enhance their networking experience in a professional setting.**

## 📅 Development Roadmap

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, please describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality.

**Important notes:**
- Each milestone is capped at **$5,000 USD**
- Milestones must be delivered within **3 months** of approval
- The maximum grant amount is **$10,000 USD** per application (up to **$15,000 USD** per project in exceptional cases)
- You will only receive payment after successful milestone delivery

### Overview

- **Estimated Duration:** 3 Months 
- **Full-Time Equivalent (FTE):**  1 Full Time Developer 
- **Total Costs:** $10,000 USD 

> Note that deliverables 0a to 0d are mandatory. Please adapt their specification to your project.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | ConnectMag will operate under a Proprietary License, where intellectual property rights remain with the company while users are granted usage rights for their customized QR code magnets. This will also cover our blockchain-based functionalities built on the Polkadot network, protecting the unique process of linking physical QR codes with blockchain-backed digital experiences.|
| 0b. | Documentation |We will provide clear product documentation outlining the ordering process, customization options, and usage instructions for customers. This will include a detailed guide on how users can link their QR codes to professional networking sites, how the Polkadot-based integration works, and how users can claim POAP tokens as digital collectibles on-chain. A simple FAQ will address common inquiries related to both the physical product and the blockchain-backed services.|
| 0c. | Testing and Testing Guide |A quality assurance process will test QR code functionality, magnet durability, and Polkadot blockchain integrations. Tests will verify QR code readability, magnet adhesion to various phone cases, and the secure, seamless user experience when connecting to blockchain-based features like POAP issuance. The testing guide will explain how these processes are validated and measured for both physical and blockchain components. |
| 0d. | Article | We will publish an article detailing the development of ConnectMag, covering the design and manufacturing process, its use in professional networking, and the integration of Polkadot blockchain from the very start of development. The article will explain the rationale for choosing Polkadot, how it enhances security and interoperability for features like POAP issuance, and the broader impact of merging physical networking tools with blockchain-backed digital collectibles. |
| 1. | Custom QR Code Integration (Actual Creation)| From Day 1, we’ll develop a feature allowing users to generate unique QR codes linking to professional sites, with a Polkadot-based identity integration. Users will input their information via a secure web interface, generating a QR code that links to their digital profile while integrating blockchain functionality for token issuance and on-chain verification. This milestone includes finalizing our manufacturer and ensuring the Polkadot integration is embedded into the product’s digital framework. |
| 2. | Magnet Customization Options | Users will customize their ConnectMag QR code magnets by choosing colors, designs, and sizes while linking their QR codes to profiles connected to the Polkadot network. The intuitive web interface will allow users to select templates or upload designs and associate their magnet with a secure blockchain-backed identity for future digital interactions and POAP collection. |
| 3. | POAP Integration for Digital Collectibles | This milestone will formalize the integration of Proof of Attendance Protocol (POAP) via the Polkadot blockchain. When a ConnectMag QR code is scanned at an event, the system will issue a unique, on-chain POAP token, securely recorded and verifiable on the Polkadot network. This enhances networking by adding a tangible digital reward system and immutable record of attendance.
|

### 💰 Budget Breakdown

Please provide a breakdown of your budget by milestone:

| Milestone | Deliverables | Cost (USD) | Estimated Completion |
| --- | --- | --- | --- |
| 1 | Custom QR Code Integration & Magnet Customization | $5,000 | 1.5 months |
| 2 |Magnet Attachment Solutions (for phone cases without magnets) | $3,000 | 1 month|
| 3 |POAP Partnership for integration for Digital Collectibles	| $2,000 | 0.5 months|
| **Total** | | **$10,000** | **3 months** |

## 🔮 Future Plans

Please include:

- How you intend to continue development after the Fast-Grant
- Any plans for seeking additional funding (other grants, VC funding, etc.)
- Your vision for the project's growth and impact in the Polkadot ecosystem

**After the completion of the Fast-Grant, we intend to continue developing ConnectMag by expanding its features and reach. We will focus on refining our platform to include even more customization options for users, such as allowing for various magnet designs and integrations with additional professional networking sites. After the grant, we plan to focus on scaling our product, expanding our partnerships with major conferences like Dreamforce, and launching targeted marketing campaigns to increase awareness and adoption.**

**In terms of funding, we have applied for a £1,000 grant aimed at young entrepreneurs, and will continue to seek other funding opportunities, such as additional grants or venture capital, to help us expand operations, enhance the product, and grow our user base. We anticipate using the Fast-Grant funding to establish a strong foundation and will continue to build upon it for future growth.**

**We envision ConnectMag becoming a go-to tool for professionals at events, conferences, and networking opportunities, seamlessly integrating digital technology and real-world interaction. Through its continued development, our goal is to make ConnectMag an essential tool within the Polkadot ecosystem, helping users connect in meaningful ways with an emphasis on security, customization, and blockchain-enabled rewards.**


## ℹ️ Additional Information

Here you can add any additional information that you think is relevant to this application, such as:

- Work you have already done
- If there are any other teams who have already contributed to the project
- Other funding you may have applied for


Remember that the Fast-Grants Programme is designed as a first step for promising projects. We're looking for projects that can continue to grow beyond this initial funding.
