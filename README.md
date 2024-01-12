# PORTFOLIO

![Inc-Dev Logo](images/IncDev_Logo_Color-w-bg.png "Inc-Dev Logo")

## Cases

### Smoke Laboratory

[Smoke Laboratory](https://smokelab.pl) - e-commerce website that is focused on selling hookah tobacco, hookah, electronic smoking devices and liquids for them.

![Smoke Laboratory Cover](images/smokelab.png "Smoke Laboratory Cover")

Development of this project differs much from the standard e-commerce webside development approach as flexible and highly customizable platform was one of the core requirements. We took it seriously developing own admin panel (or CMS, content management system) that took that variability of scenarios of use of the website to the completely different level.

The developed design system was matched with company's style and brandbook to create a serious and modern picture.

Website home page:
![Smoke Laboratory Home Page](images/smokelab-1.png "Smoke Laboratory Home Page")

Website products list page:
![Smoke Laboratory Products List](images/smokelab-2.png "Smoke Laboratory Products List Page")

The design system alongside with rapid-working UI creates a beautiful image that makes client's first impression unforgettable and generates income for the website owners.

### Good Balance

[Good Balance](https://good-balance.eu) is a web platform that implements features for accounting alongside with a marketplace for business, franchise and investments finding.

![Good Balance](images/good-balance.png "Good Balance")

The project's core point is to be very flexible and allow for future support of many different features. The task was solved by building a front-end and back-end completely from the ground-up in the way that the software is not bound by the previous functionality.

Core features of [Good Balance](https://good-balance.eu):

- Announcements publishing - a part of website that gives users the opportunity to publish an announcement of the required type in order to complete the given task more effectively <br><br>
![Good Balance Announcements](images/good-balance-announcements.png "Good Balance Announcements")
  - **Franchise sale announcements** - selling a franchise through a website
  - **Business sale announcements** - selling a business through a website
  - **Finding investment announcements** - finding the investments for your business
- Invoice management tool - part of website that allows for quick creation and saving of invoices. It consists of two main parts:
  - **Invoice creation tool** - a tool that allows for quick building of invoices. The list of all its features is:
    - Invoice numeration
    - Multi-language invoices
    - Calculating the required VAT sum
    - Saving the seller information via the invoice cabinet
    - Multi-currency support
    - On-The-Fly invoice generation
  - **Invoice cabinet** - used to save the created invoices. Available to registered users and uses on-the-fly pdf files generation in order to achieve the task of getting the invoices in the correct form
- Blog - a page where admin can publish tips and answers, forms and documents, usefuls links and news in order for users to use

### MonFi

[MonFi](https://monfi.io) is an investment platform that is planned to revolutionize the way we use cryptocurrency and make crypto loans available to the public. 

![MonFi](images/monfi.png "MonFi")

At the current state, MonFi is only a crowdfinding platform but as its development continues, the core functionality of the platform is to be released.

MonFi case parts:

- Landing page
- Crowdfunding platform
- Token and ICO

#### Landing page

MonFi's landing page is designed and developed to match the overall stylistics and general trends in crypto.

![MonFi Landing](images/monfi-landing.png "MonFi Landing")

The core function of the landing page is to describe what **MonFi** is all about and show the potential client all the opportunities they will have if they start using the company's products.

This landing takes the approach of being **simple** yet **super informative** using modern design trends such as background gradients and patterns.

Main action the user is expected to engage in is Login/Register buttons in the website header that, by clicking on them, navigate the user to the crowdfunding platform.

#### Crowdfunding platform

The crowdfunding platform's goal is to gain resources to implement the projects true functionality into life. 

![MonFi Crowdfunding Platform](images/monfi-investment.png "MonFi Crowdfunding Platform")

It achieves its goal through **investment boxes**. Investment boxes differ by price and duration. The longer the box takes to complete - the greater the income is. This proportion creates great possibilities for possible investors and creates an opportunity for MonFi team to develop the platform using the given resources.

The platform supports payment with many crypto tokens and coins, including `USDT TRC20`, `USDT ERC20`, `BTC` and `ETH`. The payment is also achievable via `SEPA` money transfer.

The platform involves many interesting concepts. For example, investment packages can have many payouts. The app also has multi-level referral program that allows for better platform marketing.

#### Token and ICO

An interesting part of crowdfunding strategy of MonFi is Monfi token. 

The token itself operates on the `ETH` chain that gives great opportunities for investments as this chain is the most popular among the other chains.

The ICO is implemented via token presale smart contract and page on investment platform:

##### Presale smart contract 

Manages how the tokens can be purchased. It is called from the web UI using MetaMask or different MetaMask API compatible ETH web3 provider

##### Presale page

![MonFi Token Presale](images/monfi-presale.png "MonFi Token Presale")

It is a small dApp placed on the crowdfunding platform and has capabilities of selling the token with either ETH or USDT ERC20.

## YoterUp

[YoterUp](https://yoterup.com/) is a commercial website that combines modern design with simplicity and visual effects.

![YoterUp](images/yoterup.png "YoterUp")

Though the website is not big, it si full of micro animations and details that make the picture of the website feel full and complete. 

The site consists of 5 pages:
- Landing page - main idea about the company is described here
- For Advertisers - the page displays the information that will be useful to understand for advertisers that want to use the platform
- For Publishers - the page displays general info that publishers can use to better understand how the business model work
- Offers - page lists advertising offers from multiple services. 
*UPD: As for now, the page is not working currectly due to problems on the side of the project founders*

## Forbs

[Forbs](https://forbsab.se) is a landing page for the swedish building company. 

![Forbs](images/forbs.jpeg "Forbs")

The website has minimalistic design and offers a lot of informational content about the company including:

- Brief facts about the company
- Services list
- Contact info
- Company policies
  - Quality policy
  - Environment policy
- Company news
- Team contacts

As every other landing page, this website has action in focus - contacting the company with contact form. The contact form is implemented to suit the company's needs about the potential client's information.

## MEISER Product Finder

[MEISER Product Finder](https://meiser.pages.dev/) is a web-application that allows the users and potential clients of the company to browse catalog of systems that are available for purchase.

![MEISER Product Finder](images/meiser.png "MEISER Product Finder")

The end product consists of two parts:
- Client-facing website
- CMS for managing the content displayed in product finder

### Client-facing website

This application has technical design and features finding the products by their characteristics. It also supports different sorting options. All the system types and products are **configurable inside the CMS**

The client-facing application features:
- Minimalistic technical design that matches the main website style
- Filtering products by their attributes (containment level, installation conditions etc.)
- Sorting products by table columns
- Custom display for every type of system (every type of system has its own filters and table columns)

### CMS

As one of the requirements of the system was to have a possibility to change the list of product finder items, system types, table columns and filters, the special CMS was built in order to achieve the goal.

The CMS can only be accessible by admin. The authentication of the system is managed by Auth0 so it is secured by many standards implemented by the auth provider.

CMS functionality includes:
- Creation of system types
- Editing of system type data
- Changing the order of displayed system types
- Adding attributes to system types
- Editing which attributes of system types should/should not be displayed as filters
- Editing which attributes of system types should/should not be displayed in the table
- Editing the product information, its image and attribute values